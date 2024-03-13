## Introduction

<br>

- 글자에 주는 강조 효과 (Bold, Italic 등)

<br>

## Bold

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
**Bold**
```

</td>
<td>

**Bold**

</td>
</tr>
<tr>
<td>

```md
__Bold__
```

</td>
<td>

__Bold__

</td>
</tr>
</tbody>
</table>

<br>

## Italic

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
*Italic*
```

</td>
<td>

*Italic*

</td>
</tr>
<tr>
<td>

```md
_Italic_
```

</td>
<td>

_Italic_

</td>
</tr>
</tbody>
</table>

<br>

## Bold, Italic

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
***Bold, Italic***
```

</td>
<td>

***Bold, Italic***

</td>
</tr>
<tr>
<td>

```md
___Bold, Italic___
```

</td>
<td>

___Bold, Italic___

</td>
</tr>
<tr>
<td>

```md
__*Bold, Italic*__
```

</td>
<td>

__*Bold, Italic*__

</td>
</tr>
<tr>
<td>

```md
**_Bold, Italic_**
```

</td>
<td>

**_Bold, Italic_**

</td>
</tr>
</tbody>
</table>

<br>

## Strikethrough (Cancel line)

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
~~Cancel line~~
```

</td>
<td>

~~Cancel line~~

</td>
</tr>
</tbody>
</table>

<br>

## Underline

<br>

<table>
<thead>
<tr>
<th>Markdown</th>
<th>HTML</th>
<th>Render</th>
</tr>
</thead>
<tbody>
<tr>
<td>

```md
<!-- 대체로 불가 -->
__Under line__
```

</td>
<td>

```html
<u>Underline</u>
<span style="text-decoration: underline">
Underline
</span>
```

</td>
<td>

<span style="text-decoration: underline">
Underline
</span>

</td>
</tr>
</tbody>
</table>

<br>

## 주의사항

<br>

- `밑줄`의 경우 마크다운에서 지원하지 않는 경우가 많다. HTML 스타일로 사용하는 것이 좋다.
    - `<u>` 태그의 경우 HTML5에서 철자 오류 또는 주석으로 사용된다.

<br>

## 참조 자료

<br>

- [How to make a word underline in Markdown](https://stackoverflow.com/questions/44840416/how-to-make-a-word-underline-in-markdown)
- [Emphasis](https://www.markdownguide.org/basic-syntax/#emphasis)