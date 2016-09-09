## 생활코딩 공부

생활코딩에서 공부한 내용을 정리한 것 입니다. 이곳 내용의 출처는 모두 [생활코딩](https://www.opentutorials.org/)입니다.

### HTML 문법

- HTML 

  | Hypertext         | MarkUp      | Language |
  | ----------------- | ----------- | -------- |
  | 문서와 문서를 링크(웹의 본질) | TAG형 언어를 뜻함 | 일반 음성 언어 |

  - 즉, HTML은 태그 언어( 마크업 언어 ) Html은 곧 정보이다.

  - 태그( Tag )란?

    | 안녕하세요                      | lang                |
    | -------------------------- | ------------------- |
    | **안녕**(강조)하세요              | "안녕" 부분을 강조         |
    | \<strong\>안녕\</strong\>하세요 | strong 부분이 마크업 언어!! |

- \<a\>태그

  **Anchor** (닻, 기반을 두다.)의 앞글자를 차용함.

  링크 기능을 가졌으며 링크 기능이 마치 닻이 내려져 없는듯 해서 그렇게 이름을 지은 듯함.

- 속성 

  EX 1> \<a href="http://opentutorial.org/course/1"/\> 생활코딩 \</a\>

  - href : 속성명 (html reference) - > 일종의 약속임.
  - href의 url 부분 : 속성값

  EX 2> 위의 예에서 \<a .... target="_blank"\>.....\</a\>

  라는 코드를 추가하면 링크가 새창으로 열린다. ( 공백이 속성 구분자.)

- 리스트

  - 태그 종류
    - \<li\> : 리스트의 아이템을 표시하는 태그
    - \<ul\> : unordered list 의 줄임말
    - \<ol> : ordered list 의 줄임말

- 헤드코드 필수

  - \<title\> : 웹사이트 제목
  - \<meta charset="utf-8"/\> : 한글의 께임 방지

- 의미론적인 웹

  - \<header> : 큰 제목이라는 의미를 나타냄.
  - \<nav> : 네비게이션이라는 의미를 나타냄.
  - \<article> : 본문이라는 의미를 나타냄.
  - **네비게이션 영역에서 링크를 걸으면 article로 현재 nav 내용 밑에 뜬다.**

- Client Side Tech (클라이언트 측 혁신)

  - HTML - 정보 담당( 문서 정보 )
  - CSS - 디자인 담당
  - JavaScript - 위 두개가 못하는 부분 담당


- Sever Side Tech (서버 측 혁신)
  - PHP - DB와 Client의 유명한 통신
  - MySQL - DB

### JavaScript & php

 Javascript는 웹페이지 내에서 동적인 작업 (예 : 버튼)을 처리할 때, 프로그래밍적인 기능이 필요할 때 쓰이는 script언어 이다. (웹 브라우저에서 실행됨.)

- php 삽입방법

  - php 엔진이 php interpreter를 동작시켜 실제 브라우저에서 볼 때는 html 소스로 보인다.(**서버사이드 언어기 때분에 서버에서 미리 번역해서 전송해서 그렇다.**)
  
  <?php // 예는 태그가 아니다.
  echo 20;
  ?>

  - 대부분의 코드가 들어간다. 'echo 20'은 20을 웹페이지에 출력하는 코드이다.

- JavaScript 삽입 방법
