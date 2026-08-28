# still-young-days-feed

**오늘도청춘(Still Young Days)** 앱이 읽는 공개 데이터 피드입니다.

- 이 저장소의 내용은 [still-young-days-data](https://github.com/JKPark83/still-young-days-data) (private) 파이프라인이 **자동 생성·배포**합니다. 직접 수정하지 마세요.
- 원본: 한국노인인력개발원 새누리 노인일자리 API (data.go.kr 15015153)
- 구조:
  - `jobs/{시군구코드}.json` — 시군구별 일자리 목록 (schemaVersion 1)
  - `index.json` — 수집 메타데이터 (generatedAt, 건수 등)
- 앱 접근 URL (`FEED_BASE_URL`): `https://jkpark83.github.io/still-young-days-feed/`
