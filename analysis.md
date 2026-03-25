# QR 결제 데모 앱 개발 — 제안 분석 로그

> 생성일: 2026-03-25
> 공고 URL: https://www.wishket.com/project/153849/

## 1. 공고 파싱 결과

```yaml
job:
  title: "QR 결제 데모 앱 개발"
  category: "개발 > 안드로이드 > 기타"
  budget_range: "4,000,000원 (조율 가능)"
  duration: "30일 (조율 가능)"
  tech_stack: [Flutter/React Native, Firebase]
  description: "정부 정책자금 신청 및 투자 유치 발표용 QR 결제 데모(시연용) 모바일 앱 + 관리자 페이지"
  requirements:
    - "사용자 앱: 간편 로그인, 잔액 조회, 가상 충전, QR 결제 시뮬레이션, 거래 내역"
    - "가맹점 기능: QR 코드 생성, Mock 결제 승인 알림, 매출 내역 조회"
    - "관리자 페이지: 사용자/가맹점/거래 내역 관리"
    - "모든 UI 텍스트 중국어"
    - "Android APK 파일 필수"
    - "실제 결제/알리페이/위챗페이 연동 없음"
  client_questions: []
  deadline: "2026년 04월 03일"
  job_post_url: "https://www.wishket.com/project/153849/"
  urls: []
  images: []
```

## 2. URL/이미지 분석

참고 URL/이미지 없음.

## 3. 실현 가능성 분석 (내부용)

- **프로젝트 유형**: 모바일 앱 (Flutter/RN) → 조건부 가능, 버퍼 +20%
- **기본 공수 (AI 보조 없이)**:
  - 기획/설계: 3 M/D
  - Figma 디자인: 4 M/D
  - FE 개발 (사용자+가맹점): 10.5 M/D
  - BE 개발 (Firebase+관리자): 10 M/D
  - QA/배포: 2.5 M/D
  - 합계: 30 M/D
- **AI 반영 공수 (45-55% 절감)**:
  - 기획: 2 M/D, 디자인: 3.5 M/D, FE: 3.5 M/D, BE+관리자: 4.5 M/D, QA: 1 M/D
  - 소계: 14.5 M/D
- **버퍼 적용** (+20% 모바일): 14.5 × 1.20 = 17.4 M/D
- **달력 일수**: 17.4 × (7/5) = 24.4일 ≈ 25일
- **클라이언트 예상 기간 vs 산정 기간**: 30일 vs 25일
- **판정**: 산정 기간 ≤ 클라이언트 예상 기간 → 클라이언트 기간 그대로 사용

## 4. 포트폴리오 매칭

| 프로젝트 | 기술(40%) | 도메인(30%) | 기능(20%) | 규모(10%) | 총점 |
|---------|----------|-----------|----------|----------|------|
| **Calendar Share** | 40 (Flutter+Firebase+QR) | 20 (B2C 모바일) | 16 (QR 기능) | 8 | **84** |
| **Fortune App** | 40 (Flutter+Firebase) | 15 (B2C 앱) | 12 (간편로그인) | 8 | **75** |
| **DayStarter** | 32 (Flutter+Firebase) | 15 (B2C 앱) | 10 (중국어UI) | 6 | **63** |

### 매칭 근거
1. **Calendar Share**: Flutter + Firebase + QR 코드 생성/스캔 — 동일 기술 조합
2. **Fortune App**: Flutter + Firebase, 3개월 빠른 딜리버리, Clean Architecture
3. **DayStarter**: Flutter 기반, 6개 국어(중국어 포함) 다국어 경험

## 5. 최종 제안 요약

- **지원 금액**: 3,600,000원 (VAT 별도)
- **지원 기간**: 30일
- **핵심 제안 포인트**:
  - Flutter + Firebase 동일 기술 스택 다수 프로젝트 경험
  - QR 코드 생성/스캔 실제 구현 경험 (Calendar Share)
  - 중국어 UI 포함 다국어 앱 출시 경험 (DayStarter)
  - 기획~배포 풀패키지 딜리버리 경험 (Fortune App 3개월)

## 6. 최종 산출물

### 제안서 사이트 URL
https://proposal-router.claude-ai-b27.workers.dev/proposal-qr-payment-demo/

### 지원 금액
3,600,000

### 지원 기간
30일

### 클라이언트 질문 답변
해당 없음

### 지원 내용

안녕하세요, QR 결제 데모 앱 개발 프로젝트에 지원합니다.

본 프로젝트에 대한 상세 제안서(견적서, 공수계산서, PRD, 일정, 포트폴리오)를 별도 페이지로 준비하였습니다. 아래 링크에서 확인해 주시면 감사하겠습니다.
▶ 제안서 상세 페이지: https://proposal-router.claude-ai-b27.workers.dev/proposal-qr-payment-demo/
▶ 위시켓 포트폴리오: https://www.wishket.com/partners/p/blueverse1/

---

<프로젝트 진행 제안>

