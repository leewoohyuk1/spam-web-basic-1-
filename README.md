# spam-web-basic-1-

첫 번째 커밋이다~!

1.html : 웹사이트의 뼈대를 만드는 역할 기본 구조 역할

2.ss : 웹사이트를 꾸며주는 역할  디자인 역할

3.js(JavaScript) : 기능을 넣는 역할

4.Library: 함수들의 모임 남이작성한 코드쓰기위해 만들어진 놈


5.npm 사용 --> js라이브러리 관리가 쉬어짐 wedpack쓰면js라이브러리 용량줄여줌

6.nodejs : js파일을 pc아무데서나 실행할 수 있도록 도와줌!!
spa라이브러리 Vue,Svelte,React,Angular 등등의 라이브러리들을 갖다 쓰면 html 생성 구조 변경이 매우 쉬워진다.

7.build:
번들링툴이용해서JS파일 하나로 합치기 
자바스크립트 라이브러지 vue,Svelte,React,Angular등등 html관리가 쉬어짐+새로고침 없이 부드럽게 동작하는 사이트 만들기 가능 단점: 수많은 변수관리 어려움 그래서 변수관리 

8.state managemant: SPA에서 사용중인 변수들 관리 
매우큰 단점 구글검색 결과 노출 어려움 첫페이지 로딩 오래 걸림
해결하기 위해서 나온 것 server side rendering:html을 서버에서 만들어서 보내줌

9.meta-framework -js 이용시 간단한 서버 만들기 가능+server side rendering도가능함

10.TypeScript: 타입기능이 업글된 자바스크립트
타입스크립트 문법으로 코드 짜고 변수나 함수에 타입을 집어넣을 수 있다.

11.Serverless : 서버를 대신 만들어주는 서비스 회원인증, DB입출력, 기타 서버 기능 알아서 해줌
단점:종량제라 금액이 매운맛이다(아유 매워라)

<<<<<<< Updated upstream
12.결론:요즘 리액트 같은 이상한 어려운 라이브러리사용하기시작함-->프론트앤드 개발자가 많이 필요해짐 돈도 잘범 이상한 라이브러리나 신기술 도입하면 프론트앤드 개발자라는 전문성과 밥그릇을지킬수있음(일석이조)
=======
# a
## b
### c
#### d
##### e
###### f
q태그

- 1
- 2
 - 3

```javercript
console.log("hello world!");
```
# javercript
## 실행방법
- 일단 모든 브라우저는 자바스크립트를 해석하고 실행 할수있는자바 스크립트 엔진을 내장 하고있다.
- 실행 방법을 알아보자 먼저 HTML index.html 파일에 ! tab을 하고 ` </body> </body>` 사이에 ` <script>` 입력후  그 사이에 
```javercript 
console.log("hello wold!");
``` 
을 입력해준다.
- index.html 우클릭후 라이브 서버 만들기 후 F12를 눌러 console를 눌러 확인해보면
입력 하였던 Hello word! 가 적혀있는걸 확인 할수있다.
- app.js 에서 터미널 개방후 cd js 입력 그 다음 ` nood app.js ` 입력하면 앞서 입력 하였던 hello word! 가 출력 돼는걸 볼수있을것이다.



CLMEL표기법 숫자 $ _만 가능(-,*등은불가)
첫글자로는 숫자 불가

VER 재선언 가능 재할당 가능 오이스팅 가능 전역변수 

호이스팅: 밑에서 선언한 변수

LET 재선언 불가능 재할당 가능 블록범위 변수

CONST 재선언 불가능 재할당 불가능,상수

자바 스립트 자료형 숫자,문자열,UNLL(값이 존재 하지 않음) UNDEFINWD(변수가 초기화 되지 않거나 값 할당x).심벌,객체,배열,함수
 

brake; 반복울 추게함
cotinue; 반복을 계속함

do while 이 있음 

let i = 1;
let j = 2;

while (j<10) {
    i = 1
    while (i<10){
        console.log( j + " * " + i + " = " + i*j )
        i++;
    }
    j++
}
이런식 으로 하면 
j가 10 전까지 계 속 바뀌 고 다음 으로 넘어 갈때 i의 값도 바뀐다 그러면 i*J의 값을 게속 10 전 까지 9*9 까지 출력 하게된다
for.js 의 for 문 같은 경우 중간중간 ; 로 나눠준다 


for (let i = 1; i<10; i++) {
    console.log("2 * " + i + " = " + i*2)
}
이렇게 하면 i 가 10전 까지 올라 가면서 구구단 2단 을 출력 하는 for문이 완성이 된당