---
layout: archive
permalink: /research/
author_profile: true
redirect_from:
  - /research
---

{% include base_path %}

M3 (Multimodal to Multimodal with external Memory)
======
M3를 사용하여 다음과 같은 주제를 연구한다.
- 생성기 개선 연구: 문장 생성 능력을 개선한다. 또한 원하는 형식의 문장을 생성하기 위한 연구를 진행한다.
- 검색기 개선 연구: 유사도 기반 검색, 단계별 추론 등의 연구를 진행한다.
- 입력, 출력, 외부 메모리 표현법 연구: 텍스트와 함께 이미지 등 다른 모달을 함께 사용할 수 있는 방법 연구
- 학습방법 연구: 증강 언어모델(Augmented Language Model)에 적합한 학습 방법 연구

M3를 기반으로 하는 프로젝트
- Controllable Text Generation: 
- KB based Task Oriented Dialogue
- Combined Resolution of Ellipses and Anaphora in Dialogues
- Dense Retrieval for QA
- Visual Language Model



NLTKo(NLTK with Korean language features)
======
- NLTKo는 기존의 NLTK에 한국어 처리를 위한 함수들과 추가적인 기능들을 확장한 도구이다. 확장된 기능은 다음과 같다.
- 한국어 토크나이저
- 한국어 전처리 (자소분리, 자소결합, 문자판별 등)
- 한국어 분석기 (품사태거, 의존구문분석기, 개체명분석기, 한국어WSD)
- 번역기능 (한국어: 영어)
- 한국어 세종 시소러스 검색 (영어 Wordnet 대체)
- 각종 평가 방법 (BLEU, ROUGE, F1, MAUVE, BERT Score 등)
- 정렬 방법 (Needleman-Wunsch 알고리즘, Hirschberg 알고리즘 등)
- 거리 계산 방법 (Levenshtein Edit Distance, Wasserstein Distance 등)
- 검색 방법 (Faiss-Semantic 검색 등)