
## 조별 진행 상황 작성 안내

7월 1일, 7월 8일, 7월 15일 오전 10시까지 각 조의 진행 상황을 아래 링크에 접속하여 작성해 주시기 바랍니다.

### 1조

* https://docs.google.com/spreadsheets/d/1cdyRL0GnKCfhIwgiQ4xBGH8tDIXV0Irf/edit?usp=sharing&ouid=100115907442537167655&rtpof=true&sd=true

### 2조

* https://docs.google.com/spreadsheets/d/1WF5KS5V9aKUSOBe5rn1BY2uIXoqGXH1b/edit?usp=sharing&ouid=100115907442537167655&rtpof=true&sd=true


### 3조

* https://docs.google.com/spreadsheets/d/1kmupwGHZi3mPoEtzOLoTI2hBUWwQoYcU/edit?usp=sharing&ouid=100115907442537167655&rtpof=true&sd=true


---


## 프로젝트 산출물 작성 가이드

프로젝트 최종 결과물은 단순히 소스 코드만 제출하는 것이 아니라, 기획부터 설계, 구현, 배포, 테스트까지의 전 과정을 문서화하여 관리하는 것을 목표로 합니다.

### 1. 프로젝트 개요 및 기획 문서

프로젝트의 목적과 방향성을 설명하는 문서입니다.

* 프로젝트 정의서

  * 프로젝트 목적
  * 해결하려는 문제
  * 주요 기능 소개

* 요구사항 명세서(SRS)

  * 기능 요구사항
  * 비기능 요구사항

    * 성능
    * 보안
    * 응답 속도
    * 확장성

* 서비스 흐름도

  * 사용자 요청부터 결과 반환까지의 전체 서비스 구조
  * React → Spring Boot → LLM → 사용자 응답 흐름 표현
  * 전체 아키텍처 다이어그램 작성



### 2. 기술 스택 및 아키텍처 문서

프로젝트에 사용한 기술과 선정 이유를 설명합니다.

* 기술 스택 선정 이유

  * React 사용 이유
  * Spring Boot 사용 이유
  * 데이터베이스 선정 이유
  * LLM 모델(Qwen 등) 선정 이유

* 데이터베이스 설계

  * ERD(Entity Relationship Diagram)
  * 테이블 구조 설명
  * 주요 관계 정의

* API 명세서

  * Swagger 활용 
  * 요청(Request) 및 응답(Response) 예시 작성
  * 프론트엔드와 백엔드 연동 규격 정의



### 3. AI(LLM) 통합 설계 산출물

AI 기능 구현 과정을 문서화합니다.

* 프롬프트 엔지니어링 전략

  * System Prompt 설계
  * 사용자 입력 처리 방식
  * 답변 품질 향상 방법
  * 언어 및 출력 형식 제어 방법

* 데이터 흐름 문서

  * React → Backend → LLM → Backend → React
  * 시퀀스 다이어그램 작성 권장



### 4. 개발 및 구현 산출물

실제 구현 결과를 정리합니다.

* 핵심 코드 설명

  * 주요 기능 구현 코드
  * AI 연동 코드
  * 인증/인가 처리 코드
  * 데이터 처리 로직

* UI/UX 화면 명세서

  * 화면 설계서
  * React 컴포넌트 구조
  * 주요 페이지 흐름
  * 사용자 인터페이스 설명



### 5. 인프라 및 배포 문서 (AWS)

서비스 운영 환경과 배포 과정을 설명합니다.

* 배포 아키텍처

  * AWS EC2
  * AWS RDS
  * AWS S3
  * Docker
  * Nginx
  * 전체 인프라 구성도

* CI/CD 파이프라인

  * GitHub
  * Jenkins 또는 GitHub Actions
  * Docker Hub
  * AWS EC2
  * 자동 배포 과정 설명

* 트러블슈팅 일지

  * 발생한 문제
  * 원인 분석
  * 해결 과정
  * 개선 사항


### 6. 테스트 및 결과 산출물

프로젝트 검증 결과를 정리합니다.

* 테스트 결과서

  * 단위 테스트(Unit Test)
  * 통합 테스트(Integration Test)
  * 기능 테스트 결과

* 시연 자료

  * 실행 화면 캡처
  * GIF
  * 시연 영상
  * 발표 자료(PPT)



### 권장 사항

* 다이어그램, 이미지, 표 등을 적극 활용합니다.
* 서비스 흐름도, ERD, 시퀀스 다이어그램, 배포 아키텍처 다이어그램을 포함하는 것을 권장합니다.
* 코드뿐만 아니라 설계, 구현, 배포, 테스트 과정 전체를 기록하여 프로젝트 완성도를 높입니다.

---
# 프로젝트 최종 제출 안내

## 프로젝트 발표 일정

- **발표일:** 2026.07.23(목) 오후 3시

---

## 제출 안내

### 제출 파일은 Word로 통합 제출합니다.

단, **시연 영상**과 **발표 자료(PPT)**는 별도 파일로 제출합니다.

### 제출 파일 목록

1. 산출물 작성 파일 (Word)
2. 시연 영상
3. 발표 자료 (PPT)
4. 소스코드

### 제출 방법

위 파일들을 하나의 압축 파일(.zip)로 묶어 제출합니다.

예)

- 1조.zip
- 2조.zip
- 3조.zip

### 제출처

- hiksyksyksy@naver.com

---

## 제출 예시

```text
1조.zip
 ├─ 프로젝트_산출물.docx
 ├─ 발표자료.pptx
 ├─ 시연영상.mp4
 └─ source/
   
