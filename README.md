# Hello World!
## 🙋‍About Me
### **Contact**
- `Email` js.wise10@kakao.com
- `Github` [https://github.com/jaykingg](https://github.com/jaykingg)

### **Introduction**

- 안녕하세요 ! 3년차 백엔드 개발자 모준서입니다.
- “선한 영향력과 함께, 어제보다 더 나은 삶을 만드는 서비스를 만들자” 라는 모토를 가지고 개발을 하고 있습니다.
- 커머스, 협업툴 등의 스타트업에서 서비스 개발 및 운영해왔으며 주로 Platform API 와 Testing, BackOffice 를 담당했습니다.
- 결과에 끝나는 것이 아니라 Clean Code, Convention 적립에 대한 고민을 즐겨합니다.
- 겸손이 가장 중요한 덕목이라 생각합니다.

## 💻Skills

### BackEnd
- Kotlin, Java
- SpringBoot, Spring Webflux, Spring MVC, Spring Data JPA
- Koest, Mockito
- Gradle

### DevOps
- AWS
    - EC2, ECS, S3
- Apache Kafka
- Docker
- MongoDB, Postgres, Redis
- Nginx

### Tools
- Intellij
- Slack
- Git, Github

## 🔆 Work Experience

### 하비풀
2022.06 - 2023.02
백엔드 개발자
*Series A 투자유치 실패로 개발팀 해체*
*MAU 15만, 일일 평균 주문 수 2000건의 취미플랫폼*<br/>
- 서비스 런칭
    - 초기 Monolithic 구조에서 MSA 로 변경 및 개발
    - Apache Kafka / Mongo kafka Connect 를 사용한 CDC 처리
        - Spring Boot 2.X 에서 Connect 가 비주기적으로 떨어지는 현상 개선
            - Spring Data Stream 이 대부분 동기로 구성되었으나 Boot 3.0 부터 Reactive 를 지원하게되어 3.0으로 Version Up 하여 개선
    - 주문 서비스 개발
        - 도메인 설계 및 주문결제/취소/조회 등 서비스 개발
        - PG사 결제모듈 및 웹훅서비스 연동
            - PG사 웹훅서비스 Response 버그 리포팅
    - 장바구니 서비스 개발
        - 도메인 설계 및 상품담기/삭제/조회 등 서비스 개발

- 데이터 동기화 서비스 개발
    - 운영팀에서 관리하는 Notion 데이터를 자사서비스 데이터로 이관하는 동기화 서비스 개발

- Backoffce 개발
    - 운영팀에서 주문서 관리 및 주문에 대한 관리를 할 수 있는 Backoffice 서비스 개발

- Github Action을 사용하여 CI/CD  적용 및 배포 자동화

- 통합테스트 작성 및 환경세팅
    - Kotest 기반, Behavior Spec을 사용
    - 개발된 모든 Endpoint 에 대한 Integration Test

### 플로우
2020.08 - 2022.06
엔터프라이즈 개발자
[https://flow.team/](https://flow.team/)
*클라우드 및 JTBC, KT, POSCO, SAMSUNG, BGF, 캐피탈 등 구축형 협업툴 서비스*
- Enterprise 서비스 개발
    - Cloud 서비스를 기업형 서비스로 전환 및 기업형 기능 개발
    - 내부망 환경에서의 서비스 구축, 개발 및 운영

- SOLID 를 적용한 레거시 코드 개선
    - 코드 종합 및 중복을 제거
    - `공통` / `기업A, B..` 로 코드 분리 개선
        - 가독성, 디버깅 용이로 생산성 증대
    - Application Property 를 사용하여 필요한 Resource 만 Load 하도록 처리
    - 코드 / 구조 개선 후 사내공유

- 채팅서버 개선
    - 기존 채팅서버는 Node 에서 Socket + 파일업로드 + Database connection 를 모두 처리하고있어 특정시간 대 부하증가
        - Scale Up / Out 보단 분산모델을 선택
        - Batch 서버에 Redis 를 두고 채팅서버는 Batch 서버에 메세지만 전달하고 Socket 을 처리하도록 처리
        - Batch 서버에서 각 프로세스가 메세지를 읽어 Databse Write 처리를 하도록 처리

- VCS 프로세스 적립
    - SVN 에서 Git 으로 전환되면서 Version 관리에 대한 프로세스 적립

### 신원
2018.06 - 2019.06
IT 회계파트 개발자
- 사내/법인 ERP 회계파트 서비스개발 및 운영
    - 현장/매장에서 필요한 기능들을 회계데이터 기반으로 서비스 개발

- VCS 도입
    - 공유드라이브에 코드를 저장하는 형태에서 VCS(Git)를 도입 추진 및 적용

### ✅ Certificate
- 정보처리기사
### ❕ ETC.
- 2018.01 해커톤 아이디어 투표율 1위
- 2016.11 ICT 학술대회 논문게재
- 2015.11 공대 프로그래밍 대회 동상
- 2015.11 한이음 BIG 프로젝트 전시상