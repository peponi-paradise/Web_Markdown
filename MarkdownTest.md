Markdown이란, 플레인 텍스트 포맷을 이용하여 쉽게 쓸 수 있게 만든 마크업 언어로 이해된다. 아래는 위키 페이지의 소개 부분이다<sup>(1)</sup>.

<br>

>Markdown is a lightweight markup language for creating formatted text using a plain-text editor. John Gruber and Aaron Swartz created Markdown in 2004 as a markup language that is appealing to human readers in its source code form. Markdown is widely used in blogging, instant messaging, online forums, collaborative software, documentation pages, and readme files.  
The initial description of Markdown contained ambiguities and raised unanswered questions, causing implementations to both intentionally and accidentally diverge from the original version. This was addressed in 2014, when long-standing Markdown contributors released CommonMark, an unambiguous specification and test suite for Markdown.

<br>

기존 *Markup*에 비해 작성하기 쉬운 것이 *Markdown*이고, 웹 또는 SW의 ReadMe 파일 등 광범위로 사용되고 있는 만큼 익혀두면 좋을 것 같다.

~~(필자는 지금까지 소프트웨어의 버전 정보 또는 Intro를 text 파일에 작성하고 있었다..)~~
<br>

이번 연습은 블로그 글쓰기용 Markdown 연습/정리가 될 것 같다.<br>연습 내용은 markdownguide.org의 Basic syntax 페이지<sup>(2)</sup>를 참조하였다.<br>특이점 : 티스토리 블로그에 올리는 경우, 자체 마크다운 규격이 있는 것 같다 (글쓰기 모드에서 마크다운으로 변경 시, 일부 적용되지 않는 기능이 있다고 경고가 발생한다).<br>실제로 적용 형태가 VS code의 확장 Markdown All in One과는 다르게 보인다. 따라서 정리 후 티스토리에서 보기 편하게 수정하면서 연습을 해야겠다.

<br><br>

### Heading
- 글의 Header 지정 : '#' 사용 (1개 ~ 6개, 많이 붙일 수록 글자 크기 작아짐)
<br>

    ```md
    # or === 가장 큼
    ## or --- 두번째
    ### 세번째
    ...
    ###### 가장 작음
    ```
<br>

- 테스트

    # 가장 큼 : '#'
    가장 큼 : '==='
    ===
    ## 두번째 : '##'
    두번째 : '---'
    ---
    ### 세번째
    ...
    ###### 가장 작음
<br>

- 주의사항
Heading 넣기 전 한 줄 비워야함. 정상적으로 보이지 않는 경우 있음.
<br><br>

### Paragraphs 
- 말 그대로 단락 작성. 단락 사이에 빈 줄을 두어 구분
<br>

    ```md
    첫번째 단락

    두번째 단락
    ```
<br>

- 테스트

    첫번째 단락

    두번째 단락
<br>

- 주의사항
의도적인 경우를 제외하고는, 단락 앞에 탭 또는 스페이스를 두면 안된다고 한다.
<br><br>

### Line Breaks
- 의도적으로 글 중간에 글을 바꾸거나, 새로운 줄을 입력할 때 사용.
\<br> 또는 두 줄 이상의 띄어쓰기로 줄 바꿈
<br>

```md
첫번째 줄<br>
두번째 줄


세번째 줄
```
<br>

- 테스트

첫번째 줄<br>
두번째 줄


세번째 줄
<br>

- 주의사항
백슬래쉬(Backslash, \\) 사용 시 줄 바꿈 인식 제대로 안될 수 있다고 함. (각 마크다운 규칙에 따라 적용될 수도, 안될 수도..) 가능하면 안쓰는 쪽으로 해야겠다.

- 특이사항
   1. \<br> 태그로 줄 바꿈 시 한 단락 안에서 같은 문단으로 취급되는데, 두 줄 이상 띄워 줄바꿈 시 다른 문단으로 취급될 수도 있는 것 같다 (VS code Markdown All in One 표시로 봤을 때..)
   2. 개행만 했을 뿐인데.. 티스토리 마크다운 모드의 경우 엔터를 인식하여 한 줄 더 개행을 하게 된다.
<br>

### Emphasis
- 글자에 주는 강조 효과 (Bold, Italic 등)
<br>

```md
**이거는 Bold**
__이것도 Bold__

*이거는 Italic*
_이것도 Italic_

***이거는 Bold와 동시에 Italic***
___이것도 Bold와 동시에 Italic___
__*이렇게 해도 Bold와 동시에 Italic*__
**_이것까지도 동시 적용 허용_**

~~이거는 취소선~~

<u>이거는 밑줄</u>
<span style="text-decoration: underline">이게 HTML/CSS style이지만 정석으로 보임</span> 출처 : stackoverflow - 아래 링크 참조
```
<br>

