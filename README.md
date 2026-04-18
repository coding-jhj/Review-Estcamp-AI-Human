<div align="center">

<!-- 헤더 배너 -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=6366f1&height=200&section=header&text=AI%20%ED%95%99%EC%8A%B5%20%EA%B5%90%EC%9E%AC&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=coding-jhj%20%EC%99%84%EC%A0%84%ED%8C%90&descAlignY=58&descSize=20&descColor=c7d2fe" alt="header"/>

<br/>

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://github.com/coding-jhj)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://github.com/coding-jhj)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://github.com/coding-jhj)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://github.com/coding-jhj)

<br/>

> **Python 기초부터 Transformer · BERT까지** — 이스트캠프 AI 부트캠프 학습 내용을 직접 정리한 완전판 교재입니다.

<br/>

</div>

---

## 📖 소개

이 레포지토리는 **이스트캠프 AI Human Camp** 수강 중 학습한 내용을 체계적으로 정리한 인터랙티브 HTML 교재입니다.
사이드바 네비게이션으로 챕터를 자유롭게 이동하며 코드 예제·수식·다이어그램을 한 곳에서 확인할 수 있습니다.

<br/>

## 🗺️ 학습 로드맵

```mermaid
flowchart LR
    A[Python 기초] --> B[NumPy\n기초·심화·고급]
    B --> C[통계 기초\n& 선형대수]
    C --> D[데이터 사이언스\nPandas · 시각화]
    D --> E[머신러닝\n분류 · 회귀 · 불균형]
    E --> F[딥러닝 기초\nKeras · TensorFlow]
    F --> G[CNN]
    G --> H[NLP 기초]
    H --> I[Attention\n& 듀얼인코더]
    I --> J[Transformer\n& BERT]

    style A fill:#6366f1,color:#fff,stroke:none
    style B fill:#7c3aed,color:#fff,stroke:none
    style C fill:#7c3aed,color:#fff,stroke:none
    style D fill:#2563eb,color:#fff,stroke:none
    style E fill:#059669,color:#fff,stroke:none
    style F fill:#059669,color:#fff,stroke:none
    style G fill:#d97706,color:#fff,stroke:none
    style H fill:#dc2626,color:#fff,stroke:none
    style I fill:#dc2626,color:#fff,stroke:none
    style J fill:#be185d,color:#fff,stroke:none
```

<br/>

## 📚 목차

| # | 챕터 | 주요 내용 |
|:-:|------|-----------|
| 0 | 🏠 **개요 & 학습 경로** | 전체 커리큘럼 구성 |
| 1 | 🐍 **Python 기초** | 변수 · 조건문 · 함수 · 클래스 · 예외처리 · 정규표현식 |
| 2 | 🔢 **NumPy 기초** | 배열 생성 · dtype · 사칙연산 · 브로드캐스팅 |
| 2b | 🔢 **NumPy 심화** | 인덱싱 · 슬라이싱 · 이미지 처리 · 불린/팬시 인덱싱 |
| 2c | 🔢 **NumPy 고급** | newaxis · ravel/flatten · split · concatenate |
| 3 | 📐 **통계 기초** | 중심경향 · 산포도 · 공분산 · 상관계수 · 선형회귀 |
| 4 | 📐 **선형대수 기초** | 벡터 연산 · 행렬 연산 · 행렬 곱셈 & 전치 |
| 5 | 📊 **데이터 사이언스** | Pandas · 결측치 처리 · 특성 공학 · 시각화 |
| 6 | 🤖 **머신러닝** | 타이타닉 분류 · 자전거 수요 예측 · 신용카드 사기 탐지 · 모델 평가 |
| 7 | 🧠 **딥러닝 기초** | 퍼셉트론 · Keras 신경망 · TensorFlow 텐서 · Optimizer/Loss |
| 8 | 👁 **CNN** | Padding & Stride · MNIST CNN · 전이학습 |
| 9 | 💬 **NLP 기초** | 텍스트 전처리 · Word2Vec & fastText · 한국어 리뷰 분석 |
| 10 | 🔁 **Attention & 듀얼인코더** | Attention 메커니즘 · 듀얼 인코더 실습 |
| 11 | ⚡ **Transformer & BERT** | Transformer 구조 · BERT & 파인튜닝 · Vector DB & RAG |

<br/>

## ✨ 주요 특징

- 🧭 **인터랙티브 사이드바** — 챕터/섹션 단위 즉시 이동
- 💻 **코드 하이라이팅** — highlight.js 기반 Python 코드 블록
- 📝 **시각적 노트 유형** — 💡 개념 설명 / ⚠️ 주의사항 / ✅ 핵심 팁
- 📊 **표 & 수식** — 비교표 · 수학적 공식 시각화
- 🃏 **카드 레이아웃** — 그리드 기반 개념 정리

<br/>

## 🚀 사용 방법

```bash
# 1. 레포지토리 클론
git clone https://github.com/coding-jhj/Review-Estcamp-AI-Human.git

# 2. HTML 파일 브라우저로 열기
open AI_학습_교재___coding-jhj_완전판.html
```

> 별도 서버 불필요 — 로컬에서 HTML 파일을 직접 열면 됩니다.

<br/>

## 🛠 사용 기술 스택

<div align="center">

| 분류 | 기술 |
|------|------|
| **언어** | Python 3.x |
| **수치 연산** | NumPy, Pandas |
| **시각화** | Matplotlib, Seaborn |
| **머신러닝** | scikit-learn |
| **딥러닝** | TensorFlow / Keras |
| **NLP** | Word2Vec, fastText, BERT, Hugging Face |
| **문서** | HTML5, highlight.js |

</div>

<br/>

## 📂 파일 구조

```
📦 repo
 ┣ 📄 AI_학습_교재___coding-jhj_완전판.html   ← 메인 교재 (인터랙티브)
 ┗ 📄 README.md
```

<br/>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=6366f1&height=100&section=footer" alt="footer"/>

**📌 이스트캠프 AI Human Camp 4기** | 학습 정리 by [coding-jhj](https://github.com/coding-jhj/Review-Estcamp-AI-Human)

</div>
