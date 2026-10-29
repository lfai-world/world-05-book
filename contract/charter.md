# Agent Charter — LFAI WORLD 공장 (제품 정의서 · 1장)

| 항목 | 내용 |
|---|---|
| Goal | 주인이 AI와 나눈 대화를, 사람이 승인한 것만 웹 책 · 카드 · 낭독 · 영상 · 교재 · 공유 문구로 출판한다 |
| Non-goals | 주인 목소리(RVC) · 주인 얼굴 영상 · GPU 학습 · 별도 클라우드 서버 — 상위 티어(플러그 · 온프레미스) 몫 |
| Users | 계정 주인 1명(작가) · 공개 쇼룸 독자 |
| Autonomy | **A2 — 사람 승인 후 행동.** 공개(05)는 관문 04 승인 없이는 일어나지 않는다 |
| Blast radius | `fmea.csv` — 최고 위험 = 개인정보가 공개 쇼룸에 나감(되돌리기 어려움) |
| Data sensitivity | 원본 대화 = 높음(비공개 서랍만) · 편집본 = 승인 후 공개 |
| Tools & permissions | `permissions.yaml` · 플러그 `tool.schema.json` |
| Success metrics | 최종 수율 ≥ 95% · 1차 수율 ≥ 80% · 사이클 타임 ≤ 24시간 · 장당 실제원가 ≤ 표준원가 × 1.2 · 사람 검사 OK 비율 ≥ 90% |
| Failure modes | `error.taxonomy.json` (불량 코드) |
| Human checkpoints | `hitl-map.md` — ① 관문 04 공개 승인 ② 출하 전 품질 검사 |
| Budget | 무료 Actions 2,000분/월(= 약 150장). 넘으면: 공개 05 렌더 · PC 슬롯 · Pro |
| Owner | 계정 주인 (운영 · 설치: LFAI) |
