<h3 id="title">Definition Lists</h3>

1. 몇몇 마크다운은 리스트식 정의를 지원한다. 버전 이력 관리, 용어 정의 등에 좋아보인다.
2. 한 줄에 원하는 글을 적고,
3. 다음 줄에 콜론+스페이스 `: ` 기호에 이어 글을 적어준다.
<br>

```md
의자
: 내가 앉아있는 것
: 옷을 걸어두는 용도

키보드
: 매일매일 붙잡고 있는 것
: 20년도 더 쓴 것 같은데 아직도 오른손은 독수리 타자..
: 원한다면 **글자** *Formatting*도 [`가능`](#title)
```
<br>

의자
: 내가 앉아있는 것
: 옷을 걸어두는 용도

키보드
: 매일매일 붙잡고 있는 것
: 20년도 더 쓴 것 같은데 아직도 오른손은 독수리 타자..
: 원한다면 **글자** *Formatting*도 [`가능`](#title)

<br>

- 특이사항
    1. 깃허브에서는 지원하지 않는 것 같다. 출력된 것 확인해보니 그냥 글자로만 나온다..
    2. 티스토리도 마찬가지이다. 일부 마크다운만 지원하나보다.
    3. 따라서 지원이 안되는데 정 필요한 경우, HTML로 작성해야한다.

<br>

```html
- Format

<dl> : Definition list
    <dt> : Definition title
    <dd> : Definition detail


- Example

<dl>
    <dt>의자</dt>
    <dd>내가 앉아있는 것</dd>
    <dd>옷을 걸어두는 용도</dd>
    <dt>키보드</dt>
    <dd>매일매일 붙잡고 있는 것</dd>
    <dd>20년도 더 쓴 것 같은데 아직도 오른손은 독수리 타자..</dd>
    <dd>원한다면 <strong>글자</strong> <i>Formatting</i>도 <a href="#title">가능</a></dd>
</dl>
```
<br>

<dl>
    <dt>의자</dt>
    <dd>내가 앉아있는 것</dd>
    <dd>옷을 걸어두는 용도</dd>
    <dt>키보드</dt>
    <dd>매일매일 붙잡고 있는 것</dd>
    <dd>20년도 더 쓴 것 같은데 아직도 오른손은 독수리 타자..</dd>
    <dd>원한다면 <strong>글자</strong> <i>Formatting</i>도 <a href="#title">가능</a></dd>
</dl>

<br><br>


### 참조 문헌
1. [markdownguide.org - Extended syntax](https://www.markdownguide.org/extended-syntax/#tables "Extended syntax overview")