- 테스트

**이거는 Bold**
__이것도 Bold__

*이거는 Italic*
_이것도 Italic_

***이거는 Bold와 동시에 Italic***
___이것도 Bold와 동시에 Italic___
__*이렇게 해도 Bold와 동시에 Italic*__
**_이것까지도 동시 적용 허용_**

~~이거는 취소선~~

<u>이거는 밑줄</u>
<span style="text-decoration: underline">이게 HTML/CSS style이지만 정석으로 보임</span>
<br>

- 주의사항
1. Bold 표시하는 방법 중 \_\_ (Underline 2개) 사용하는 경우, 띄어쓰기 안하고 글자 사이에 바로 넣어버리면__Bold 적용 안되고 이렇게됨__<br>ex) Bold \_\_Test__ (O)<br>ex2) Bold__Text__ (X)
2. Italic 표시 방법 중 \_ (Underline 1개) 사용하는 경우에도_마찬가지로 적용 안됨_
3. 동시에 표현하는 방법 중 \_\_\_ (Underline 3개) 사용하는 경우도___적용 안됨___
<br>

- 결론

Bold와 Italic은 그냥 * 기호를 쓰자
<br>

- 특이사항
1. 위 주의사항에 설명 써놓은거.. 티스토리는 적용 되네..??? 깃허브 마크다운을 따라가서 그런가..
2. Underline 표시 방법 중 \<u> 역시 HTML 형식으로, HTML5에서 철자 오류 또는 주석으로 사용된다. 즉, 사용을 권장하지 않음.. CSS style을 이용하자.
<br>

### Blockquotes
- 인용문. 기본적으로는 왼쪽에 세로 한 줄 쳐져있는 박스 안에 글자가 있으나, 티스토리에서는 따옴표("") 아래 들어가며 글자가 다르게 표시됨
<br>

- 마크다운 스타일 인용문

![MarkdownStyle image](https://github.com/peponi-paradise/Blog-Image/blob/main/Web/Markdown/original_blockquote.png "MarkdownStyle image")
<br>

- 티스토리 스타일 인용문

![TistoryStyle image](https://github.com/peponi-paradise/Blog-Image/blob/main/Web/Markdown/tistory_blockquote.png "TistoryStyle image")
<br>

```md
"> " (> 기호 + 스페이스) 를 이용하여 인용문 삽입

> 단순한 문장은 이렇게 해서 사용

> 여러 단락으로 이루어진 인용문을 넣는 경우, 첫 단락 작성 후
>
> 빈 인용문을 한줄 추가한 뒤, 다음 줄에 작성

> 인용문 안에 또 인용문을 넣는 경우
>
>> 인용문 기호를 연달아 사용하면 들어감
>>> 이런식으로

> ###인용문 안에 이런식으로 다른 Markdown 요소를 넣는 것도 가능
>
> - 예를 들자면
> - 이런거?
>
> __이런것도__ **가능함**
```
<br>

- 테스트

> 단순한 문장은 이렇게 해서 사용

> 여러 단락으로 이루어진 인용문을 넣는 경우, 첫 단락 작성 후
>
> 빈 인용문을 한줄 추가한 뒤, 다음 줄에 작성

> 인용문 안에 또 인용문을 넣는 경우
>
>> 인용문 기호를 연달아 사용하면 들어감
>>> 이런식으로

> ### 인용문 안에 이런식으로 다른 Markdown 요소를 넣는 것도 가능
>
> - 예를 들자면
> - 이런거?
>
> __이런것도__ **가능함**

<br>

- 주의사항
인용문 쓸 때 윗 줄 하나 이상 비워줘야함. 그렇지 않은 경우, 제대로 적용 안될 수 있다한다.
아래는 예시

```md
이렇게 쓰면 인용문 제대로 안들어가는 경우 있음
> 위에 있는 줄 때문에 적용 안됨


이렇게 써야 인용문 항상 제대로 들어간다고 함

> 이렇게 한 줄 이상
```
<br>

- 특이사항
티스토리에서는 다 깨진다.. 일괄 따옴표 표시 ㅜㅜ.. 스킨 변경이 필요하다
<br>


### 참조 문헌
1. [Wiki - Markdown](https://en.wikipedia.org/wiki/Markdown "Introduction of Markdown")
2. [markdownguide.org - Basic syntax](https://www.markdownguide.org/basic-syntax/#overview "Basic syntax overview")
3. [stackoverflow - Make underline](https://stackoverflow.com/questions/44840416/how-to-make-a-word-underline-in-markdown "stackoverflow - Make underline")