<h2 id="title">Text decoration and formatting</h2>

<h3 id="Emoji">Emoji</h3>

1. 텍스트 작성 중 사용하는 emoji를 markdown으로 표현할 수 있다.
2. 많은 markdown은 간단한 텍스트 입력만으로 자동 emoji 변환을 지원하고 있다.
3. GitHub에서 지원하는 emoji의 경우, 아래 페이지를 참조하면 된다.
    https://gist.github.com/rxaviers/7360908
    사용 방법은 아래와 같다.
<br>

```md
글 작성 도중 emoji를 넣고 싶은 자리에 `:emoji name:`을 입력한다.

- Example

    - Smile : :smile:
    - Laughing : :laughing:
    - Cry : :cry:
```
<br>

- Smile : :smile:
- Laughing : :laughing:
- Cry : :cry:

<br>

4. 위에서 보여지는 바와 같이, 티스토리는 지원을 하지 않는다.
5. 그럼에도 emoji를 사용하고 싶은 경우, 아래 사이트들에서 복사/붙여넣기 하는 방법을 추천한다.
    1. https://emojipedia.org/
    2. https://getemoji.com/

<br>

6. Emoji는 unicode이기 때문에, unicode를 찾아서 넣어주는 방법도 있다. Unicode 정보 및 사용법은 아래 내용을 참조하면 된다.
    - Unicode 확인 가능한 사이트
        1. https://www.w3schools.com/charsets/ref_emoji_smileys.asp
        2. https://unicode.org/emoji/charts/full-emoji-list.html
        3. https://html-css-js.com/html/character-codes/icons/
<br>

```md
- 사용법
    1. `&#`+`Decimal 값`+`;`
    2. `&#`+`Hex 값`+`;`

- Example (Name : GRINNING FACE, Emoji : 😀)
    1. &#128512;
    2. &#x1F600;
```
<br>

- Example (Name : GRINNING FACE, Emoji : 😀)
    1. &#128512;
    2. &#x1F600;
<br>
--------------------------

<h3 id="Highlight">Highlight</h3>

1. 일반적으로 사용되지는 않지만, 몇몇 Markdown은 text highlighting을 지원한다.
2. Highlight 적용할 글자 전후로 등호 기호 `==`를 2개씩 붙여주면 된다.
<br>

```md
나는 ==이 글자==를 highlight 처리하고 싶다.
```
<br>

나는 ==이 글자==를 highlight 처리하고 싶다.
<br>

3. 위에서 보여지는 바와 같이, 적용되지 않는 경우가 있다. (티스토리 확인 필요)
4. 이럴 경우 필요하다면 HTML로 적용시킬 수 있다.
<br>

```html
나는 <mark>이 글자</mark>를 highlight 처리하고 싶다.
```
<br>

나는 <mark>이 글자</mark>를 highlight 처리하고 싶다.
<br>

5. 대체로 에디터들이 HTML을 지원하기 때문에, 이 방법은 잘 적용될 것으로 기대된다.
<br>
--------------------------

<h3 id="Sub-SuperScript">Sub and Super script</h3>

1. 일반적으로 사용되지는 않지만, 몇몇 Markdown은 아래 & 위 첨자를 지원한다.
2. 아래 첨자의 경우 물결 `~` 기호를 적용할 글자 전후에 사용한다.
3. 위 첨자의 경우 제곱 `^` 기호를 적용할 글자 전후에 사용한다.
<br>

```md
- Subscript (아래 첨자)
    - 아래 첨자를 표시하는 경우 ~이렇게~ 하면 적용
    - 화학식 기호 표현에도 용이함 : NH~3~

- Superscript (위 첨자)
    - 위 첨자를 표시하는 경우 ^이렇게^ 하면 적용
    - 수식 표현에 용이함 : aX^2^ + bX + C
```
<br>

- Subscript (아래 첨자)
    - 아래 첨자를 표시하는 경우 ~이렇게~ 하면 적용
    - 화학식 기호 표현에도 용이함 : NH~3~

- Superscript (위 첨자)
    - 위 첨자를 표시하는 경우 ^이렇게^ 하면 적용
    - 수식 표현에 용이함 : aX^2^ + bX + C
<br>

4. 위에서 보여지는 바와 같이, 의도와 다르게 나오거나 적용되지 않는 경우가 있다.
5. 이럴 경우 필요하다면 HTML로 적용시킬 수 있다.
<br>

```html
- Subscript (아래 첨자)
    - 아래 첨자를 표시하는 경우 <sub>이렇게</sub> 하면 적용
    - 화학식 기호 표현에도 용이함 : NH<sub>3</sub>

- Superscript (위 첨자)
    - 위 첨자를 표시하는 경우 <sup>이렇게</sup> 하면 적용
    - 수식 표현에 용이함 : aX<sup>2</sup> + bX + C
```
<br>

- Subscript (아래 첨자)
    - 아래 첨자를 표시하는 경우 <sub>이렇게</sub> 하면 적용
    - 화학식 기호 표현에도 용이함 : NH<sub>3</sub>

- Superscript (위 첨자)
    - 위 첨자를 표시하는 경우 <sup>이렇게</sup> 하면 적용
    - 수식 표현에 용이함 : aX<sup>2</sup> + bX + C
<br><br>

<h3 id="참조-문헌">참조 문헌</h3>

1. [markdownguide.org - Extended syntax](https://www.markdownguide.org/extended-syntax/#emoji "Extended syntax overview")
2. [[HTML] 이모지(emoji) 삽입하는 방법!](https://23log.tistory.com/81)