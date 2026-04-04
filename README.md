# 안녕하세요, 정채강입니다.

LLM 기반 시스템, RAG 파이프라인, 그리고 AI 의사결정 시스템 개발에 관심을 가지고 있습니다.  
현재 **Rice University Biosciences** 전공으로 재학 중이며, AI 시스템과 데이터 기반 문제 해결을 중심으로 프로젝트를 진행하고 있습니다.

---

## 주요 프로젝트

### Invest-RAG
SEC 공시 문서를 기반으로 Retrieval 성능을 평가하고 개선하는 RAG 시스템

- FAISS 기반 벡터 검색 (~4,000 chunks)
- Retrieval 평가 파이프라인 설계 (Recall@k, MRR)
- LLM reranking을 통한 ranking quality 개선

Repo  
https://github.com/CG-Brian/invest-rag


### Self-Correcting Validator
LLM structured output의 신뢰성을 높이기 위한 validation pipeline

- Pydantic schema validation
- rule-based business validation
- error-guided retry loop

Repo  
https://github.com/CG-Brian/self-correcting-validator


### Telecom Ops Decision Agent
통신/렌탈 도메인에서 마케팅, 퍼널, CS 데이터를 통합해 의사결정을 지원하는 AI 에이전트

- Snowflake Cortex Analyst / Complete, Snowpark 기반 멀티 도메인 의사결정 시스템 구현
- CVR + Revenue 기반 rule-based scoring과 LLM synthesis를 결합해 실행 가능한 인사이트 생성
- Top-1 Accuracy, Hallucination Rate, CVR/Revenue uplift 기반 evaluation framework 설계

Repo  
https://github.com/CG-Brian/telecom-ops-agent

---

## 기술 스택

Python  
LLM API  
RAG  
FAISS  
Retrieval Evaluation  
Pydantic  
Snowflake Cortex  
Snowpark  
Streamlit
