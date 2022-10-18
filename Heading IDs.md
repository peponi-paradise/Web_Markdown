<h3 id="title">Heading IDs</h3>

1. 글에 헤더를 사용하는 경우, 헤더에 원하는 ID를 부여하는 기능.
2. `### 헤더이름 {#원하는ID}` 로 사용한다.
3. 대체로 마크다운에서는 커스텀 ID 부여 기능을 지원한다.
4. GFM을 비롯한 몇몇 마크다운에서는 ID 자동 생성을 지원한다.
    ex) `### 헤더 1` 로 헤더를 만든 경우, 대체로 ID를 헤더-1로 자동 부여.
5. 해당 ID를 통해 [`내부링크`](#참조-문헌)를 걸 수 있다[footnote][Markdown 기초 연습 - Links](https://peponi-paradise.tistory.com/entry/Markdown-Practice-Links)[/footnote].

<br>

```md
- 사용법 (Markdown 방식)

    ### 헤더 이름 {#ID-1}

- HTML 방법 - Markdown 방식으로 ID 지정이 불가할 때

    - Format : <HeadingLevel id="헤더 ID 지정">헤더 이름</HeadingLevel>
```
<br>

- 사용법 (Markdown 방식)
    ### 헤더 이름 {#ID-1}

- HTML 방법 - Markdown 방식으로 ID 지정이 불가할 때
    <h3 id="ID-1">헤더 이름</h3>
<br>

```md
1. 내부 링크 걸기

    - Markdown 방법

        [`이름`](#ID)

    - HTML 방법

        Format : <a href="#ID">이름</a>

```
<br>

- Markdown 방법
    [`Heading IDs(타이틀)`](#title)

- HTML 방법
    <a href="#ID-1">'헤더 이름'으로 이동</a>
<br><br>

<h3 id="참조-문헌">참조 문헌</h3>

1. [markdownguide.org - Extended syntax](https://www.markdownguide.org/extended-syntax/#tables "Extended syntax overview")
2. [Markdown 기초 연습 - Links](https://peponi-paradise.tistory.com/entry/Markdown-Practice-Links)
3. [Markdown 기초 연습 - Footnotes (각주)](https://peponi-paradise.tistory.com/entry/Markdown-Pracitce-Footnotes)

<br>