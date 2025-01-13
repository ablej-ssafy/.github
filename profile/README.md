# [Able Recruit 👔](https://www.noteme.kro.kr)

## Index

#### &emsp; [➤ 프로젝트 소개](#project-intro)<br>

#### &emsp; [➤ 프로젝트 설계](#project-design)<br>

#### &emsp; [➤ 기능 소개](#feature-intro)<br>

#### &emsp; [➤ 산출물](#deliverables)<br>

<br>

# 📄프로젝트 소개 {#project-intro}

## 기획 배경

실제 외부 조사기관 자료에 의하면, 취업 준비에 어려움을 겪고 있는 취업 준비생이 약 82%에 달하는 것으로 나타났습니다.
<br><br>
대부분 채용 공고 탐색과 자신을 어필하는 과정에서 크게 어려움을 겪고 있음을 알 수 있었습니다.
<br><br>
AI를 활용한 채용 공고 추천과, 이력서 및 포트폴리오 관리를 도와줌으로써 이러한 문제를 해결하고자 프로젝트를 진행하게 되었습니다.

## 프로젝트 소개

### 🎯 AI 기반 종합 채용 시스템

1. 맞춤 채용 공고 추천

2. 포트폴리오 관리

3. GitHub 프로젝트 분석

4. 면접 예상 질문 메일링

<br>

## 📆 프로젝트 기간

<table border="1" cellpadding="10">
    <tr>
        <th>프로젝트 기간</th>
        <td>2024.10.14 ~ 2024.11.19 (5주)</td>
    </tr>
</table>

<br>

## 팀 소개

<table border="1" cellpadding="15">
    <tr>
        <th>Contributors</th>
        <td>Position</td>
    </tr>
    <tr>
        <th>김범수</th>
        <td>- 팀장 <br> - BackEnd <br> - AI <br> - GitHub 분석 <br> - 이력서 API</td>
    </tr>
    <tr>
        <th>김용수</th>
        <td> - BackEnd <br> - 메일링 서비스 <br> - 외부 이력서 인식 AI</td>
    </tr>
    <tr>
        <th>민준수</th>
        <td>- BackEnd <br> - INFRA <br> - 기업 및 채용공고 API</td>
    </tr>
    <tr>
        <th>김보현</th>
        <td>- FrontEnd <br> - 회원가입 / 로그인 <br> - 포트폴리오 작성 페이지</td>
    </tr>
    <tr>
        <th>김도영</th>
        <td>- FrontEnd <br> - ISR 적용 <br> - 공고 / 회사 상세 페이지 <br> - 포트폴리오 페이지</td>
    </tr>
    <tr>
        <th>윤하연</th>
        <td>- FrontEnd <br> - 이력서 업로드 및 공고 추천 <br> - GitHub 분석 <br> - CSS 스타일링</td>
    </tr>
</table>

<br><br><br>

# 📄프로젝트 설계 {#project-design}

## 개발 환경

BE : SpringBoot, JPA, QueryDSL, Spring AI, Spring Security, RestDocs, Mockito, thymeleaf
<br>
FE : NextJS 14.2.15, React 18, TypeScript, mongoose
<br>
INFRA : PostgreSQL, Redis, GCS, MinIO, MongoDB, GitHub Actions
<br>
AI : GhatGPT API, Llama, FastAPI, celery

<br>

### BackEnd

  <div style="display: flex; flex-direction: row; align-items:center;">
    <img alt="JAVA" src="https://img.shields.io/badge/Java 17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">
    <img alt="SpringBoot" src="https://img.shields.io/badge/springboot-%236DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white">
    <img alt="springsecurity" src="https://img.shields.io/badge/springsecurity-6DB33F.svg?style=for-the-badge&logo=springsecurity&logoColor=white">
    <img alt="thymeleaf" src="https://img.shields.io/badge/thymeleaf-005F0F.svg?style=for-the-badge&logo=thymeleaf&logoColor=white">
  </div>
  
### FrontEnd

  <div style="display: flex; flex-direction: row; align-items:center;">
    <img alt="next.js" src="https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=next.js&logoColor=white">
    <img alt="typescript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
    <img alt="React" src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black">
    <img alt="SCSS" src="https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white">
    <img alt="eslint" src="https://img.shields.io/badge/eslint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white">
  </div>

### AI

  <div style="display: flex; flex-direction: row; align-items:center;">
    <img alt="ollama" src="https://img.shields.io/badge/ollama-000000?style=for-the-badge&logo=ollama&logoColor=white">
    <img alt="fastapi" src="https://img.shields.io/badge/fastapi-009688?style=for-the-badge&logo=fastapi&logoColor=white">
    <img alt="celery" src="https://img.shields.io/badge/celery-37814A?style=for-the-badge&logo=celery&logoColor=white">
  </div>

