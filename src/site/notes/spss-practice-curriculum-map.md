---
title: SPSS 실습 커리큘럼 지도
category: synthesis
tags: [spss, curriculum, statistics]
aliases: [SPSS 학습 로드맵, SPSS practice curriculum]
relationships:
  - target: "[[spss-practice-workbook]]"
    type: derived_from
  - target: "[[spss30-data-catalog]]"
    type: uses
sources:
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/20240826_spss_실전_문제집_최종통합본.pdf"
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/2026_Excel_SPSS_R_통계학입문_익힘문제_연습문제.pdf"
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS 30 매뉴얼 OCR.pdf"
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS, AMOS, PROCESS macro를 활용한 매개효과, 조절효과 및 조절된 매개효과분석 OCR.pdf"
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS, R, Python을 활용한 Kaggle 데이터 전략 실무 연습(OCR).pdf"
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS30 Data"
summary: SPSS 자료 묶음을 기초 자료 이해, 평균 차이, 관계/예측, 고급 다변량, PROCESS macro, Kaggle 응용 단계로 재배열한 학습 지도이다.
provenance:
  extracted: 0.5
  inferred: 0.5
  ambiguous: 0.0
base_confidence: 0.9
lifecycle: draft
lifecycle_changed: 2026-07-04
tier: core
created: 2026-07-04T22:51:31+09:00
updated: 2026-07-04T22:51:31+09:00
dg-publish: true
---

# SPSS 실습 커리큘럼 지도

이 지도는 여러 PDF와 실습 데이터 폴더를 한 번에 공부하기 위한 순서 제안이다. 원문 자료의 장 순서와 데이터 파일 번호를 따르되, 실제 학습 흐름에 맞게 재배열했다. ^[inferred]

## 1단계 - 자료 이해와 기술통계

- 핵심 페이지: [[spss-data-types]]
- 원문: [[excel-spss-r-statistics-practice-problems]], [[spss-30-manual]]
- 데이터: [[spss30-data-catalog|SPSS30 Data]] 2-3장

목표는 명목형, 순서형, 척도형 자료를 구분하고 빈도표, 기술통계, 그래프로 데이터를 설명하는 것이다.

## 2단계 - 평균 차이와 집단 비교

- 핵심 기술: [[spss-running-t-test]], [[spss-running-anova]]
- 원문: [[spss-practice-nje-workbook-2024]], [[spss-30-manual]]
- 데이터: 5-9장

단일/독립/대응 t 검정에서 시작해 일원, 이원, 반복측정, 공분산분석으로 확장한다.

## 3단계 - 관계와 예측

- 핵심 페이지: [[spss-regression]], [[spss-running-regression]]
- 데이터: 10-12장

상관분석과 편상관으로 관계를 보고, 선형회귀와 로지스틱 회귀로 설명/예측 모델을 만든다.

## 4단계 - 척도, 분류, 군집, 선호 구조

- 원문: [[spss-30-manual]]
- 데이터: 13-18장

신뢰도, 요인분석, 판별분석, 군집분석, 다차원척도법, 컨조인트, 비모수 검정으로 확장한다.

## 5단계 - 논문형 경로모형과 실무 예측

- PROCESS/AMOS: [[mediation-moderation-and-conditional-process]], [[process-macro-analysis-workflow]]
- Kaggle 응용: [[kaggle-data-strategy-practice-spss-r-python]]

논문형 분석은 매개/조절/조건부 간접효과를 다루고, 실무형 분석은 문제 정의, 전처리, 모델 비교, 전략 도출을 강조한다.

## Sources

- [[spss-practice-workbook]]