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

(8단계 완료 후 추가 예정)
