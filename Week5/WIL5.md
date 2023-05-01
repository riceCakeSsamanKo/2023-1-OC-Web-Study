# HTML5

  ## HTML5 기본 정리
  시작시 <!DOCTYPE html>로 시작한다. 모든 내용은 <html> </html> 사이에 기술되며
  <head></head> 태그 사이에는 메타데이터가, <body></body> 사이에는 우리에게 보여지는 내용이 기술된다.

  태그는 보통 <tag>content</tag>과 같이 기술되는 것이 일반적이다. 그러나 꼭 종료 태그가 있어야하는 것은 아니며 종료 태그가 없는 요소를 빈 요소라고 한다.
  <img src = "abc.jpg>

  ## 시멘틱 웹
  검색엔진이 크롤링을 하는데에는 html의 시멘틱 요소를 읽어서 해당 데이터의 의미를 파악해 관련된 데이터들과 함께 의미와 관련성을 가지는 거대한 데이터베이스로 구축한다.
  로봇이 크롤링을 하는데 있어 해당 콘텐츠의 의미를 명확히 표현하는 태그를 시멘틱 태그라고 한다.

  ## head tag
  head 요소 사이에는 title, style, link, script에 대한 메타 데이터가 포함된다. 메타데이터는 화면에 표시되지 않는 설정과 같은 데이터이다.

  ### title tag
  <head>
    <title>문서 제목</title>
  </head>
  위와 같은 형태로 구성되어 있으며 브라우저의 탭에 표시되는 문서 제목을 정의한다.

  ### style tag
  <head>
    <style>
      body {
        background-color: yellow;
        color: blue;
      }
    </style>
  </head>
  html 문서를 위한 style 정보를 정의한다.

  ### link tag
  <head>
    <meta charset="utf-8">
    <title>문서 제목</title>
    <link rel="stylesheet" href="style.css">
  </head>
  외부 리소스와 연결, 연계 정보를 정의한다. html, css와 주로 사용.

  ### script tag
  <head>
    <script>
      document.addEventListener('click', function () {
        alert('Clicked!');
      });
    </script>
  </head>
  자바 스크립트 코드를 해당 문서에 적용한다.

  <head>
    <meta charset="utf-8">
    <script src="main.js"></script>
  </head>
  직접 코드를 치는 것이 아닌 위 처럼 src 어트리뷰트로 자바스크립트 파일과 연결 가능.

  ### meta tag
  desciption, keywords등 브라우저나 검색엔진에서 사용될 메타데이터를 정의하는 역할을 한다. 

  <meta charset="utf-8">
  charset 어트리뷰트로 해당 브라우저가 사용할 문자셋을 정의한다.

  <meta name="keywords" content="HTML, CSS, XML, XHTML, JavaScript">
  keywords는 검색엔진이 사용할 keywords를 정의한다.

  <meta name="description" content="Web tutorials on HTML and CSS">
  descripton으로는 웹페이지의 설명을 명시한다.

  ## body tag
  웹 페이지 상에서 보이는 부분을 body에 기술한다

  ### strong tag
  볼드체를 지정

  ### p tag
  <p>를 통해서 단락을 지정