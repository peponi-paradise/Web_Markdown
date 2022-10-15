### Images
- 글에 이미지를 추가하는 기능. 느낌표 ! 와 대괄호 [] 를 이용하여 대체 텍스트 지정. 마우스 툴팁은 URL 뒤에 큰따옴표 "" 를 삽입하여 지정 (툴팁은 옵션)

```md
1. 기본 사용법

    * 사용법 1 : ![대체 텍스트](URL)

    * 사용법 2 : ![대체 텍스트](URL "마우스 툴팁")

    * 예시 : ![마크다운 이미지](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg "마크다운 이미지")

2. 이미지와 함께 링크 걸기

    * 이미지 자체로 연결 링크가 된다. 이미지 클릭 시 설정된 URL로 이동

    * 사용법 : 1. 기본 사용법을 대괄호 [] 로 감싼 후, 괄호 () 안에 URL 지정
    [![대체 텍스트](URL)](이동 URL)

    * 예시 : [![마크다운 이미지](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg "마크다운 이미지")](https://ko.wikipedia.org/wiki/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4)
```
<br>

- 테스트

1. 기본 사용법<br><br>
    * 사용법 1 : ![대체 텍스트](URL)<br><br>
    * 사용법 2 : ![대체 텍스트](URL "마우스 툴팁")<br><br>
    * ![마크다운 이미지](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg "마크다운 이미지")<br><br>
2. 이미지와 함께 링크 걸기<br><br>
    * 이미지 자체로 연결 링크가 된다. 이미지 클릭 시 설정된 URL로 이동<br><br>
    * 사용법 : 1. 기본 사용법을 대괄호 [] 로 감싼 후, 괄호 () 안에 URL 지정<br>[![대체 텍스트](URL)](이동 URL)<br><br>
    * [![마크다운 이미지](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg "마크다운 이미지")](https://ko.wikipedia.org/wiki/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4)

<br><br>

- 주의사항
    1. 이미지 로드를 위한 URL이 잘못 지정되었거나 삭제되는 등 이미지를 불러오지 못하는 경우, 깨진 이미지 아이콘 !["](URL) 이 발생하며 대체 텍스트만 표시된다.

<br><br>

### 참조 문헌
1. [markdownguide.org - Basic syntax](https://www.markdownguide.org/basic-syntax/#overview "Basic syntax overview")