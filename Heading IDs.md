## Introduction

<br>

- 글에 헤더를 사용하는 경우, 헤더에 원하는 ID를 부여하는 기능
- `## 헤더 이름 {#ID}`로 부여한다.
- 마크다운에서는 대체로 ID 자동 생성을 지원한다.
    - `## 헤더 1`로 만든 경우, ID는 대체로 `헤더-1`이다.
- 해당 ID를 통해 [내부링크](https://peponi-paradise.tistory.com/entry/Markdown-Practice-Links)를 걸 수 있다.

<br>

## Example {#Example}

<br>

- ID 부여 방법
    ```md
    ## Header {#ID}
    ```
    ```html
    <!-- 마크다운 방법으로 ID 지정이 불가할 때 -->

    <h2 id="ID">Header</h2>
    ```

- 내부 링크 걸기
    ```md
    [Example](#Example)
    ```
    ```html
    <a href="#Example">Example</a>
    ```

<br>

## Rendering (내부 링크)

<br>

- 마크다운
    [Example](#Example)
- HTML
    <a href="#Example">Example</a>

<br>

## 참조 자료

<br>

- [markdownguide.org - Extended syntax](https://www.markdownguide.org/extended-syntax/#tables "Extended syntax overview")
- [Markdown 기초 연습 - Links](https://peponi-paradise.tistory.com/entry/Markdown-Practice-Links)
- [Markdown 기초 연습 - Footnotes (각주)](https://peponi-paradise.tistory.com/entry/Markdown-Pracitce-Footnotes)