■ 프로젝트 분석
정부 정책자금 신청 및 투자 유치 발표를 위한 QR 결제 시연용 데모 앱 프로젝트로 이해하였습니다. 실제 결제 연동 없이 중국 관광객 대상 서비스의 핵심 QR 결제 흐름을 시각적으로 시연하는 것이 목표입니다. Flutter + Firebase 기반으로 사용자 앱(소비자), 가맹점 기능, 관리자 페이지를 개발하며, 모든 UI를 중국어로 구현합니다.

■ 작업 일정

[Phase 1: 기획/설계 + UI/UX 디자인] Day 1–8 (8일)
- 요구사항 상세 분석 및 화면 플로우 설계
- Firestore 데이터 모델 및 API 설계
- Figma 기반 UI 디자인 (사용자 앱 12+ 화면, 가맹점, 관리자)

[Phase 2-1: 사용자 앱 개발] Day 9–16 (8일)
- Flutter 프로젝트 세팅 및 Firebase 연동
- 간편 로그인, 잔액 조회, 가상 충전
- QR 코드 스캔 → 결제 시뮬레이션 4단계 플로우
- 거래 내역 조회

[Phase 2-2: 가맹점 + 백엔드 + 관리자] Day 17–24 (8일)
- 가맹점 QR 생성, Mock 결제 승인 알림, 매출 내역
- Firebase Cloud Functions 백엔드 로직
- 관리자 웹 페이지 (사용자/가맹점/거래 관리)

[Phase 3: QA/배포 + 인수] Day 25–30 (6일)
- 전체 시연 시나리오 테스트 및 중국어 UI 검수
- 최종 APK 빌드, 소스 코드 및 문서 이관

■ 마일스톤 및 산출물
- M1 (Day 8): 화면 설계서, Figma 디자인 승인
- M2 (Day 16): 사용자 앱 빌드 — QR 결제 시뮬레이션 동작 확인
- M3 (Day 24): 가맹점 + 관리자 페이지 동작 확인
- M4 (Day 30): 최종 APK + 소스코드 + 문서 인수

■ 미팅 시 협의 필요 사항
- 중국어 번역 진행 방식 (클라이언트 제공 vs 번역 대행 시 별도 비용)
- 가상 충전 금액 단위 및 통화 (위안/원 등)
- 데모 시연 시나리오 상세 (발표 환경, 인터넷 가용 여부 등)
- 관리자 페이지 호스팅 환경 (Firebase Hosting 활용 제안)

---

<유사 프로젝트 진행 경험>

▶ Calendar Share — 소셜 캘린더 앱 (2025)
- 프로젝트 유형: B2C 모바일 앱 (크로스플랫폼)
- 핵심 기능: 소셜 캘린더, QR 코드 생성/스캔, 실시간 메시징, 45+ 화면
- 유사점: Flutter + Firebase + QR 코드 동일 기술 조합. QR 스캔/생성 기능 실제 구현 경험
- 기술 스택: Flutter, Firebase, QR Code, Provider, Supabase

▶ Fortune App — 운세 앱 (2024.07–2024.09, 3개월)
- 프로젝트 유형: B2C 모바일 앱 (iOS + Android)
- 핵심 기능: 사주 분석, Clean Architecture, BLoC, 다국어 지원, 소셜 로그인
- 유사점: Flutter + Firebase 기반 3개월 빠른 딜리버리. 기획~출시 풀패키지 수행 경험
- 기술 스택: Flutter, Firebase, BLoC, Node.js

▶ DayStarter — 게이미피케이션 수면 앱 (2022.06~, 3년 운영)
- 프로젝트 유형: B2C 모바일 앱 (헬스케어)
- 핵심 기능: 48개 화면, 37개 데이터 모델, 6개 언어 스토어 리스팅
- 유사점: 중국어(간체) UI 포함 다국어 앱 실제 스토어 배포 경험
- 기술 스택: Flutter, NestJS, Firebase, PostgreSQL

---

<사용 기술과 툴>

▶ 개발 기술
- 프론트엔드: Flutter (Dart), React, Next.js
- 백엔드: Firebase (Authentication, Firestore, Cloud Functions)
- QR 코드: qr_flutter (생성), mobile_scanner (스캔)
- 상태 관리: BLoC / Provider

▶ 개발 도구 및 인프라
- 버전 관리: GitHub
- CI/CD: GitHub Actions
- 클라우드: Firebase (Hosting, Functions, Firestore)
- 디자인: Figma

▶ 커뮤니케이션
- 일일 진행 공유: Slack 또는 카카오톡
- 주간 미팅: Zoom / Google Meet
- 문서 공유: Notion 또는 Google Docs
- 이슈 트래킹: GitHub Issues

### 관련 포트폴리오 추천
1. **Calendar Share** — Flutter + Firebase + QR 코드 생성/스캔 동일 기술 조합
2. **Fortune App** — Flutter + Firebase 3개월 빠른 딜리버리, 풀패키지 경험
3. **DayStarter** — 중국어 포함 6개 국어 다국어 앱 출시 경험
