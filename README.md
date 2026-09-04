# daily_research_digest

ANNS(근사 최근접 이웃 검색), 벡터 데이터베이스, RAG(검색 증강 생성) 및 관련 분야의 최신 논문, 도구/라이브러리, 벤치마크, 뉴스를 매일 정리하는 리서치 다이제스트 저장소입니다.

## 다루는 주제

- **ANNS (Approximate Nearest Neighbor Search)** — HNSW, DiskANN, IVF, 그래프 기반 인덱스 등
- **벡터 데이터베이스** — Milvus, Qdrant, Weaviate, Pinecone, pgvector, LanceDB 등
- **RAG (Retrieval-Augmented Generation)** — 검색 파이프라인, 청킹, 재순위화(reranking), 에이전틱 RAG 등
- 위 주제와 밀접하게 연관된 기타 정보 검색/임베딩 관련 연구

## 구조

- `digests/YYYY-MM-DD.md` — 날짜별 다이제스트. 각 다이제스트는 다음 카테고리로 구성됩니다.
  - **논문 (Papers)** — 제목, 링크와 함께 핵심 내용을 요약
  - **도구/라이브러리 (Tools/Libraries)** — 신규 릴리스 및 주요 변경 사항
  - **벤치마크 (Benchmarks)** — 성능 비교 및 실험 연구
  - **뉴스 (News)** — 업계 발표, 커뮤니티 화제

## 운영 방식

매일 자동으로 arXiv, 벡터 DB 벤더 블로그/릴리스 노트, GitHub 릴리스, 테크 뉴스(Hacker News 등)를 검색해 최근 24시간 내 발행된 항목을 수집하고 정리합니다. 해당 기간 내 유의미한 신규 발행물이 없을 경우, 그 사실을 다이제스트에 간단히 기록합니다.

모든 문서는 한국어로 작성됩니다.
