## Introduction

<br>

- 번호 또는 기호를 사용하여 리스트 만듦. 글 조직화에 이용
- 두 가지 리스트 타입을 혼합해서 사용할 수 있다.

<br>

## 기본 사용법

<br>

```md
<!-- 번호를 사용하는 리스트 -->

1. 1
2. 2
3. 3

<!-- 번호를 막 써도 자동 정렬 -->

1. 1
1. 2
1. 3

<!-- 리스트 중첩 (탭으로 들여쓰기) -->

1. 1
2. 2
    1. 2 - 1
    2. 2 - 2
3. 3
```
```md
<!-- 기호를 사용하는 리스트 -->
<!-- -, *, + 기호 사용 가능 -->

- 1
- 2
- 3

* 1
* 2
* 3

+ 1
+ 2
+ 3

<!-- 리스트 중첩 -->

- 1
- 2
    1. 2 - 1
    2. 2 - 2
- 3
```

<br>

## 기본 사용법 - Rendering

<br>

- 번호를 사용하는 리스트

1. 1
2. 2
3. 3

<br>

1. 1
1. 2
1. 3

<br>

1. 1
2. 2
    1. 2 - 1
    2. 2 - 2
3. 3

<br>

- 기호를 사용하는 리스트
<br>

- 1
- 2
- 3

<br>

* 1
* 2
* 3

<br>

+ 1
+ 2
+ 3

<br>

- 1
- 2
    1. 2 - 1
    2. 2 - 2
- 3

<br>

## 리스트 안에 다른 마크다운 요소 넣기

<br>

```md
- code
    ```python
    def TestFunction(PrintString:str):
        print(PrintString)
    ```
- 인용문
    > 인용문
- 단락
    1번 단락

    2번 단락
- 이미지
    ![이미지](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)
```

<br>

## 리스트 안에 다른 마크다운 요소 넣기 - Rendering

<br>

- code
    ```python
    def TestFunction(PrintString:str):
        print(PrintString)
    ```
- 인용문
    > 인용문
- 단락
    1번 단락

    2번 단락
- 이미지
    ![이미지](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

<br>

## 주의사항

<br>

- CommonMark를 포함한 다른 Markup의 경우 순서가 있는 리스트 구성 시 ")" 기호를 delimiter로 사용할 수 있으나 일부이기 때문에 "." 사용을 권장한다고 한다.
- 순서를 지정하지 않는 리스트의 경우 기호를 섞어쓰지 않도록 주의한다.

<br>

## 참조 자료

- [Lists](https://www.markdownguide.org/basic-syntax/#lists-1)