### INFRA

  <div style="display: flex; flex-direction: row; align-items:center;">
    <img alt="ubuntu" src="https://img.shields.io/badge/ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"> 
    <img alt="docker"src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> 
    <img alt="Nginx" src="https://img.shields.io/badge/nginx-009539?style=for-the-badge&logo=nginx&logoColor=white"> 
    <img alt="jenkins"src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white">
    <img alt="githubactions"src="https://img.shields.io/badge/githubactions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
    <img alt="minio"src="https://img.shields.io/badge/minio-C72E49?style=for-the-badge&logo=minio&logoColor=white">
  </div>
  
### DB

  <div style="display: flex; flex-direction: row; align-items:center;">
    <img alt="postgresql" src="https://img.shields.io/badge/postgresql-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"> 
    <img alt="mongodb" src="https://img.shields.io/badge/mongodb-47A248?style=for-the-badge&logo=mongodb&logoColor=white">
    <img alt="redis"src="https://img.shields.io/badge/redis-FF4438?style=for-the-badge&logo=redis&logoColor=white">
  </div>

### 협업 툴

  <div style="display: flex; flex-direction: row; align-items:center;">
    <img alt="github" src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"> 
    <img alt="gitlab" src="https://img.shields.io/badge/gitlab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white"> 
    <img alt="jira" src="https://img.shields.io/badge/jira-0052CC?style=for-the-badge&logo=jira&logoColor=white">
    <img alt="notion" src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
  </div>

<br><br><br>

# 📄기능 소개 {#feature-intro}

### 1. 맞춤 채용 공고 추천

<p>1.1 이력서 등록</p>
<p>&emsp;- Drag And Drop을 이용해 손쉽게 이력서를 등록할 수 있습니다.</p>

<div style="display: 'grid', gridTemplateRows: 'repeat(3, minmax(0, 1fr))', gap: '0.75rem'">
  <img src='./readMeImage/Section01/Main.png' alt='Main' width=300px>
  <img src='./readMeImage/Section01/NoResume.png' alt='NoResume' width=300px>
  <img src='./readMeImage/Section01/ResumeDND.png' alt='ResumeDND' width=300px>
  <img src='./readMeImage/Section01/ResumeUpLoad.png' alt='ResumeUpLoad' width=300px>
</div>

<br>

<p>1.2 이력서 분석</p>

<p>&emsp;- 등록한 이력서를 AI 서버로 보내 맞춤 채용 공고를 추천해줍니다.</p>

<div style="display: 'grid', gridTemplateRows: 'repeat(3, minmax(0, 1fr))', gap: '0.75rem'">
  <img src='./readMeImage/Section01/UpLoadComplete.png' alt='UpLoadComplete' width=300px>
  <img src='./readMeImage/Section01/ResumeLoading.png' alt='ResumeLoading' width=300px>
  <img src='./readMeImage/Section01/ResumeRecruitment.png' alt='ResumeRecruitment' width=300px>
  <img src='./readMeImage/Section01/ResumePreview.png' alt='ResumePreview' width=300px>
</div>

<br>

<p>1.3 채용 상세 정보 및 회사 상세 정보 확인 가능</p>

<div style="display: 'grid', gridTemplateRows: 'repeat(3, minmax(0, 1fr))', gap: '0.75rem'">
  <img src='./readMeImage/Section01/RecruitmentDetail.png' alt='RecruitmentDetail' width=300px>
  <img src='./readMeImage/Section01/CompanyDetail.png' alt='CompanyDetail' width=300px>
</div>

<br>

### 2. 포트폴리오 관리

<p>2.1 포트폴리오 작성</p>
<p>&emsp;- 포트폴리오를 직접 작성할 수 있습니다</p>
<p>&emsp;- 이러한 과정이 복잡하다면, 이미 보유한 이력서를 불러와 자동완성으로 포트폴리오를 채워줍니다.</p>
<p>&emsp;- 불러온 이력서 데이터와 현재 등록되어있는 데이터를 비교하여 원하는 정보를 선택하여 넣을 수 있습니다.</p>

<div style="display: 'grid', gridTemplateRows: 'repeat(3, minmax(0, 1fr))', gap: '0.75rem'">
  <img src='./readMeImage/Section02/NoPortFolio.png' alt='NoPortFolio' width=300px>
  <img src='./readMeImage/Section02/ResumeUpLoad.png' alt='ResumeUpLoad' width=300px>
  <img src='./readMeImage/Section02/LoadingPortFolio.png' alt='LoadingPortFolio' width=300px>
  <img src='./readMeImage/Section02/SelectResume.png' alt='SelectResume' width=300px>
  <img src='./readMeImage/Section02/AutoComplete.png' alt='AutoComplete' width=300px>
