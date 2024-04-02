# React

- React : Library
- Vue, Angular : Framework

- Webpack(웹팩) : 나눠져 있는 파일들을 압축하는 오픈 소스 JS 모듈 번들러 라이브러리
- Babel (바벨) : 최신 JS문법을 지원하지 않는 브라우저를 위해 문법 변환 시켜주는 라이브러리
- npx : 노드 패키지 실행을 도와주는 도구
- Single Page  Application (SPA) : HTML 5의 Hisroty API를 사용해서 페이지 전환 (Reat-Rounter-Dom -> History API 사용)



|---|---|
Hisroty.back() | 세션 기록의 바로 뒤 페이지로 이동하는 비동기 메서드. 브라우저의 뒤로 가기를 누르는 것과 같은 효과를 낸다. 
Historry.forward() |  세션 기록의 바로 앞 페이지로 이동하는 비동기 메서드. 브라우저의 앞으로 가기를 누르는 것과 같은 효과를 낸다.
History.go() | 특정한 세션 기록으로 이동하게 해 주는 비동기 메서드. 1을 넣어 호출하면 바로 앞 페이지로, -1을 넣어 호출하면 바로 뒤 페이지로 이동한다.
History.pushState() | 주어진 데이터를 세션 기록 스택에 넣는다. 직렬화 가능한 모든 Javascript 객체를 저장하는 것이 가능하다.
History.replaceState() | 최근 세션 기록 스택의 내용을 주어진  데이터로 교체한다.

|제목|내용|설명|
|------|---|---|
|테스트1|테스트2|테스트3|
|테스트1|테스트2|테스트3|
|테스트1|테스트2|테스트3|

---

## Node.js (npm) 
Node.js 설치

./ 현재 디렉토리에다 설치
```bash
npx create-react-app ./

claer

npm run start
npm start
```
이름 수정하면 안됨
1. publick / indes.html : 페이지 템플릿
2. src/ index.js : 자바스크립트 시작점

