---
title: SPSS 회귀분석 실행과 해석
category: skills
tags: [spss, regression, modeling]
aliases: [SPSS 다중회귀분석 실행, SPSS linear regression]
relationships:
  - target: "[[spss-regression]]"
    type: uses
  - target: "[[spss-output-interpretation-workflow]]"
    type: related_to
sources:
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS 30 매뉴얼 OCR.pdf"
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS, R, Python을 활용한 Kaggle 데이터 전략 실무 연습(OCR).pdf"
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS30 Data"
summary: SPSS 선형회귀에서 모형 요약, ANOVA, 계수표, 다중공선성, 잔차 독립성을 순서대로 읽는 실행 절차이다.
provenance:
  extracted: 0.76
  inferred: 0.24
  ambiguous: 0.0
base_confidence: 0.9
lifecycle: draft
lifecycle_changed: 2026-07-04
tier: supporting
created: 2026-06-28
updated: 2026-07-04T22:51:31+09:00
dg-publish: true
---

# SPSS 회귀분석 실행과 해석

회귀분석은 결과변수의 변화를 하나 이상의 설명변수로 설명하거나 예측하는 절차다. SPSS에서는 `분석 > 회귀분석 > 선형` 메뉴에서 기본 선형회귀를 실행한다.

## 실행 절차

1. 종속변수는 척도형인지 확인한다.
2. 독립변수 후보를 이론과 데이터 구조에 맞게 고른다.
3. `통계량` 옵션에서 추정값, 모형 적합, 공선성 진단, Durbin-Watson을 선택한다.
4. 필요하면 잔차 플롯과 표준화 잔차를 저장해 이상치와 가정 위반을 검토한다. ^[inferred]

## 출력 해석

- **Model Summary**: `R`, `R^2`, 수정 `R^2`, Durbin-Watson을 확인한다.
- **ANOVA**: 회귀모형 전체가 유의한지 확인한다.
- **Coefficients**: `B`, `Beta`, `t`, `Sig.`, VIF를 확인한다.
- **공선성 진단**: VIF가 지나치게 크면 변수 제거, 결합, 이론적 재검토를 고려한다.

## 확장

결과변수가 이분형이면 로지스틱 회귀로 전환한다. 변수 간 경로 자체가 관심이면 [[process-macro-analysis-workflow|PROCESS macro 분석]]이나 AMOS 경로모형으로 확장한다.

## Sources

- [[spss-30-manual]]
- [[kaggle-data-strategy-practice-spss-r-python]]
- [[spss30-data-catalog]]