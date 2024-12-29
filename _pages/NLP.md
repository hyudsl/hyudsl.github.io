---
layout: interests-post
title: Natural Language Processing
permalink: '/NLP.html'
---
# Data Science Lab's Natural Language Processing (NLP) Research

![Chatbot](./NLP_image.jpg)

## Introduction to NLP
Natural Language Processing (NLP)는 인간의 언어를 이해하고 해석하며, 이를 통해 기계와 더 자연스럽게 소통할 수 있는 기술을 개발하는 학문입니다. 예를 들어, 우리가 사용하는 스마트폰의 Speech Assistant, Machine Translation 시스템, 그리고 Email Spam Filter 모두 NLP 기술에 기반하고 있습니다. 
더 나아가 최근 AI 혁명을 주도하고 있는 ChatGPT와 같은 LLM 기술도 자연어처리의 한 분야입니다.
데이터 사이언스 연구실에서는 이러한 기술을 더욱 발전시키기 위해 흥미로운 연구를 진행하고 있습니다.
**대표적인 자연어처리 연구 주제**
- Sentiment Analysis: 소셜 미디어나 리뷰에서 사용자 의견을 분석하여 감정을 파악합니다.
- Machine Translation: 서로 다른 언어를 실시간으로 번역하여 글로벌 소통을 돕습니다.
- Information Retrieval: 필요한 정보를 대규모 데이터에서 빠르게 찾아냅니다.
- Question Answering Systems: 질문에 대한 정확한 답변을 자동으로 제공합니다.
- Named Entity Recognition (NER): 텍스트에서 이름, 날짜, 장소와 같은 중요한 정보를 추출합니다.

다음은 연구실에서 진행한 자연어처리 연구의 구체적인 내용입니다.

## Improving Domain-Specific Language Models
도메인 특화 언어 모델은 전문 분야의 텍스트를 정확히 이해하고 분석하는 데 필수적입니다. 금융, 법률, 특허, 의료 등 다양한 도메인의 텍스트 데이터를 이용하여 연구를 진행합니다. 연구실은 특히 금융 도메인에 특화된 인공지능 연구를 진행하고 있습니다. 

**Financial domain specific**
그 결과 금융 데이터에 특화된 사전 학습 모델 FiLM을 개발하여 공개하였으며, 이번 연구를 통해 금융 데이터의 다양성이 모델 성능에 미치는 영향을 연구하여 금융 문서 분석의 효율성을 높였습니다.
* Jaeyoung Choe, Keonwoong Noh, Nayeon Kim, Seyun Ahn, Woohwan Jung, "Exploring the Impact of Corpus Diversity on Financial Pretrained Language Models" ([EMNLP 2024 findings](https://aclanthology.org/2023.findings-emnlp.138/))
* 김지훈, 정우환, "대화형 금융정보 검색을 위한 의도 분류", 한국소프트웨어종합학술대회 (KSC2023), 2023

**Numeric Hallucination**
경제 문서에서 발생하는 숫자 환각 현상을 탐지하고 해결하는 기술을 연구하고 있습니다. 이를 통해 경제 데이터 분석의 신뢰도와 정확성을 높이는 데 기여하고 있습니다.
* 김지안, 김나연, 정우환, "경제 문서에서의 숫자 환각(Hallucination) 현상 완화를 위한 숫자 매칭", 한국소프트웨어종합학술대회 (KSC2023), 2023
* 김지안, 정우환, "LLM 생성 경제 텍스트의 수치형 할루시네이션 탐지", 한국컴퓨터종합학술대회 (KCC2024), 2024

**Patent Text Generation**
한국어 특허 문서 생성을 위한 특화 언어 모델(KorPatBART)을 개발했습니다. 이를 통해 특허 텍스트 작성 과정을 자동화하여 연구자와 발명가들이 아이디어를 더 효율적으로 특허화할 수 있게 되었습니다.
* 김나연, 김지안, 유장현, 최민영, 정우환, "KorPatBART: 특허 문서 텍스트 생성을 위한 한국어 특허 도메인 사전학습 BART 모델", 한국소프트웨어종합학술대회 (KSC2023), 2023

## Advanced Named Entity Recognition (NER)
NER은 텍스트에서 이름, 장소, 날짜와 같은 주요 개체를 식별하는 기술입니다. 연구실은 저자원 데이터 환경에서도 효과적인 세분화된 NER 방법론을 개발했습니다. Teacher-Student 모델 기반의 강력한 분류기를 설계하여 정확도를 높였으며, 이 접근법은 의료·법률 문서와 같은 전문 분야에도 적용할 수 있습니다.
* Su Ah Lee, Seokjin Oh, Woohwan Jung, "Enhancing Low-Resource Fine-Grained Named Entity Recognition by Leveraging Coarse-Grained Datasets" ([EMNLP 2023]https://aclanthology.org/2023.emnlp-main.197/)
* Seongwoon Oh, Woohwan Jung, and Kyuseok Shim, "THUNDER: Named Entity Recognition using a Teacher-student Model with Dual Classifiers for Strong and Weak Supervisions” ([ECAI 2023](https://ebooks.iospress.nl/doi/10.3233/FAIA230466))

## Enhancing Machine Translation
서로 다른 언어 간의 실시간 소통을 실현하는 기계 번역은 글로벌 사회의 핵심 기술입니다. 연구실은 프롬프트 기반 번역 데이터 증강(Prompt-Based Translation Data Augmentation) 기법을 개발하여 기존 번역 모델의 한계를 극복하고 번역 품질을 크게 향상시켰습니다. 특히 데이터가 부족한 환경에서도 우수한 성능을 유지하는 기술을 연구하고 있습니다.
최근 LLM은 기존 번역품질을 월등히 뛰어 넘는 성능을 보이고 있기 때문에 이를 제대로 평가하기 위한 평가 방법을 제안하였습니다.
* Keonwoong Noh, Seokjin Oh, Woohwan Jung, "Beyond Reference: Evaluating High Quality Translations Better than Human References", ([EMNLP 2024](https://aclanthology.org/2024.emnlp-main.294/))
* 오석진, 이수아, 정우환, "자연어 생성 모델을 통한 프롬프트 기반 번역 벙렬 데이터 증강", 한국컴퓨터종합학술대회 (KCC2023), 2023

## Join Us
데이터 사이언스 연구실은 AI와 NLP 분야의 최첨단 기술로 실제 문제를 해결하고자 하는 열정적인 연구자를 찾고 있습니다. 관심이 있으시다면 [Contact Us](https://dsl.hanyang.ac.kr/contact)를 통해 연락해 주세요.