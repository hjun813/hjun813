# 👋 안녕하세요, 백엔드 엔지니어 김현준입니다.

비즈니스 가치를 기술로 실현하는 백엔드 엔지니어를 목표로 성장하고 있습니다.  
맹목적인 기술 도입보다는 서비스가 직면한 한계와 자원을 객관적으로 분석하고,  
논리적인 근거를 바탕으로 문제를 해결하는 개발자가 되고자 합니다.

<br/>

## 🧑‍💻 About Me

- 중앙대학교 소프트웨어학부 졸업
- NHN Pebble 플랫폼 백오피스 팀 개발 인턴
- Java / Spring Boot 중심의 백엔드 개발 학습 및 프로젝트 경험
- MSA, Redis, Kafka, AWS, Docker 등을 활용한 서비스 개선 경험
- 기술적 의사결정의 근거를 문서화하고 팀과 공유하는 개발 문화를 지향합니다.

<br/>

## 🛠 Tech Stack

### Language
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/C/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white">

### Backend
<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
<img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white">
<img src="https://img.shields.io/badge/REST API-000000?style=for-the-badge">

### Frontend
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">

### Database / Infra
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
<img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white">
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white">

### Tools
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
<img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black">
<img src="https://img.shields.io/badge/ChatGPT-412991?style=for-the-badge&logo=openai&logoColor=white">
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white">

<br/>

## 💪 Strengths

### 문제를 레이어별로 분해하는 분석력
인프라, DB, 애플리케이션 로직 등 문제의 원인을 레이어별로 분리하여 분석합니다.  
UNBOX 프로젝트에서는 상품 조회 병목을 추적하고, No-Offset 페이지네이션과 Redis 캐싱을 적용하여  
응답 시간을 `8s → 150ms`로 개선했습니다.

### 논리적 근거 중심의 기술 선택
기술을 도입할 때 단순히 최신 기술이기 때문이 아니라,  
서비스의 문제 상황과 비용, 복잡도, 확장성을 함께 고려합니다.  
CQRS, Redis 캐싱, Kafka, MSA 등의 선택 과정에서도 Trade-off를 분석하고 팀과 공유했습니다.

### 배움을 지속하는 개발자
Kafka, Redis, Kubernetes, MSA 등 프로젝트마다 새로운 기술을 직접 도입하고 적용하며 학습했습니다.  
낯선 기술을 단순히 사용하는 것에 그치지 않고, 왜 필요한지와 어떤 문제를 해결하는지 이해하려고 합니다.

<br/>

## 📌 Projects

## 1. UNBOX

> C2C 신발 리셀 플랫폼  
> 구매/판매 입찰, AI 리뷰 요약, 주문 관리, PG 연동 기능을 제공하는 리셀 서비스입니다.

### 프로젝트 정보

| 항목 | 내용 |
|---|---|
| 기간 | 2025.12 ~ 2026.02 |
| 역할 | 5인 팀 프로젝트 / 백엔드 개발 |
| 기술 스택 | Spring Boot, PostgreSQL, AWS, Redis, Kafka, MSA, Kubernetes, Docker |
| GitHub | [UNBOX-BE](https://github.com/team4-coding-gamja/UNBOX-BE) |

### 주요 기여

- 서비스 확장성을 고려한 MSA 전환 및 아키텍처 설계
- 상품 조회 성능 개선을 위한 No-Offset 페이지네이션 적용
- Redis 캐싱을 통한 조회 성능 최적화
- Kafka 기반 이벤트 비동기 처리 구조 설계
- Resilience4j Circuit Breaker를 활용한 장애 전파 차단
- Gemini AI를 활용한 테스트 환경 구축 및 테스트 커버리지 개선

### Trouble Shooting

#### Product 조회 성능 개선

기존 상품 조회 구조에서는 데이터 증가와 Deep Pagination으로 인해 조회 성능 저하가 발생했습니다.  
k6 부하 테스트를 통해 병목을 확인했고, 여러 해결책을 비교했습니다.

처음에는 CQRS 도입도 고려했지만, 문제의 핵심이 단순 읽기 부하와 Deep Pagination에 있다고 판단했습니다.  
따라서 CQRS는 오버엔지니어링이라고 판단하고, Redis 캐싱과 No-Offset 페이지네이션을 적용했습니다.

결과적으로 상품 조회 응답 시간을 다음과 같이 개선했습니다.

```txt
8s → 150ms
약 50배 성능 개선
MSA 전환

인기 상품 발매 상황에서 특정 서비스에 트래픽이 집중될 경우,
모놀리식 구조에서는 전체 시스템 장애로 이어질 가능성이 있다고 판단했습니다.

이를 해결하기 위해 도메인 단위로 서비스를 분리하고,
Kafka를 활용해 결제 완료 후 정산, 재고 반영, 알림 등의 후속 처리를 비동기화했습니다.

또한 OpenFeign과 Circuit Breaker를 활용하여
실시간 검증이 필요한 구간에서는 동기 통신을 유지하되, 장애 전파를 방지할 수 있도록 설계했습니다.

<br/>
2. WAVEFLOW

음악 제작자를 위한 협업 및 파일 버전 관리 플랫폼
음악 파일 업로드, 버전 관리, 협업 흐름을 직관적으로 제공하는 서비스입니다.

프로젝트 정보
항목	내용
기간	2025.06 ~ 2025.07
역할	5인 팀 프로젝트 / 팀장 / 풀스택 개발
기술 스택	React, TypeScript, NestJS, Python, PostgreSQL, AWS EC2, S3, wavesurfer.js, librosa
GitHub	RealWaveFlow
주요 기여
음악 파일 업로드 기능 개발
음악 파일 버전 관리 기능 개발
플랫폼 화면 개발 및 UI/UX 개선
대용량 오디오 파일 업로드 최적화
팀장으로서 기술적 쟁점 정리 및 팀 내 의사결정 주도
Trouble Shooting
음악 파일 업로드 안정성 개선

음악 파일 업로드 과정에서는 메타데이터 추출, 중복 파일 검사, 음악 파일 생성 등
여러 로직이 함께 수행되어야 했습니다.

초기 구조에서는 비동기 처리로 인해 실행 순서가 보장되지 않았고,
그 결과 DB에 NULL 값이 저장되거나 특정 로직이 누락되는 문제가 발생했습니다.

이를 해결하기 위해 데이터 무결성에 중요한 핵심 로직은 동기적으로 처리하도록 구조를 변경했습니다.
그 후 안정성이 확보된 상태에서 멀티파트 업로드와 병렬 업로드를 적용해
대용량 파일 업로드 속도와 사용자 경험을 개선했습니다.

대용량 오디오 파일 업로드 처리 속도
기존 대비 70% 이상 개선
<br/>
📚 Education & Experience
구분	내용
University	중앙대학교 소프트웨어대학 졸업
Internship	NHN Pebble 플랫폼 백오피스 팀 개발 인턴
Education	크래프톤 정글
Education	구름 프로펙트 클라우드 과정
<br/>
📊 GitHub Stats

<br/>
📫 Contact
Email: hyeonjun0899@gmail.com
GitHub: @hyeonjun0899
