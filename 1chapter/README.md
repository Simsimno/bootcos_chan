# 1강

- 자주 사용되는 언어, c, java, python
- help

## HTTP

- 먼저 인터넷 부터 이해, 네트워크의 집합체임
- 서로 통신하기 위해 HTTP를 쓴다
- HTTP는 어떤 종류의 데이터도 전송 가능하다
- 유상태? 지속적 / 채팅, 온라인 겜
- 무상태 필요할 때만 씀 / 메일?
- HTTP == 무상태
- 정보 보존을 위해 쿠키를 씀
- URL 위치> 프로토콜의 종류, IP, 도메인 주소, 포트번호, 문서의 경로
- 웹 동작, 클라이언트 요청
- ? 뒷부부분 무엇

## 웹 Front-End 와 웹 Back-End

- 웹은 프론트엔드랑 백엔드로 나뉘어짐
- 브라우저 == 프론트엔드? 클라이언트? 암튼 보이는 거
- 웹백엔드 == 보이지 않아
- 웹프론트엔드의 역할 / 예뻐야 한다. 잘 보여주기.
- HTML, JAVASCRIPT, CSS
- 타 웹사이트를 보면서 참고하기
- 도구 더보기, 개발자 도구, 소스코드 확인 가능 그러나 봐도 모른다
- 아마존 탐구함 CSS확인. 역시 봐도 모르겠다
- 소스, 네트워크, 엘레멘트 확인

## 백 엔드 개발자가 알아야 할 것들
- 언어 하나쯤은 할 수 있어야 한다...
- 알고리즘, 자료구조, 네트워크, DBMS(데이터베이스)다루는 것

## browser의 동작
- 브라우저의 내부를 이해하면 좋다...
- html언어에 대해서
- 브라우저는 브라우저 컴포넌트로 구성, UI덩어리, 브라우저 엔진-화면 보여주는 것(픽셀단위)
- 데이터 관리하는 영역, 네트워킹 모듈, 자바스크립트 해석하는 것, 백엔드 영역.
- 렌더링 엔진?
- HTML은...트리 구조의 형태(데이터구조)

<tag class="title">안녕하세요</tag>

## 웹 서버 소프트웨어의 종류

- 가장 많이 사용함 : Apache, 마이크로소프트, 구글, Nginx
- 인터넷 웹 서비스 netcraft //통계를 보여주는 곳임

## WAS

- 서비스를 제공 : 서버 / 웹 서버
- 서버에게 서비스를 요청해서 보여줌 : 클라이언트 / 웹 브라우저
- 데이터베이스를 관리 : DBMS / MySQL, MariaDB, Oracle, PostgreSQL
- 클라이언트 DBMS 사이에 또다른 서버 : 미들웨어
- 미들웨어 == WAS
- WAS의 기능, 프로그램 실행 환경, 데이터 베이스 접속 기능, 여러개의 트랜잭션을 관리, 업무를 처리하는 비즈니스 로직을 실행한다.

## HTML 태그
- w3shchool.com 참고
- a 태그 배움, <a href="abcd"></a>
- ul, li 태그 배움.
- heading 태그 배움, <h1></h1>
- img 태그 배움, <img src="img name" width="넓이" height="높이"

## HTML Layer 태그
- header, section, nav, footer, aside.
- header : 소개나 탐색을 돕는 것의 그룹임. 제목이나 로고, 구획의 제목, 탐색 폼과 같은 것들
- section : 일반적인 구획, 컨텐츠의 주제그룹임. 한마디로 그룹의 경계선 같은ㄱㅓ
- nav : 네비게이션 역할, 일종의 메뉴.
- footer : 꼬릿말임
- aside : 주요한 주제가 아님, 어디까지나 사이드, 참고용

## HTML 구조설계
- img, button
- img : 그림 넣는 거
- button : 버튼.

## class 와 id 속성
- class 여러 것에 옷입히기 CSS
- 진심으로 고유한.

## CSS 선언
- span { color : red; }
- 선택자 + property + value
- 스타일 적용하는 방법 3가지, inline, internal, external
- inline : html 태그 안에 넣음
- internal : html에 css를 집어넣음.
- external : 별도의 css파일을 만듦

## 상속과 우선순위 결정
- 상속 : color, font-size 종류의 것들은 상속됨
<br> border, padding 종류는 상속이 안됨.
- cascading : 우선순위에 대해서, 중복이나 같은 노드일 때.
<br> 기본 우선순위 inline > internal > external 동일하면 나중의 것이 적용
body > span 같이 구체적으로 하면 우선순위 높음.
id > class > element

## CSS Selector

- 엘리먼트를 빠르게 찾을 수 있는...문법
- id, class, tag selector
- 부모에게 상속받아 영향을 받을 수도 있다
- px 단위, em 단위

## Layout
- display (block, inline, inline-block)
- position(static, absolute, relative, fixed)
- float(left, right) 
-

## float
- list-style:none;
- float, overfloaw-auto, wrap
- margin-bottom, top

## Servlet 작성방법
- Servlet : 웹프로그래밍에서 클라이언트의 요청을 처리하고 
그 결과를 다시 클라이언트에게 전송하는 Servlet 클래스의 구현 규칙을 지킨 자바 프로그래밍 기술
- setContenttype : 동영상인지 이미지인지 알려주는 메서드
- HttpServlet : 

#2강

##자바스크립트 기본
-이런 이런