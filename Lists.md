## Introduction

<br>

- 번호 또는 기호를 사용하여 리스트 만듦. 글 조직화에 이용
- 두 가지 리스트 타입을 혼합해서 사용할 수 있다.

<br>

## 기본 사용법

<br>

<table>
<thead>
<tr>
<th>Markdown</th>
<th>Render</th>
</tr>
</thead>
<tbody>
<tr>
<td>

```md
1. 번호를
2. 사용하는
3. 리스트
```

</td>
<td>

1. 번호를
2. 사용하는
3. 리스트

</td>
</tr>
<tr>
<td>

```md
<!-- -, *, + 사용 가능 -->

- 기호를
- 사용하는
- 리스트
```

</td>
<td>

- 기호를
- 사용하는
- 리스트

</td>
</tr>
<tr>
<td>

```md
1. 중첩된
    - 리스트
        - 구성
            1. 가능
```

</td>
<td>

1. 중첩된
    - 리스트
        - 구성
            1. 가능

</td>
</tr>
</tbody>
</table>

<br>

## 리스트 안에 다른 마크다운 요소 넣기

<br>

- 여기서는 간단히 다른 마크다운 요소가 삽입될 수 있다는 정도만 보여준다.

<table>
<thead>
<tr>
<th>Markdown</th>
<th>Render</th>
</tr>
</thead>
<tbody>
<tr>
<td>

```md
- code
    ```python
    def TestFunction(PrintString:str):
        print(PrintString)
    ```
```

</td>
<td>

- code
    ```python
    def TestFunction(PrintString:str):
        print(PrintString)
    ```

</td>
</tr>
<tr>
<td>

```md
- 인용문
    > 인용문
```

</td>
<td>

- 인용문
    > 인용문

</td>
</tr>
<tr>
<td>

```md
- 단락
    1번 단락

    2번 단락
```

</td>
<td>

- 단락
    1번 단락

    2번 단락

</td>
</tr>
<tr>
<td>

```md
- 이미지
    ![이미지](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)
```

</td>
<td>

- 이미지
    ![이미지](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

</td>
</tr>
</tbody>
</table>

<br>

## 주의사항

<br>

- CommonMark를 포함한 다른 Markup의 경우 순서가 있는 리스트 구성 시 `)` 기호를 delimiter로 사용할 수 있으나 일부이기 때문에 `.` 사용을 권장한다고 한다.

<br>

## 참조 자료

- [Lists](https://www.markdownguide.org/basic-syntax/#lists-1)