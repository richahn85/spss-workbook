---
title: SPSS 자료 형태와 변수 정의
category: concepts
tags: [spss, statistics, data]
aliases: [SPSS 데이터 타입, 측정수준, 변수 정의]
relationships:
  - target: "[[excel-spss-r-statistics-practice-problems]]"
    type: derived_from
  - target: "[[spss30-data-catalog]]"
    type: related_to
sources:
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/2026_Excel_SPSS_R_통계학입문_익힘문제_연습문제.pdf"
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS 30 매뉴얼 OCR.pdf"
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS30 Data"
summary: SPSS 분석 전에 자료의 척도와 변수 역할을 정하는 방법을 정리한 페이지로, 어떤 분석법을 선택할 수 있는지의 출발점이다.
provenance:
  extracted: 0.78
  inferred: 0.22
  ambiguous: 0.0
base_confidence: 0.9
lifecycle: draft
lifecycle_changed: 2026-07-04
tier: supporting
created: 2026-06-28
updated: 2026-07-04T22:51:31+09:00
dg-publish: true
---

# SPSS 자료 형태와 변수 정의

SPSS 실습의 첫 판단은 변수의 측정수준과 분석 역할을 정하는 것이다. 같은 데이터라도 명목형, 순서형, 척도형 중 무엇으로 해석하느냐에 따라 사용할 수 있는 메뉴와 검정법이 달라진다.

## 핵심 구분

- **명목형**: 성별, 집단, 지역, 브랜드처럼 범주의 이름이 의미를 갖는다. 교차분석, 카이제곱 검정, 집단 구분 변수로 자주 쓰인다.
- **순서형**: 만족도, 선호순위처럼 순서는 있지만 간격이 정확히 같다고 보기 어려운 자료다.
- **척도형**: 키, 매출, 점수, 연봉, 시간처럼 평균과 표준편차 계산이 의미 있는 수치형 자료다.

## 변수 역할

- **종속변수**는 설명하거나 예측하려는 결과다.
- **독립변수**는 집단, 조건, 설명 요인, 예측 요인으로 쓰인다.
- **통제변수**는 주 관심 효과를 해석할 때 함께 보정하는 변수다.

## 분석 선택으로 이어지는 규칙

- 집단 변수와 척도형 결과변수가 있으면 [[spss-running-t-test|t 검정]] 또는 [[spss-running-anova|ANOVA]]를 검토한다.
- 두 범주형 변수의 관련성을 보려면 카이제곱 검정과 교차표가 기본이다.
- 여러 척도형 예측변수로 척도형 결과를 설명하려면 [[spss-running-regression|회귀분석]]으로 이동한다.
- 결과가 이분형이면 로지스틱 회귀나 분류 모델을 검토한다. ^[inferred]

## Sources

- [[excel-spss-r-statistics-practice-problems]]
- [[spss-30-manual]]
- [[spss30-data-catalog]]