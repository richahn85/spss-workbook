---
title: SPSS 회귀분석과 예측 모델링
category: concepts
tags: [spss, regression, modeling]
aliases: [SPSS regression, 다중회귀분석, 로지스틱 회귀분석]
relationships:
  - target: "[[spss-data-types]]"
    type: uses
  - target: "[[mediation-moderation-and-conditional-process]]"
    type: related_to
sources:
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS 30 매뉴얼 OCR.pdf"
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS, R, Python을 활용한 Kaggle 데이터 전략 실무 연습(OCR).pdf"
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS30 Data"
summary: SPSS 회귀분석은 연속형 결과를 설명하는 선형회귀에서 이분형 결과를 예측하는 로지스틱 회귀와 Kaggle식 분류/예측 모델링으로 확장된다.
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

# SPSS 회귀분석과 예측 모델링

회귀분석은 독립변수가 종속변수를 얼마나 설명하는지, 어떤 방향으로 영향을 주는지, 예측에 쓸 수 있는지를 평가하는 분석 틀이다. SPSS 매뉴얼과 Kaggle 실무 자료를 함께 보면 회귀분석은 논문식 설명 모델과 비즈니스 예측 모델의 연결점으로 쓰인다.

## 선형회귀

선형회귀는 척도형 종속변수와 하나 이상의 설명변수 사이의 관계를 모델링한다. SPSS 출력에서는 모형 요약, ANOVA, 계수표를 순서대로 확인한다.

- `R^2`와 수정 `R^2`: 설명력
- ANOVA의 `Sig.`: 모형 전체의 유의성
- 계수표의 `B`, `Beta`, `t`, `Sig.`: 개별 변수의 방향과 유의성
- VIF와 공차한계: 다중공선성 점검
- Durbin-Watson: 잔차 독립성 점검

## 로지스틱 회귀와 분류

종속변수가 이탈/비이탈, 성공/실패처럼 이분형이면 로지스틱 회귀가 더 적절하다. Kaggle 실무 자료는 로지스틱 회귀를 의사결정나무, 신경망과 비교해 예측 모델 후보 중 하나로 다룬다.

## 확장

[[mediation-moderation-and-conditional-process|매개효과와 조절효과]]는 회귀분석을 기반으로 변수 간 경로와 조건부 효과를 해석하는 확장 주제다.

## Sources

- [[spss-30-manual]]
- [[kaggle-data-strategy-practice-spss-r-python]]
- [[spss30-data-catalog]]