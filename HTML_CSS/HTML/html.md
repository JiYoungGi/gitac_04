## HTML Basic

```
<!DOCTYPE html> : 문서(웹페이지) 타입(종류) - 버전(html5)
<html> : 웹 페이지 전체 영역

  <head> : 웹 페이지의 추가정보, 타이틀, 파일 임포트
    <title></title>
  </head>

  <body> : 웹 페이지의 본문영역 - 웹 페이지의 모든 콘텐츠 표시
  </body>

</html>
```

##HTML Syntax

- Tag를 사용해서 Element를 표시/표현

```
<tag>contents</tag> : 시작태그, 종료태그로 구성

```

## Text Contents Markup

내용 : 시작태그, 종료태그로 구성

: 시작하기만 하는 존재 - 요소(빈 요소)

- 포함관계 (Nested Element)
  -Tag 영역안에 다른 Tag가 포함되는 것 -포함하는 요소 : 조상요소(ancestor), 부모요소(parent) -포함되는 요소 : 자손요소(descendant), 자식요소(child)
  큰제목
  단락

html 기준

부분: 본체
예전에는 h1, p body 기준
요구사항 : X
인덕션 : html
부분: h1, p
득템 : X

-Attribute(속성)
-tag에 추가 정보
-attr이름="값"

## Text Contents Markup

### Heading(제목)

- h(heading) 태그
- h1 ~ h6

### Paragraph(단락)

- p(paragraph) 태그

WYSIWYG(What you see Is What you Get : html은 WYSIWYG 지원이 가능합니다)

- 강제 줄바꿈 : br(break) 태그

  - 시작태그만 존재하는 빈요소(Empty Element)

- 강제 공백 : &nbsp;(Non-Break Space) (엔터티 코드)

& : 앰퍼샌드 '코어' : 코딩

계정을 사용하지 않고 있습니다.

- 수평선(Horizontal Rule) :hr
  - 단락을 구분하는 구분선
  - 빈 요소

### HTML Link

- a(anchor) : 하이퍼링크 연결 태그
- href(Hypertext Reference) : 목적지 정보 제공 속성(atrribute)
- bookmark -연결된 페이지로 이동하지 않고 같은 페이지 내에서 위아래 이동

  '''

  - page link
    <a href="url">텍스트</a>

  -bookmark

  - link
    <a href="#target">목적지</a>

  - target
  <h2 id="target">단락 제목</h2>

  '''

텍스트

- URL(Uniform Resource Locator) : 파일위치식별자 - 상세주소

- 인터넷 주소체계
  -IP(internet protocol) address : 인터넷에서 사용하는 주소
  -Domain name : IP 주소를 영어단어로 표현 -서버종류 : www -회사이름 : naver, daum -기관성격 : com, net (3자리) / co, go, ac (4자리) -국가(4자리): kr, uk, ca, fr ...

```
0~255까지 숫자 4개로 구성
Ex) 192.168.0.1

- 인터넷 접속 프로세스 : 주소표시줄에 Domain Name 입력 => IP주소로 변환 => 접속

- url 체계
IP/Domain 주소/상세경로/파일정보
Ex) https://www.w3schools.com/html/default.asp

```
