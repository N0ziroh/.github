## Welcome to the team 🙌

![logo](https://github.com/user-attachments/assets/5a9915d5-a2aa-4563-8ddf-7d205afae6ab)

- [Docs open issue](https://github.com/N0ziroh/Docs/issues)
- [Front open issue](https://github.com/N0ziroh/FrontEnd/issues)
- [Back open issue](https://github.com/N0ziroh/BackEnd/issues)

<!--
**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
👀 Contribution guidelines - how do team members dive in?
👩‍💻 Useful resources - where do you keep your docs? Is there anything else the team should know?
🍪 Fun facts - what is your team's favorite snack?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

## 목차

- [0. 프로젝트 개요](#0-프로젝트-개요)
- [1. 아키텍쳐](#1-아키택처)
- [2. 기술 스택](#2-기술-스택)
- [3. 개발 진행 방법](#3-개발-진행-방법)
- [4. 요구 사항 정의서](#4-요구-사항-정의서)
- [5. 결제](#5-결제)

## 0. 프로젝트 개요

- Professional Prosecutor Clone Coding
- 프로젝트 기간: 
    - 1차 개발: 2024.9.1.~31.
- 회의: 매주 수요일 19시에 진행

## 1. 아키텍쳐 

<img src="https://github.com/user-attachments/assets/38615b15-8f9a-4ac6-858b-a7d029533182" width="300" height="200"/>

## 2. 기술 스택

- 협업 툴: Slack, Github(Issues)
- 1차 개발: React + Spring Boot + AWS + Github Action
    - AWS: **IAM, Route 53, ACM, ELB(EC2, S3, RDS)**
- 2차 개발(고려 중): 1차 개발 + Docker + Kafka

## 3. 개발 진행 방법

> Step
> 1. AWS 환경 설정 구축
> 2. Server AWS에서 실행
> 3. Client AWS Server에 API 요청
> 4. 배포전 각각 Position에서 단위 테스트 실행
> 
> 개발 전 API 정의서 작성 必

> FrontEnd
> ~~1. 메인 페이지~~
> ~~2. 테스트 페이지 샘플~~
> ~~3. 문의 페이지~~
> 4. 결과 페이지
> 5. SNS 연동
> 6. PG 연동

> BackEnd
> ~~1. API 테스트 -> API문서 작성~~
> ~~2. google 가입~~
> ~~3. AWS 회원 가입~~
> ~~4. AWS인스턴스 띄우기~~
> ~~5. Java AWS에 띄우기~~
> 6. Git Action 구축
> ~~7. Test Code 작성~~
> 8. React aws에 띄우기
> 9. 클라 호스팅
> 10. PG 연동

## 4. 요구 사항 정의서

1차 개발(앞의 숫자는(M/D)
- 3 검사 테스트 기능 리서치 -> @Paransaik 
- 3 호스팅
- 7 통계
- 3 결과 페이지
- 7 외부 SNS 연동
- 2 문의하기
- 2 결제(PG 연동) 리서치 -> @Paransaik 
- 5 테스트 환경 배포

2차 개발
- 다국어
- 결과 페이지 확장(카드 결제, 실시간 계좌 이체, 가상 계좌 추가 )
- 사주/팔자/타로
- API Return 형식 정하기
- 상단/하단 바로 이동 버튼 생성
- 배포 아키텍쳐
- 무중단 배포
- 외부 SNS 연동 보완
- 검사 항목 추가(웩슬러, 니코로직)

3차 개발
- GPT연동
- 법률 자문 서비스

## 5. 결제

- 도메인
- AWS
- Git Action
