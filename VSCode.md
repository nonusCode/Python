# Visual Studio Code

> 마이크로소프트가 개발한 소스 코드 편집기



### 확장(Extentions)

* Auto Close Tag

  > 자동으로 닫는 태그 생성

* Auto Rename Tag

  > 자동으로 여는 태그와 닫는 태그 동기화



* Bracket Pair Colorizer

  > 짝이 되는 괄호끼리 색으로 구분

  

* HTML Snippets

  > HTML 자동완성

* HTML CSS Support

  > CSS 자동완성

* Hightlight Matching Tag

  > 짝이 되는 태그끼리 색으로 구분

  

* Jinja

  > django 템플릿 태그 색으로 구분

  

* Korean Language Pack for Visual Studio Code

  > VSCode 한글로 지원

  

* Live Server

  > 웹페이지를 열어주고 실시간으로 갱신

  

* open in browser

  > 설정된 browser로 열기

  

* Prettier

  > 코드 저장 시 정해놓은 규칙에 맞게 자동으로 정렬

* Python



* vscode-icons

  > 파일 아이콘을 보기 쉽게 바꾸어줌



### 환경설정

> Python `4 Space` 들여쓰기
>
> HTML/CSS `2 Space` 들여쓰기

1. `Ctrl + Shift + p` 키를 눌러 `Preference: Open settings(JSON)` 검색

2. `4 Space`가 Default 값이기 때문에 다음과 같이 추가

   ```json
   {
   	"[html]": {
       "editor.tabSize": 2,
       },
       "[css]": {
       "editor.tabSize": 2,
       },
   }
   ```

