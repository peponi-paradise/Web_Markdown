## 1. Introduction

<br>

- 표를 넣는 기능
- `|` (파이프) 와 `-` (하이픈) 기호를 이용해 작성

<br>

## 2. 사용법

<br>

### 2.1. 기본 사용법

<br>

```md
|항목 1|항목 2|항목 3|항목 4|
|---|---|---|---|
|내용 1|내용 2|내용 3|내용 4|
|내용 5|내용 6|내용 7|내용 8|
|내용 9|내용 10|내용 11|내용 12|
```

|항목 1|항목 2|항목 3|항목 4|
|---|---|---|---|
|내용 1|내용 2|내용 3|내용 4|
|내용 5|내용 6|내용 7|내용 8|
|내용 9|내용 10|내용 11|내용 12|

<br>

### 2.2. 셀 정렬

<br>

- 표의 각 셀에 있는 내용 정렬. 두번째 줄을 이용하여 정의하며 콜론 `:` 기호를 사용해 작성
    ```md
    |항목 1|항목 2|항목 3|항목 4|
    |:---:|:---|---:|---|
    |가운데 정렬|왼쪽 정렬|오른쪽 정렬|내용 4|
    |가운데 정렬|왼쪽 정렬|오른쪽 정렬|내용 8|
    |가운데 정렬|왼쪽 정렬|오른쪽 정렬|내용 12|
    ```

    |항목 1|항목 2|항목 3|항목 4|
    |:---:|:---|---:|---|
    |가운데 정렬|왼쪽 정렬|오른쪽 정렬|내용 4|
    |가운데 정렬|왼쪽 정렬|오른쪽 정렬|내용 8|
    |가운데 정렬|왼쪽 정렬|오른쪽 정렬|내용 12|

- 만약 가운데 정렬이 되지 않는 경우, `<center>` 태그로 셀 단위 지정하여 사용
    ```md
    |항목 1|항목 2|항목 3|<center>항목 4</center>|
    |:---:|:---|---:|---|
    |가운데 정렬|왼쪽 정렬|오른쪽 정렬|내용 4|
    |가운데 정렬|왼쪽 정렬|오른쪽 정렬|<center>내용 8</center>|
    |가운데 정렬|왼쪽 정렬|오른쪽 정렬|내용 12|
    ```

    |항목 1|항목 2|항목 3|<center>항목 4</center>|
    |:---:|:---|---:|---|
    |가운데 정렬|왼쪽 정렬|오른쪽 정렬|내용 4|
    |가운데 정렬|왼쪽 정렬|오른쪽 정렬|<center>내용 8</center>|
    |가운데 정렬|왼쪽 정렬|오른쪽 정렬|내용 12|

<br>

### 2.3. 셀 크기 변경

<br>

- 셀의 글자 공간이 부족해 보기 좋지 않은 경우, 띄어쓰기를 삽입해 강제로 크기 조절이 가능
- `&nbsp;`를 이용해 열 길이를 늘림
    ```md
    - Before
        |항목 1|항목 2|항목 3|
        |---|---|---|
        |내용 1|내용 2|내용 3|
    
    - After     
        |항목 1|항목 2|항목 3|
        |---|---|---|
        |&nbsp;&nbsp;내용 1&nbsp;&nbsp;&nbsp;|내용 2|내용 3|
    ```

    - Before
        |항목 1|항목 2|항목 3|
        |---|---|---|
        |내용 1|내용 2|내용 3|
    
    - After     
        |항목 1|항목 2|항목 3|
        |---|---|---|
        |&nbsp;&nbsp;내용 1&nbsp;&nbsp;&nbsp;|내용 2|내용 3|

<br>

### 2.4. 셀 병합 (확장)

<br>

- 나머지 셀을 공란으로 비우는 경우, 여러 열에 걸쳐있는 셀이 자동으로 병합 (확장)됨

```md
|항목 1|항목 2|항목 3|항목 4|
|---|---|---|---|
|병합 기준점||||
||병합 기준점|||
||||병합 기준점|
```

|항목 1|항목 2|항목 3|항목 4|
|---|---|---|---|
|병합 기준점||||
||병합 기준점|||
||||병합 기준점|

<br>

### 2.5. 글자 Formatting

<br>

- 기울임 (Italic), 굵게 (Bold) 등 표 내용에도 글자 formatting 가능

```md
|항목 1|항목 2|항목 3|항목 4|
|---|---|---|---|
|*기울임*|**굵게**|~~취소선~~|<u>밑줄</u>|
|<span style="text-decoration: underline">밑줄 2</span>|<span style="color:blue">색상 추가</span>|<span style="color:blue">*색상 추가, 기울임*</span>|<span style="text-decoration:underline;color:red">밑줄, 색상 추가</span>|
|[`내부 링크`](#introduction)|[일반 링크](http://tistory.com)|[참조링크][1]|**[링크 강조](http://tistory.com)**|

[1]: http://tistory.com "Tistory"
```

|항목 1|항목 2|항목 3|항목 4|
|---|---|---|---|
|*기울임*|**굵게**|~~취소선~~|<u>밑줄</u>|
|<span style="text-decoration: underline">밑줄 2</span>|<span style="color:blue">색상 추가</span>|<span style="color:blue">*색상 추가, 기울임*</span>|<span style="text-decoration:underline;color:red">밑줄, 색상 추가</span>|
|[`내부 링크`](#introduction)|[일반 링크](http://tistory.com)|[참조링크][1]|**[링크 강조](http://tistory.com)**|

[1]: http://tistory.com "Tistory"

<br>

## 3. 기타 - 테이블 제너레이터 이용

<br>

- 아래는 마크다운 테이블 생성 사이트이다.
    1. <https://www.tablesgenerator.com/markdown_tables>
    2. <https://tableconvert.com/markdown-generator>

<br>

## 4. 참조 자료

<br>

- [markdownguide.org - Extended syntax](https://www.markdownguide.org/extended-syntax/#tables "Extended syntax overview")
- [마크다운 - 표(테이블)만들기](https://inasie.github.io/it%EC%9D%BC%EB%B0%98/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4-%ED%91%9C-%EB%A7%8C%EB%93%A4%EA%B8%B0/)
- [[마크다운] 표만들기 - 셀정렬 방법](https://steemit.com/kr/@antares007/-201787t14245290z)
- [마크다운 테이블 열 크기 늘리기](https://www.memoengine.com/blog/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4%20%ED%85%8C%EC%9D%B4%EB%B8%94%20%EC%97%B4%20%ED%81%AC%EA%B8%B0%20%EB%8A%98%EB%A6%AC%EA%B8%B0/)
- [마크다운 언어를 이용해서 표 만들기(영문)](https://productivityarchive.wordpress.com/2013/08/10/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4-%EC%96%B8%EC%96%B4%EB%A5%BC-%EC%9D%B4%EC%9A%A9%ED%95%B4%EC%84%9C-%ED%91%9C-%EB%A7%8C%EB%93%A4%EA%B8%B0%EC%98%81%EB%AC%B8-2/)
- [Markdown 기초 연습 - Emphasis](https://peponi-paradise.tistory.com/entry/Markdown-Practice-Emphasis)