# 🛒 SSG.COM 클론코딩

<img width="150" src="https://github.com/6-SSGSAKK/.github/assets/73014511/da216ac2-21a3-4426-81a7-6192d2f24c30">
<img width="150" src="https://github.com/6-SSGSAKK/.github/assets/73014511/5b78e4bb-b3e9-46a9-ae4a-6c8ace2c3cc6">

<br />
<br />

- 배포 URL : https://ssgssak.shop
- Test ID : spharos1
- Test PW : spharos2024

<br />

# 목차
1. [프로젝트 개요](#1-프로젝트-개요)
2. [팀원 구성](#2-팀원-구성)
3. [시스템 아키텍처](#3-시스템-아키텍처)
4. [기술 스택](#4-기술-스택)
5. [파일구조](#5-파일구조)
6. [ERD](#6-ERD)
7. [역할 분담](#7-역할-분담)
8. [구현 기능](#8-구현-기능)
9. [트러블 슈팅](#9-트러블-슈팅)
10. [개선 목표](#10-개선-목표)
11. [프로젝트 후기](#11-프로젝트-후기)

<br />

# 1. 프로젝트 개요
**진행 기간** :  2024.02.21 ~ 2024.04.16

**목표**
- 단순히 코드를 따라치는 클론코딩이 아닌 쓱닷컴 서비스 분석 및 DB 설계 과정을 거쳐 문서 작성 및 개발 프로세스를 익힘
-  프로젝트에 다양한 기술을 적용하여 새로운 기술들을 학습
- 팀 프로젝트를 통해 협업 툴 사용 및 협업 방식을 습득

<br />

# 2. 팀원 구성
| **Name**     | 박태훈                                                                  | 박진영                                                                  | 박찬웅                                                                  | 김예진                                                                  | 서여진                                                                                                                                  |
|:------------:|:--------------------------------------------------------------------:|:--------------------------------------------------------------------:|:--------------------------------------------------------------------:|:--------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| **Profile**  |<img width="120" src="https://github.com/6-SSGSAKK/.github/assets/73014511/6fcc8ace-bc4a-4dc8-86df-451c7dff299f">|<img width="120" src="https://github.com/6-SSGSAKK/.github/assets/73014511/71bdb6da-a3b0-48e9-87ad-0dae65a58ab2"> | <img width="120" src="https://github.com/6-SSGSAKK/.github/assets/73014511/58a5f2fe-3c0e-4812-b8d5-f7410b6265c2">| <img width="120" src="https://github.com/6-SSGSAKK/.github/assets/73014511/57d3f608-042c-4ed2-ae40-671dd8057bc1"> | <img width="120" src="https://github.com/6-SSGSAKK/.github/assets/73014511/47ec7d32-12bf-4303-9198-7444e2c78c3c"> |  
| **Position** | Backend <br/> (팀장)      | Backend              | Backend          | Frontend                   | Frontend            | 


<br />

# 3. 시스템 아키텍처
![system-architecture](https://github.com/6-SSGSAKK/.github/assets/73014511/c376fc79-3cb5-459e-9a4f-e56a2b4c089e)

<br />

# 4. 기술 스택

## 💻 IDE

![VSCode](https://img.shields.io/badge/VisualStudioCode-007ACC?style=for-the-badge&logo=VisualStudioCode&logoColor=white)
![IntelliJ](https://img.shields.io/badge/intellijidea-000000?style=for-the-badge&logo=intellijidea&logoColor=white)

## 📱 Frontend
![NEXT.JS](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=Next.js&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white) ![Tailwind](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=TailwindCSS&logoColor=white)

## 💾 Backend

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens) ![SpringBoot](https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white) ![SpringBoot](https://img.shields.io/badge/springsecurity-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white) ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) ![mysql](https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white)


## 🔃 DevOPS

![docker](https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![amazonec2](https://img.shields.io/badge/amazonec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)

<br />

# 5. 파일구조

<br />

# 6. ERD
![ERD 이미지](../docs/erd.png)

<br />

# 7. 역할 분담
### 🌗Frontend
 - #### 김예진
 	- 홈, 공통컴포넌트(헤더, 푸터, 네비게이션 등), 검색 모달
 	- 상품 리스트, 이벤트 및 베스트 상품 페이지 및 기능
 	- 상품 키워드 검색, 카테고리 별 조회 페이지 및 기능
 	- 회원 상품 좋아요 페이지 및 기능
 	- 회원/비회원 상품 주문 페이지 및 기능

 - #### 서여진
 	- 로그인, 회원가입, 마이페이지
 	- 배송지 관리 페이지 및 기능
 	- 상품 상세 페이지 및 기능
 	- 회원 장바구니 페이지 및 기능
 	- 상품 리뷰 조회 및 회원 리뷰 기능


### 🌓Backend
 - #### 박태훈
 	- 자동 배포 환경 구축
 	- 카테고리 도메인
 	- 주문 도메인

 - #### 박진영
 	- 상품 도메인(검색, 상세조회, 필터링)
 	- 리뷰 도메인
 	- 회원 장바구니 도메인

 - #### 박찬웅
 	- 스프링시큐리티 및 JWT 적용
 	- oAuth 및 이메일 인증(Redis 활용)
 	- 회원 도메인(로그인, 회원가입 등)
 	- 회원 좋아요 도메인
<br />

# 8. 구현 기능

<br />

# 9. 트러블 슈팅

<br />

# 10. 개선 목표
- Recoil을 통한 상태관리 및 성능 개선
	- Recoil을 도입하기 전 props depth가 깊어지면서 상태관리의 어려움이 있었고, 전달받은 상위 컴포넌트의 state 변경 시 하위 모든 컴포넌트의 리렌더링을 유발하는 문제가 있음.
	- 장바구니 기능 구현 중 전역 상태관리를 위해 뒤늦게 Recoil을 도입하면서 `상태관리의 중요성`을 느꼈음.
	- 추후 지나친 Prop Drilling이 있는 컴포넌트에 Recoil을 적용하여 상태(atom)를 `구독하는 컴포넌트만 업데이트`함으로써 `불필요한 렌더링을 방지`하여  성능을 개선할 예정.
   
<br />

# 11. 프로젝트 후기

<br />








