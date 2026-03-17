# 안녕하세요, 정채강입니다.

LLM 기반 시스템, RAG 파이프라인, 그리고 AI workflow automation에 관심을 가지고 개발하고 있습니다.  
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


### Gmail Cleanup Copilot
Gmail 데이터를 분석해 inbox clutter를 탐지하는 이메일 정리 시스템

- Gmail API 기반 sender-level 분석
- cleanup candidate 탐지 로직
- n8n automation 기반 월간 정리 리포트 생성

Repo  
https://github.com/CG-Brian/gmail-cleanup-copilot

---

## 기술 스택

Python  
LLM API  
RAG  
FAISS  
Retrieval Evaluation  
Pydantic  
Streamlit  
Gmail API  
n8n
