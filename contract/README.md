# contract/ — 이 공장의 계약 묶음 (SI Contract Pack × 팹 공정 사양서)
설치기가 깔고, 러너(fab.py)가 매 회전 이 기준으로 검사 · 원가 계산 · 성적서를 만든다. 계약은 고정(폭포수), 실행은 루프.

| 파일 | SI 계약 | 팹 문서 |
|---|---|---|
| charter.md | Agent Charter | 제품 정의서 |
| fmea.csv | Blast Radius Map | FMEA (RPN = 심각도 × 발생도 × 검출도) |
| output.schema.json | output.schema | 제품 스펙 시트 |
| error.taxonomy.json | error.taxonomy | 불량 코드표 |
| guardrails.yaml | guardrails | 인터락 |
| permissions.yaml | permissions | 클린룸 출입표 |
| tool.schema.json | tool.schema | 장비 인터페이스(플러그) |
| data.contract.json | data.contract | LOT 트래블러 |
| hitl-map.md | HITL Map | 품질 홀드 지점 |
| eval.cases.jsonl | eval.cases | 골든셋 — 사람 검사 판정이 쌓인다 |
| agent.card.md | Agent Card | 장비 이력 카드 — 러너가 매 회전 다시 씀 |
