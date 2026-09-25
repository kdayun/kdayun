<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=b591c9&height=250&section=header&text=Hello,%20I%27m%20Dayun!&fontSize=45&fontColor=FFFFFF&animation=fadeIn" />

# Hello, I'm DAYUN 👋

## 👩‍💻 About Me
- 📫 Email: danuy0328@gmail.com

  
## 🛠️ Tech Stack
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

## 🗂️ Experience

| 활동 | 기관 | 기간 | 비고 |
| --- | --- | --- | --- |
| LG CNS AM Inspire Camp | LGCNS | 2025.12 - 2026.06 | 풀스택 수료 |
| KAKAO x 9oormthonUNIV 2기 | 9oorm | 2024.02 - 2024.08 | 프론트엔드 수료 |
| 멋쟁이사자처럼 대학 11기 | LIKELION | 2024.01 - 2024.12 | 프론트엔드 수료 |

## 🏅 Certifications

| 내용 | 주관 | 취득일 |
| --- | --- | --- |
| SQL개발자(SQLD) | 한국데이터산업진흥원 | 2026.09.11 |
| 정보처리기사 | 한국산업인력공단 | 2025.09.12 |

## 💻 Projects

### ErumPay 
**MSA 기반 QR 간편결제 서비스**  
LG CNS AM Inspire Camp 최종 프로젝트 대상

**담당 역할: Payment Core Backend**

- 결제 승인, 성공, 실패, 취소 상태와 카드별 결제·취소 이력 관리
- 멱등성 키와 결제 상태 검증을 적용해 중복 결제 및 잘못된 결제 요청 방지
- 단건·분할 결제 처리와 실패 시 승인 건 취소를 위한 보상 로직 구현
- 카드 추천 서비스 연동 및 Redis 기반 추천 결과 캐싱·검증 구현
- Redis Pub/Sub과 SSE를 활용한 결제 상태 및 카드 추천 결과 실시간 전달
- Kafka를 활용해 결제 완료·취소 알림 이벤트를 발행하는 Producer 구현

`Java` `Spring Boot JPA` `MySQL` `Redis` `OpenFeign` `Kafka` `SSE` `Docker`

[Repository](https://github.com/ErumPay/payment-service/tree/develop/src/main/java/com/erumpay/payment/core)


