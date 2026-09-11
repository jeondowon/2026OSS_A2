# 오픈소스 스튜디오 01분반

22300650 / 전도원

## Assignment 2. HTML & CSS Practice

한동대학교 오픈소스스튜디오 과제 02.
동일한 HTML 문서에 서로 다른 CSS를 적용해 보며 HTML과 CSS의 역할을 이해하고, 여러 페이지를 하나의 사이트로 연결한 뒤 Git/GitHub로 버전을 관리하고 Vercel로 배포하는 과정을 실습한 프로젝트입니다.
(교수님 안내에 따라 Bootstrap 단계(STEP 4)는 스킵했습니다)

## Pages

- Vercel Deploy: https://2026-oss-a2.vercel.app/
- index.html: 모든 페이지들을 연결하는 메인 home 페이지

  링크: https://2026-oss-a2.vercel.app/index.html

- nostyle.html: W3Schools CSS Demo No StyleSheet을 참고하여 CSS 없이 HTML 구조만으로 작성한 기본 페이지

  링크: https://2026-oss-a2.vercel.app/nostyle.html

- style1.html: nostyle.html에 W3Schools Stylesheet 1 스타일을 적용한 페이지

  링크: https://2026-oss-a2.vercel.app/style1.html

- style2.html: nostyle.html에 W3Schools Stylesheet 4 스타일을 적용한 페이지

  링크: https://2026-oss-a2.vercel.app/style2.html

## Weekly Review

### Key Learning

1. HTML 태그
   h1 ~ h3, p, div, a 등 기본적인 html 태그들을 배웠고, 부가적으로 div 대신 사용 가능한 시맨틱 태그: header, nav, aside, main 등을 배웠다.

2. CSS
   id, class 선택자와 함께 margin, padding, border, width/height, position(absolute/relative) 등을 이용해 레이아웃 설정하는 방법을 익혔습니다.

3. 여러 페이지를 하나의 사이트로 연결하는 방법
   index.html과 각 페이지에 상호 링크(a 태그, onclick)를 추가하여 하나의 사이트처럼 동작하도록 구성하는 법을 배웠습니다.

### HTML vs CSS

HTML은 페이지의 구성과 구조(heading, p, list, div 등)를 정의하는 역할을 하고, CSS는 그 구조에 개성 및 디자인(색상, 폰트, 여백, 배치 등)을 입히는 역할입니다.

### Bootstrap 사용법

교수님 지시에 따라 Bootstrap 단계 스킵하였음.

### Problem & Solution

문제
Stylesheet 1 디자인을 적용했을 때 메뉴바의 너비가 잡히지 않고 화면 끝에서 끝까지 펼쳐지는 문제가 있었습니다.

해결
개발자 도구로 원본 사이트의 레이아웃을 확인하며 #menubar에 width: 200px 스타일을 추가하고 다른 요소들의 css 값도 하나씩 확인하며 디자인을 적용했습니다.

### AI Usage

1. 수정해야할 부분을 찾아낸 후 수정작업을 진행할 때 반복적인 작업이 있다면 AI를 사용하여 작업 시간을 단축하였습니다 (예: div 태그 -> 시맨틱 태그들로 변경).
2. index.html의 디자인을 Claude Code를 사용하여 제작했습니다.
3. Claude Code를 이용해 nostyle.html/style1.html/style2.html의 구조 일관성을 마지막에 점검했습니다.
4. 과제 instruction을 첨부하여 혹시 빠트린것이 없는지 ai를 활용하여 점검하였습니다.

### Reflection

같은 HTML이라도 CSS 선택자를 어떻게 설계하느냐(id vs class)에 따라 유지보수성이 달라진다는 것을 느꼈고, CSS를 별도 파일로 분리해서 관리하는 것이 더욱 효율적일 것이라는 생각이 들었습니다.
