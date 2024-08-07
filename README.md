# [타임인사이트] 전문가 시간 경매 서비스
## 프로젝트 소개
- 미국의 유명 투자자 워렌버핏과의 점심식사 경매에서 착안하여, 전문가의 시간을 경매에 부쳐 판매하는 서비스입니다.
- 개인 프로젝트로 기획, DB 설계, 화면 및 백엔드 구현을 담당했습니다.

## 개발 기간
2024.05.01 ~ 2024.05.29

## ERD
![ERD이미지](https://github.com/sprintkim/TimeInsight/blob/6901ef1bf51769592d54e5e7ac8a6711724b472e/Timeinsight_erd.png)

## 개발 환경 및 기술 스택
### 백엔드
- **언어**: Java 21
- **프레임워크**: Spring Boot
- **데이터베이스**: Oracle 11g
- **통합 개발 환경(IDE)**: STS
- **빌드 도구**: Apache Maven 3.9.6

### 프론트엔드
- **언어 및 마크업**: HTML, CSS, JavaScript
- **라이브러리**: React
- **통합 개발 환경(IDE)**: VSCode

### 협업 도구
- **버전 관리**: GitHub

## 주요 기능
### 1. 공통 기능
  - 회원 가입, 로그인, 회원 탈퇴
  - JWT, AOP, BcryptPasswordEncoder를 활용한 사용자 인증 및 권한 관리, 패스워드 암호화

### 2. 전문가 관리
  - 전문가 등록, 조회, 수정, 삭제
  
### 3. 경매 상품 관리
  - 시간 경매 상품 등록, 조회, 수정, 삭제

### 4. 경매 시스템
  - 경매 입찰/낙찰/패찰 시스템: 스케줄러를 활용한 경매 LifeCycle 관리
  - 낙찰금 결제 시스템: Portone 결제 API를 연동한 낙찰금 결제 기능

### 5. 실시간 경매 입찰 현황 조회
  - WebSocket을 활용한 실시간 입찰 정보 제공

![경매 시스템](https://github.com/sprintkim/TimeInsight/blob/11173c7cf151cdec984fa954e51a807878bc478f/%EA%B2%BD%EB%A7%A4%20%ED%94%84%EB%A1%9C%EC%84%B8%EC%8A%A4.png)
