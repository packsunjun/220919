# 220919
tip:emmet, snippet, jsdoc

생활코딩 - https://opentutorials.org/course/1
모던js튜토리얼 - https://ko.javascript.info/
w3 - https://www.w3schools.com/
css zengar - http://www.csszengarden.com/

2009 - ES5
2015 - ES6

트랜스파일 - 바벨, 트렌스컴파일, ES5, ts->js
(PS C:\00ts\work> tsc -v
Version 4.8.3
PS C:\00ts\work> tsc .\hello.ts
PS C:\00ts\work> node .\hello.js
Hello world!!!)

touch 시간파일 생성 (유닉스0 윈도우x)

타입스크립트는 nodejs 프로젝트를 마든 다음, 개발언어를 타입스크립트로 설정하는 방식으로 진행
Nodejs 프로젝트는 디렉토리 하나 만들고 여기에 package.json 파일을 만드는 것 으로 시작

>mkdir ch02-1
>cd ch02-1
>npm init --y   //package.json 파일을 만드는 것

나에게는 typescript와 ts-node 패키지가 설치되어 있지만 다른 개발자의 컴퓨터에는 설치되어 있지 않을 수 있기 때문에

> npm i -D typescript ts-node

타입스크립트 라이브러리 혹은 패키지 설치

>npm i -D @types/node
============================
타입스크립트 프로젝트는 타입스크립트 컴파일러의 설정 파일인 tsconfig.json 파일이 있어야 합니다.

>tsc --init

src 디렉토리와 소스 파일 만들기
>mkdir -p src/utils
>touch .\src\index.ts .\src\utils\makePerson.ts

. >하위 디렉토리 들어가기
.. >상위 디렉토리로 나가기
