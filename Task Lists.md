<h3 id="title">Task Lists</h3>

1. Task list를 지원하는 markdown 사용 시, To-do list 관리가 편하다.
2. 하이픈 기호 `-`와 스페이스를 포함한 브라켓 `[ ]`을 사용한다.
3. 체크를 하는 경우 브라켓의 빈 공간에 x를 입력한다 `[x]`
4. 마크다운으로 지원 안하는 경우, 필요하다면 HTML로 만들어야한다.

```md
- 마크다운 방법
    - [ ] 첫번째
    - [x] 두번째
    - [x] 세번째
    - [ ] 네번째
    - [ ] HTML로 Task list 만들어보기

- HTML 방법
    - Format (체크 X) : <input type="checkbox" id="ID 지정" name="이름 지정"><label for="id">체크박스 옆 내용</label>
    - Format (체크 O) : <input type="checkbox" id="ID 지정" name="이름 지정"checked><label for="id">체크박스 옆 내용</label>

    - Example
    <input type="checkbox" id="첫번째" name="첫번째"><label for="첫번째">첫번째</label><br>
    <input type="checkbox" id="두번째" name="두번째"checked><label for="두번째">두번째</label><br>
    <input type="checkbox" id="세번째" name="세번째"checked><label for="세번째">세번째</label><br>
    <input type="checkbox" id="네번째" name="네번째"><label for="네번째">네번째</label><br>
    <input type="checkbox" id="HTMLlist" name="HTMLlist"checked><label for="HTMLlist">HTML로 Task list 만들어보기</label>
```
<br>

- 마크다운 방법
    - [ ] 첫번째
    - [x] 두번째
    - [x] 세번째
    - [ ] 네번째
    - [ ] HTML로 Task list 만들어보기

- HTML 방법
    - Format (체크 X) : <input type="checkbox" id="ID 지정" name="이름 지정"><label for="id">체크박스 옆 내용</label>
    - Format (체크 O) : <input type="checkbox" id="ID 지정" name="이름 지정" checked><label for="id">체크박스 옆 내용</label>

    - Example
    <input type="checkbox" id="첫번째" name="첫번째"><label for="첫번째">첫번째</label><br>
    <input type="checkbox" id="두번째" name="두번째" checked><label for="두번째">두번째</label><br>
    <input type="checkbox" id="세번째" name="세번째" checked><label for="세번째">세번째</label><br>
    <input type="checkbox" id="네번째" name="네번째"><label for="네번째">네번째</label><br>
    <input type="checkbox" id="HTMLlist" name="HTMLlist" checked><label for="HTMLlist">HTML로 Task list 만들어보기</label>

<br><br>

<h3 id="참조-문헌">참조 문헌</h3>

1. [markdownguide.org - Extended syntax](https://www.markdownguide.org/extended-syntax/#tables "Extended syntax overview")
2. [developer.mozilla.org](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/checkbox)
3. [w3schools.com](https://www.w3schools.com/tags/att_input_type_checkbox.asp)
4. [tcpschool.com](http://www.tcpschool.com/html-tags/label)