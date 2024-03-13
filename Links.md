## Introduction

<br>

- 글에 링크를 다는 기능
- `[링크 이름](링크 주소)` 형식으로 작성

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
[티스토리](http://tistory.com)
```

</td>
<td>

[티스토리](http://tistory.com)

</td>
</tr>
<tr>
<td>

```md
[네이버](http://naver.com "툴팁")
```

</td>
<td>

[네이버](http://naver.com "툴팁")

</td>
</tr>
<tr>
<td>

```md
<!-- 링크 강조 -->

*[Italic link](https://markdownguide.org)*
```

</td>
<td>

*[Italic link](https://markdownguide.org)*

</td>
</tr>
<tr>
<td>

```md
<!-- 다이렉트 링크 (이메일 또는 URL) -->

<https://microsoft.com>
```

</td>
<td>

<https://microsoft.com>

</td>
</tr>
<tr>
<td>

```md
<!-- 내부 링크 -->

[Introduction](#introduction)
```

</td>
<td>

[Introduction](#introduction)

</td>
</tr>
<tr>
<td>

```md
<!-- 참조 링크 -->

[참조링크][1]

<!-- 주소 삽입. 페이지에서는 안보임 -->
[1]: http://tistory.com "Tistory"
```

</td>
<td>

[참조링크][1]

[1]: http://tistory.com "Tistory"

</td>
</tr>
</tbody>
</table>

<br>

## 참조 자료

<br>

- [Links](https://www.markdownguide.org/basic-syntax/#links)