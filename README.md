# Board
#### ⚪ About Project
* ##### 패스워드 인증기반 글(작성, 수정, 삭제, 조회), 댓글(작성, 삭제)을 가진 게시판 서비스 앱
* ##### NodeJs, Express, MongoDB, 템플릿엔진인 express-handlebars를 사용해 게시판 서비스 앱 구축
* * *
#### ⚪ Usage
https://www.youtube.com/watch?v=b2JAx2kzs_g
<p align="center">
  <img src="https://user-images.githubusercontent.com/79093184/259310139-8e99ac09-9b99-4840-81bb-12ff315b98b0.png" align="center" width="35%">
  <img src="https://user-images.githubusercontent.com/79093184/259310159-58570160-da66-4e3f-9fbf-c0b6f7c4098d.png" align="center" width="35%">
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/79093184/259310145-eef27935-8a75-4cd2-8745-9b553bdc9948.png" align="center" width="35%">
  <img src="https://user-images.githubusercontent.com/79093184/259310151-c0403266-3aa2-42a9-9978-0ee1a50130fe.png" align="center" width="35%">
</p>

* * *
#### ⚪ Built With
* ##### template engine
<img src="https://img.shields.io/badge/handlebars.js-3776AB?style=for-the-badge&logo=Handlebars.js&logoColor=white">

* ##### backend
<img src ="https://img.shields.io/badge/javascript-F7DF1E.svg?&style=for-the-badge&logo=JavaScript&logoColor=white"/> <img alt="express" src ="https://img.shields.io/badge/express-339933.svg?&style=for-the-badge&logo=express&logoColor=white"/> <img alt="nodedotjs" src ="https://img.shields.io/badge/nodejs-339933.svg?&style=for-the-badge&logo=nodedotjs&logoColor=white"/> <img alt="mongodb" src ="https://img.shields.io/badge/mongodb-339933.svg?&style=for-the-badge&logo=mongodb&logoColor=white"/>

* * *
#### ⚪ Getting Strated
* ##### Prerequisites: npm, node, MongoDB Connection URL
* ##### Installation & Execution
```bash
git clone https://github.com/MpqM/WebApp_Board.git
# Change the MONGO_CONNECTION_STRING value in the configs/mongodb-connection.jsfile with yours
npm install
npm start
```
* * *
#### ⚪ Description 
* ##### User
    * ##### 세션 인증 방식을 이용한 사용자 인증 + 로그인, 로그아웃, 회원가입, NAVBAR에서 사용자 이름, 프로필 사진 출력
    * ##### react-hook을 이용한 커스텀 유효성검증 로그인, 회원가입용 Form 객체 구현
    * ##### react-router-dom 이용해 라우팅 구현, 삼항연산자 조건식을 사용해 사용자 인증시에만 서비스 이용가능하게 만듬
* ##### Content
   * ##### 넷플릭스의 슬라이드를 구현하기 위해 Movie를 타입 + 장르별로 배열로 만들어 저장
   * ##### 프론트엔드에서 이중배열로 데이터가 API호출이 나와서 자식배열의 MovieId를 추출하는 로직 구현
   * ##### 장르가 선택되지 않으면 셔플 알고리즘을 통해 가지고 있는 모든 영화를 무작위로 배열
* ##### Movie
    * ##### Movie 삭제, 작성, 수정
    * ##### 캐러셀을 이용한 Movie 슬라이더 생성
* ##### RESTAPI
    * ##### USER: 회원가입, 로그인, 로그아웃, 인증정보가져오기, 삭제, 수정, 조회, 전체조회, 쿼리를 통한 월별 유저 가입수 통계
    * ##### Content: 삭제, 생성, 쿼리(type & genre)를 통한 조회 기능
    * ##### Movie: 생성, 삭제, 수정, 쿼리(type | name)을 통한 조회 기능
    * ##### 자세한 내용은 postman, server/src/controllers, routes 주석 참조
* * *
#### ⚪ Roadmap & Realization & Study
* ##### 포스트맨으로 API를 테스트하며 프로젝트 진행
* ##### 프론트엔드를 아무 지식없이 하다보니 스파게티 코드를 만들고, 놓친부분이 많았음
* ##### 예를들어 라우팅 관련 조건식에서 삼항연산자를 잘못쓰던가, 동일한 의미의 콜백함수 Props 사용이 생김
* ##### useEffect를 너무 남발했고, 자식의 자식의 부모컴포넌트끼리 props를 공유할때 콜백함수를 2번 정의했음
* ##### 이를 보완하기위해 Context에 대해 공부하고 다음 프로젝트에 적용예정
* ##### 백엔드 개발에서 RESTAPI에 대한 표준을 봤는데 이해가 안가는점이 많음

* * *
#### ⚪ Writer
* ##### <span>okqkrwhdtjd@gmail.com
* <a href = "https://github.com/MpqM"><img alt="GitHub" src ="https://img.shields.io/badge/GitHub-181717.svg?&style=for-the-badge&logo=GitHub&logoColor=white"/></a> <a href = "https://MpqM.tistory.com/"> <img alt="Tistory" src ="https://img.shields.io/badge/Tistory-white.svg?&style=for-the-badge"/></a>
* * *
#### ⚪ Contributing
* ##### Fork the Project https://github.com/MpqM/WebApp_OTT
* ##### Create your Feature Branch (git checkout -b feature/AmazingFeature)
* ##### Commit your Changes (git commit -m 'Add some AmazingFeature')
* ##### Push to the Branch (git push origin feature/AmazingFeature)
* ##### Open a Pull Request
* * *
#### ⚪ Acknowledgments & License & reference
* * * *