</div>

<p>2.2 포트폴리오 순서 및 템플릿 변경</p>
<p>&emsp;- 프로필을 제외한 모든 요소의 순서를 원하는대로 변경할 수 있습니다.</p>
<p>&emsp;- 완성된 포트폴리오는 4가지의 템플릿 중에서 선택할 수 있습니다.</p>
<p>&emsp;- 포트폴리오의 공개 여부 또한 설정할 수 있어, 공개하고 싶지 않은 경우 비공개 설정이 가능합니다.</p>

<div style="display: 'grid', gridTemplateRows: 'repeat(3, minmax(0, 1fr))', gap: '0.75rem'">
  <img src='./readMeImage/Section02/OrderDragAndDrop.png' alt='OrderDragAndDrop' width=300px>
  <img src='./readMeImage/Section02/PortFolioTemplate.png' alt='PortFolioTemplate' width=300px>
  <img src='./readMeImage/Section02/PrivatePortFolio.png' alt='PrivatePortFolio' width=300px>
</div>

<br>

### 3. GitHub 프로젝트 분석

<p>3.1 깃허브 연동</p>
<p>&emsp;- 이메일 인증 후, 깃허브와 연동하여 public으로 공개된 repository를 가져올 수 있습니다.</p>

<div style="display: 'grid', gridTemplateRows: 'repeat(3, minmax(0, 1fr))', gap: '0.75rem'">
  <img src='./readMeImage/Section03/NoGitHub.png' alt='NoGitHub' width=300px>
</div>

<p>3.2 repository 및 branch 선택</p>
<p>&emsp;- 분석할 repository와 branch를 선택하여 분석 요청을 할 수 있습니다.</p>

<div style="display: 'grid', gridTemplateRows: 'repeat(3, minmax(0, 1fr))', gap: '0.75rem'">
  <img src='./readMeImage/Section03/SelectRepository.png' alt='SelectRepository' width=300px>
</div>

<p>3.3 프로젝트 분석 완료</p>
<p>&emsp;- 분석이 완료되면 등록된 이메일로 프로젝트 분석 결과가 전송됩니다.</p>
<p>&emsp;- 전송된 이메일에서는 프로젝트 요약, 사용 기술, 핵심 기능 및 프로젝트 강점을 확인할 수 있습니다.</p>

<div style="display: 'grid', gridTemplateRows: 'repeat(3, minmax(0, 1fr))', gap: '0.75rem'">
  <img src='./readMeImage/Section03/AnalyzeRequest.png' alt='AnalyzeRequest' width=300px>
  <img src='./readMeImage/Section03/AnalyzeMail.png' alt='AnalyzeMail' width=300px>
  <img src='./readMeImage/Section03/AnalyzeResult.png' alt='AnalyzeResult' width=300px>
</div>

<br>

### 4. 면접 예상 질문 메일링

<p>4.1 면접 질문 메일링 서비스</p>
<p>&emsp;- 등록된 이력서를 기반으로 CS 질문을 생성하여 매일 아침에 등록된 이메일로 CS 질문이 전송됩니다.</p>

<div style="display: 'grid', gridTemplateRows: 'repeat(3, minmax(0, 1fr))', gap: '0.75rem'">
  <img src='./readMeImage/Section04/QuestionMail.png' alt='QuestionMail' width=300px>
  <img src='./readMeImage/Section04/QuestionDetail.png' alt='QuestionDetail' width=300px>
</div>

<br><br><br>

# 📄산출물 {#deliverables}

##### [⚙ Architecture](./readMeImage/PROJECT/Swagger.png)

##### [⚙ ERD](./readMeImage/PROJECT/ERD.png)

##### [📋 API 명세서](./readMeImage/PROJECT/Swagger.png)

<br><br><br>

### [커밋 컨벤션 🎯](https://www.notion.so/11ff07ca98df81199ddbffe1d083674d)

- `feat` : 새로운 기능 추가

- `fix` : 버그 수정

- `docs` : 문서 수정

- `style` : 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우

- `refactor`: 코드 리펙토링

- `test` : 테스트 코드, 리펙토링 테스트 코드 추가

- `chore` : 빌드 업무 수정, 패키지 매니저 수정

- `design` : CSS 등 사용자 UI 디자인 변경

- `hotfix` : 급하게 치명적인 버그를 고쳐야 하는 경우

- `merge` : 만약 Merge 할 때 Conflict가 발생할 경우, 사용할 커밋 유형
