# 🏥병원관리시스템

## 프로젝트소개 📢
● 병원 관리 시스템은 종이 문서 위주의 기존 병원 시스템을 디지털화하여, 사용자인 의료종사자들의 업무 효율을 높여 편리함을 제공하기 위한 프로젝트입니다.

● 잦은 화면 이동으로 인한 비효율성을 줄이고 최대한 한 화면 내에서 업무들을 처리할 수 있는 시스템을 만들고자 하였습니다. 

● 환자접수부터 예약, 진료, 처방, 방사선 사진촬영, 물리치료, 입퇴원, 수납까지 의료업무의 전반적인 흐름이 매끄럽게 진행되도록 설계하였습니다.

● 기존 병원시스템과의 차별화를 두기 위해 접수, 처방 등의 의료업무 진행 흐름에 따라 자동으로 환자의 위치를 변화시켜 환자의 현재 상태를 실시간으로 확인할 수 있도록 하였습니다.

● 또한, 다른 위치에서 일하는 의료진들이 환자에 대해 실시간으로 소통할 수 있게 메신저를 이용해 상대방을 언급하여 메시지를 보낼 수 있으며, 이를 실시간 알림으로 확인할 수 있게 구현하였습니다. 

● 의료종사자들의 업무 편의성을 높여 업무피로도를 줄임으로써 양질의 서비스를 제공하도록 하는 것이 목적입니다.

## 개발 기간 📆

2024.03.~2024.05.

## 팀소개 👨‍👩‍👧‍👦

🐜PL 선민수
<br/>
🐻‍❄️TA 최현흠
<br/>
😸AA 백지은
<br/>
🦊AA 김태원
<br/>
🐰DA 송현지
<br/>
🐭UA 김다애

## 기술스택 📚

<div align=center> 
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> 
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> 
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
  <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white">
  <br>
  
  <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"> 
  <img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white">
  <br>
  
 <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
  <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
  <br>

  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/fontawesome-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white">
  <br>
</div>

## ERD 🔖

![image](https://github.com/jjinny2023/FinalProjectHi4Crates/assets/143934167/597530dd-35e4-4c54-8213-acc7a441fe4e)

## 주요기능 🔧
액터별로 분류하여 정리

#### 환자 🙍‍♂️
- 카카오 로그인
- 진료예약
- 예약문자알림

#### 의사 👩‍⚕️
- 진료차트(진단 및 처방)
- 스케줄관리
- 협진
- 화상회의
 
#### 간호사 🧑‍⚕️
- 입/퇴원
- 간호일지
- 스케줄관리

#### 방사선사 및 물리치료 👨‍⚕️
- 방사선촬영
- 안내방송
- 물리치료

#### 원무과 👨‍💼
- 접수
- 예약
- 수납
- 관리
  
## 담당기능 👩‍💻

- 환자진료차트조회
- Auto Complete을 이용한 처방
- 방사선 검사요청/결과조회
- 진단서 작성, 조회 및 PDF 다운로드
- 퀵 오더세트CRUD
- toastUIGrid를 이용한 인사관리
- 수술기록 조회 및 작성
- Full Calendar API를 이용한 일정관리


## 프로젝트후기 🐾
AJAX와 JAVAScript의 중요성을 선생님들께서 많이 말씀하셨는데, 병원 관리시스템 특성상 한 화면에서 비동기로 구현하는 부분들이 많았기 때문에 이러한 개념을 적용하고 활용하는 기술을 익히는 매우 유익한 시간이었습니다. 
또한, 프로젝트에서는 여러 개의 테이블을 JOIN하여 복잡한 데이터를 처리해야 하는 부분도 있었습니다. 
처음에는 JOIN이 어려워 보였지만, 많은 연습과 경험을 통해 이를 숙지할 수 있었습니다. 테이블 JOIN에 대한 이해와 경험을 통해 데이터베이스 관련 업무에 대한 능력을 키워나갈 수 있었습니다.
수많은 오류메세지를 마주하고, 또는 오류가 메시지가 나오지 않는데도 동작을 하지 않아 막히는 순간들이 많았습니다. 
그 순간들을 통해 서버 debugging, 자바스크립트(크롬) debugging을 수행하며 꼼꼼하게 로직을 처리하는 능력을 향상시켰습니다.
프로젝트 진행 중에는 다양한 기능들을 한 화면에서 구현하다 보니 라이브러리 간의 충돌로 인해 기능이 동작하지 않는 경우가 있었습니다. 하지만 이러한 상황에서도 구글링을 통해 문제를 해결하는 능력을 향상시키고자 노력했습니다. 
이를 통해 문제해결 능력을 향상시키고, 유연하게 프로젝트를 이끌어 나갈 수 있었습니다.

