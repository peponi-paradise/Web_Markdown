## Introduction

<br>

1. 글에 이미지를 추가하는 기능
2. `![대체 텍스트](이미지 주소 "툴팁")` 형식으로 사용

<br>

## 기본 사용법

<br>

- Markdown
    ```md
    ![alt](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg "tooltip")
    ```
- Render
    ![alt](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg "tooltip")

<br>

## 이미지와 함께 링크 걸기

<br>

1. 이미지 자체로 연결 링크가 된다. 이미지 클릭 시 설정된 URL로 이동
2. 사용법 : `[![대체 텍스트](이미지 주소 "툴팁")](이동 URL)`

<br>

- Markdown
    ```md
    [![alt](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg "tooltip")](https://ko.wikipedia.org/wiki/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4)
    ```
- Render
    [![alt](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg "tooltip")](https://ko.wikipedia.org/wiki/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4)

<br>

## 주의사항

<br>

- 이미지 로드에 실패한 경우 아래와 같이 나타난다.
    ![대체 텍스트](주소)

<br>

## 참조 자료

<br>

- [Images](https://www.markdownguide.org/basic-syntax/#images-1)