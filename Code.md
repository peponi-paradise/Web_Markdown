## Introduction

<br>

- 단어 또는 구를 `` ` (Backtick) `` 기호를 이용하여 code로 지정

<br>

## Example

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
간단한 `코드` 표시
```

</td>
<td>

간단한 `코드` 표시

</td>
</tr>
<tr>
<td>

```md
<!-- 코드 내에 ` 기호가 있는 경우 -->

`` 코드 중간에 ` 기호 ``
```

</td>
<td>

`` 코드 중간에 ` 기호 ``

</td>
</tr>
<tr>
<td>

```md
<!-- 코드 블록 표현은 backtick 3개 (```) -->
<!-- 언어 지정 가능 -->

    ```python
    def TestFunction(PrintString:str):
        print(PrintString)
    ```
```

</td>
<td>

```python
def TestFunction(PrintString:str):
    print(PrintString)
```

</td>
</tr>
</tbody>
</table>

<br>

## 참조 자료

<br>

- [Code](https://www.markdownguide.org/basic-syntax/#code)