## Introduction

<br>

- 몇몇 마크다운은 리스트식 정의를 지원한다. 버전 이력 관리, 용어 정의 등에 좋아보인다.
- 정의할 용어 다음 줄에 `: ` 기입 후 글을 적어준다.

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
의자
: 내가 앉아있는 것
: 옷을 걸어두는 용도
```

</td>
<td>

의자
: 내가 앉아있는 것
: 옷을 걸어두는 용도

</td>
</tr>
</tbody>
</table>

<br>

## 특이사항

<br>

- 대체로 지원하지 않는 것 같다 (깃허브 등).
- VS code의 기본 프리뷰도 지원이 되지 않고, [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)는 동작한다.
- 지원이 되지 않지만 정 필요한 경우, HTML로 작성해야 한다.

<br>

## HTML 작성

<br>

- `<dl>`, `<dt>`, `<dd>` 태그를 이용하여 작성한다.
    - `<dl>` : Definition list
    - `<dt>` : Definition title
    - `<dd>` : Definition detail

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

```html
<dl>
    <dt>의자</dt>
    <dd>내가 앉아있는 것</dd>
    <dd>옷을 걸어두는 용도</dd>
</dl>
```

</td>
<td>

<dl>
    <dt>의자</dt>
    <dd>내가 앉아있는 것</dd>
    <dd>옷을 걸어두는 용도</dd>
</dl>

</td>
</tr>
</tbody>
</table>

<br>

## 참조 자료

<br>

- [Definition Lists](https://www.markdownguide.org/extended-syntax/#definition-lists)