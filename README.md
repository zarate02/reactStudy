# reactStudy

## 설치
- nodejs
- visual studio
	- nodejs 추가
- visual studio code
	- 플러그인
		- eslint -> 문법검사기
		- prettier -> 정렬기
		- Reactjs code snippets -> 자동완성기
		- live server -> html 테스트기
	- 설정
		- default format -> prettier
		- format on save -> 체크

## Quick Start
1. npx create-react-app my-app
2. cd my-app
3. npm start

## 구조
- node_modules : node에서 사용
- public
	- index.html : 대표페이지
- src
	- index.js : index의 자바스크립트
	- components : 컴포넌트 js의 모음
	- App.js : 라우팅, 컴포넌트들을 등록
	
## Visual Studio Start
1. dotnet new react -o ReactMemo
2. cd ReactMemo/ClientApp
3. npm install
4. npm start
5. Fetch data는 서버는 실행안했으므로 접속안됨
6. cd ..
7. dotnet run
8. 모든 기능 활성화

## React Developer Tool 
- 크롬플러그인
- react 사용여부 확인
- 아이콘 빨간색 : 개발버전
- 아이콘 파란색 : 프로덕션버전
- 파일영역으로 표시안됨(옵션변경가능)
