# 어제보다 더 나은 86,400초를 위해

### Contact.

Email. js.wise10@kakao.com

### Channel.
Notion. [Notion Resume](https://jaykingg.notion.site/jaykingg/86-400-30c93bcf93f84668a11a875d0c701215)   
GitHub. [https://github.com/jaykingg](https://github.com/jaykingg)

---

# Introduce.

### 주니어 백엔드 개발자

안녕하세요 ! 3년차 백엔드 개발자 모준서입니다.
“선한 영향력과 함께, 어제보다 더 나은 삶을 만드는 서비스를 만들자” 라는 모토를 가지고 개발을 하고 있습니다.
커머스, 협업툴 스타트업에서 서비스 런칭 및 운영한 경험이 있으며 주로 Service Platform API 와 Kotest를 이용한 Testing, BackOffice 를 개발했습니다. 결과에 끝나는 것이 아니라 Clean Code, Convention 적립에 대한 고민을 즐겨합니다. 현재 더 높은 생산성과 협업을 위한 코드 및 프로세스의 적립과 더불어 제가 경험했던(MAU15만) 트래픽이상의 대용량트래픽처리에 대해 관심이 많습니다.

### 더 넓게 높이 볼 수 있는

어제보다 나은 삶을 만드는 것이 비즈니스이고 그에 기여하여 선을 이루는 것이 개발자라고 생각합니다. 그렇기 때문에 업무를 단순 개발적 시야로만 보는 것이 아니라 비즈니스적 시야로도 바라보아야합니다. 한 가지 경험으로. 기업에 있어서 비용은 가장 중요한 자원입니다. 서비스 설계 당시서비스를 관리하기 위해 EKS 를 도입하였는데 비용적으로 큰 문제가 있었습니다. 전체적인 서비스 리소스와 컨테이너관리, EKS 의 장점을 대응할 수 있고 저렴한 ECS 를 검토요청하였고 채택되어 10배 이상의 비용을 절감했습니다.

### 함께 신중하고 뜨겁게

신중함과 열정 이 둘이 합쳐질 때 저에게 있어 차별화되는 강점이 된다고 생각합니다. 업무가 주어졌을 때, 물음표를 많이 던지곤합니다. 왜 이 것이 필요하고 어떻게 쓰이고 더 나아가 우리 서비스와 코드, 다른 팀과 업무에 어떤 영향을 줄 수 있는지 신중하게 고민하며 항상 팀원들과 의견을 교환합니다. 다소 느리게 보일 수는 있지만, 확실한 방향을 가지고 효율적으로 기간 내 업무를 완료하여 모두가 만족했을 때 말로 이룰 수 없는 희열을 뿐더러 공동의 목표를 달성하는데 중요한 부분이라고 생각합니다.

### 항상 겸손하게

“불치하문: 배움에는 위아래가 없다.” 개발을 해오면서 마음에 품고 실천하려고 하는 사자성어입니다. 저의 부족한 부분을 팀원에게 도움을 받을 수 있고, 제가 팀원의 부족한 부분을 채워주며 시너지를 발휘하는 것이 팀이 아닐까 싶습니다. 이상적인 팀워크를 위한 근간이 바로 열린 자세로 배움에 임하는 것, 겸손이라 생각합니다.

---

# Work Experience.

# Hobbyful

2022.06 - 2023.02 백엔드개발
MAU 15만, 일일 평균 주문 수 2000건의 취미플랫폼
Series A 투자유치 실패로 개발팀 해체

### Hobbyful Version2 서비스 런칭

- 초기 Monolithic 구조에서 MSA 로 변경 및 개발
- Apache Kafka / Mongo kafka Connect 를 사용한 CDC 처리
    - Spring Boot 2.X 에서 Connect 가 비주기적으로 떨어지는 현상 개선
    - Spring Data Stream 이 대부분 동기로 구성되었으나 Boot 3.0 부터 Reactive 를 지원하게되어
      3.0으로 Version Up 하여 개선
- 주문 서비스 개발
    - 도메인 설계 및 주문결제 / 취소 / 조회 등 서비스 개발
    - PG사 결제모듈 및 웹훅서비스 연동
- 장바구니 서비스 개발
    - 도메인 설계 및 상품담기 / 삭제 / 조회 등 서비스 개발

### 데이터 동기화 서비스 개발

- 운영팀에서 관리하는 Notion 데이터를 자사서비스 데이터로 이관하는 동기화 서비스 개발
- MongoDB search Aggregation 을 활용하여 검색기능 개발

### Backoffice 개발

- 운영팀에서 관리하는 Notion 데이터를 자사서비스 데이터로 이관하는 동기화 서비스 개발

### Github Action을 사용하여 CI/CD  적용 및 배포 자동화

- Github 에서 제공하는 workflow 를 사용하여 배포 자동화 구성

### 통합테스트 작성 및 환경세팅

- Kotest 기반, Behavior Spec을 사용
- 개발된 모든 Endpoint 에 대한 Integration Test

---

# 플로우

2020.08 - 2022.06 엔터프라이즈 개발
클라우드 및 JTBC, KT, POSCO, SAMSUNG, BGF, 캐피탈 등 구축형 협업툴 서비스

### Enterprise 서비스 개발

- Cloud 서비스를 기업형 서비스로 전환 및 기업형 기능 개발
- 내부망 환경에서의 인프라 구축, 서비스 개발 및 운영

### SOLID 를 적용한 레거시 코드 개선

- 코드 종합 및 중복 제거하여 생산성 개선
    - 공통 / 기업별 코드 분리
    - 가독성, 디버깅 용이로 생산성 증대
- Application Property 를 사용하여 필요한 Resource 만 Load 하도록 처리
- 코드 / 구조 개선 후 사내공유

### 채팅서버 개선

- 기존 채팅서버는 Node 에서 Socket + 파일업로드 + Database connection 를 모두 처리하고있어 특정시간 대 부하증가
    - Scale Up / Out 보단 분산모델을 선택
    - Batch 서버에 Redis 를 두고 채팅서버는 Batch 서버에 메세지만 전달하고 Socket 을 처리하도록 처리
    - Batch 서버에서 각 프로세스가 메세지를 읽어 Databse Write 처리를 하도록하여 개선

### VCS 프로세스 적립

- SVN 에서 Git 으로 전환되면서 Version 관리에 대한 프로세스 적립

---

# (주)신원

2018.06 - 2019.06 IT회계파트 개발
의류브랜드

### 사내/법인 ERP 회계파트 서비스개발 및 운영

- 현장/매장에서 필요한 기능들을 회계데이터 기반으로 서비스 개발

### VCS 도입

- 공유드라이브에 코드를 저장하는 형태에서 VCS(Git)를 도입 추진 및 적용

---

# Skill.

---

### Back-End

- Kotlin, Java
- SpringBoot, Spring Webflux, Spring MVC, Spring Data JPA
- Kotest
- Gradle

### DevOps

- AWS
    - EC2, ECS, MSK, S3
- Apache Kafka
- Docker
- MongoDB, Postgres, Redis
- Nginx

### Tools

- Intellij
- Slack
- Git, Github

---

# Certification.

- 정보처리기사

# ETC.

- 2018.01 해커톤 아이디어 투표율 1위
- 2016.11 ICT 학술대회 논문게재
- 2015.11 공대 프로그래밍 대회 동상
- 2015.11 한이음 BIG 프로젝트 전시상

---