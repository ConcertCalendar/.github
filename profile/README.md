# 📌 PushPin 

## 프로젝트 소개
### 내한 공연을 좋아하는 사람들을 위한 공연 일정 관리 및 커뮤니티 프로젝트

#### 👀 내한공연 일정을 달력에서 확인해보세요 <Br>
내한공연 일정이 등록된 달력에서 편하게 확인이 가능합니다
#### 📍 좋아하는 공연을 북마크 해보세요<br>
내가 좋아하는 공연을 북마크하고 인기있는 공연도 찾아보세요
#### ✏️ 즐겁게 관람한 공연에 대한 후기를 공유해주세요 <br>
공연을 못 본 사람들을 위해 공연 후기 게시판에서 후기를 공유해봐요

## 기술 스택

### FRONTEND
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white"/> <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=Redux&logoColor=white"/>  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white"/> <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white"/> <img src="https://img.shields.io/badge/Scss-CC6699?style=for-the-badge&logo=Sass&logoColor=white"/> 
<img src="https://img.shields.io/badge/cssmodules-000000?style=for-the-badge&logo=cssmodules&logoColor=white"/> <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=CSS3&logoColor=white"/> <img src="https://img.shields.io/badge/EC2-FF9900?style=for-the-badge&logo=amazon ec2&logoColor=white"> <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=NGINX&logoColor=white">

### BACKEND
<img src="https://img.shields.io/badge/SPRINGBOOT-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/JUNIT5-25A162?style=for-the-badge&logo=junit5&logoColor=white"> <img src="https://img.shields.io/badge/DOCKER-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/EC2-FF9900?style=for-the-badge&logo=amazon ec2&logoColor=white"> <img src="https://img.shields.io/badge/RDS-527FFF?style=for-the-badge&logo=amazon rds&logoColor=white"> <img src="https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazon s3&logoColor=white"> <img src="https://img.shields.io/badge/GITHUB ACTIONS-2088FF?style=for-the-badge&logo=github actions&logoColor=white">

### 협업
<img src="https://img.shields.io/badge/JIRA-0052CC?style=for-the-badge&logo=jira&logoColor=white"> <img src="https://img.shields.io/badge/NOTION-000000?style=for-the-badge&logo=notion&logoColor=white"> <img src="https://img.shields.io/badge/SLACK-4A154B?style=for-the-badge&logo=slack&logoColor=white">



## 서비스 아키텍처
![image](https://user-images.githubusercontent.com/77186025/235592275-0975913d-858e-4eb0-a6bc-3bc49d35c137.png)


## 주요 기능
[각 기능별 Use Case](https://github.com/ConcertCalendar/.github/wiki/Use-Case)

### 📍 공연 북마크
- 좋아하는 공연을 북마크 할 수 있습니다
### ✏️ 공연 후기 작성
- 게시물/댓글/답글을 작성할 수 있습니다
### 📆 공연 정보 조회
- 캘린더로 공연 일정을 조회할 수  있습니다
### 🔎 공연/게시글 검색
- 원하는 공연을 검색할 수 있습니다
- 키워드가 들어간 게시물을 검색할 수 있습니다
### 👨‍💻 마이 페이지
- 북마크한 공연을 확인할 수 있습니다
- 작성한 게시물을 확인할 수 있습니다

<br>

## 프로젝트에서 발생했던 Technical Issue / 트러블 슈팅
[ 👉 자세한 트러블 슈팅 과정은 여기로](https://github.com/ConcertCalendar/.github/wiki/Technical-Issue)

### BACKEND
- Github Action & S3 & Code Deploy에서 Github Action & Docker로 CI/CD 자동화 방식 변경
- JDBC + Bulk Insert로 삽입 쿼리 성능 개선
- Refresh Token 재발급 버그 해결
- QueryDSL로 동적쿼리 적용하여 공연 북마크 메서드 개수 줄이기
- yml 내 설정 변경을 통해 JavaMailSender Bean 에러 해결
- EC2에 Nginx 도입하여 포트포워딩 구현


## 배운점 / 아쉬운점

### FRONTEND
 - HTML5과 CSS3를 이용하여 레이아웃을 잡는 법을 배웠습니다.
 - axios와 fetch를 이용하여 REST API 통신 방식에 대해 배웠습니다.
 - Redux를 사용하여 React State의 상태 관리 하는 것을 배웠습니다.
 - React-router-dom을 사용하여 페이지 라우팅 하는 법을 배웠습니다.
 - CSS moudle을 사용하여 CSS module의 필요성을 배웠습니다.
 - CSS animation을 사용하여 loading 애니메이션을 만드는 법을 배웠습니다.
 - React 함수형 컴포넌트를 만드는 법에 대하여 배웠습니다.
 - Typescript 와 Javascript의 차이점에 대하여 배우고 Typescript를 사용한 React 컴포넌트를 만드는 것을 배웠습니다.
 - JWT를 이용하여 로그인을 유지하는 법을 배웠습니다.
 - Cookie를 이용하여 데이터를 저장하는 방법을 배웠습니다.
 - 정규표현식을 활용하여 이메일 형식을 위반하는지 확인하는 법을 배웠습니다.
### BACKEND
- Github Action과 Docker를 통한 CI / CD 자동화를 경험할 수 있습니다.
- JIra 협업 툴을 사용해 프론트엔드 개발자와 협업을 진행했습니다.
- JWT의 구조를 학습하고 재발급 로직에 대해서 고민할 수 있었습니다.
- 동적 쿼리를 구현하여 유연한 비즈니스 로직 구성할 수 있었습니다.
- 테스트코드는 작성했지만 여러 서비스가 종합된 통합 테스트를 진행하지 못한 점이 아쉽습니다.

## ERD
![concertCalendar (2)](https://user-images.githubusercontent.com/80939285/235438919-344dc126-5e2f-47c8-bd1e-530265c5240d.png)
