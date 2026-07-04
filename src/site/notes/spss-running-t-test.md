---
title: SPSS t 검정 실행과 해석
category: skills
tags: [spss, t-test, statistics]
aliases: [SPSS t-test, 독립표본 t 검정, 대응표본 t 검정]
relationships:
  - target: "[[spss-data-types]]"
    type: uses
  - target: "[[spss-output-interpretation-workflow]]"
    type: related_to
sources:
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS 30 매뉴얼 OCR.pdf"
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/20240826_spss_실전_문제집_최종통합본.pdf"
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS30 Data"
summary: SPSS에서 단일표본, 독립표본, 대응표본 t 검정을 실행하고 Levene 검정, t, df, p값, 평균 차이를 해석하는 절차이다.
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

# SPSS t 검정 실행과 해석

t 검정은 평균 차이를 검정하는 기본 절차다. SPSS에서는 연구 질문의 형태에 따라 단일표본, 독립표본, 대응표본 t 검정을 구분한다.

## 선택 기준

- 단일표본 t 검정: 한 집단의 평균이 기준값과 다른지 본다.
- 독립표본 t 검정: 서로 다른 두 집단의 평균 차이를 본다.
- 대응표본 t 검정: 같은 대상의 사전/사후 또는 짝지어진 두 측정값 차이를 본다.

## SPSS 실행 흐름

1. [[spss-data-types|종속변수와 집단변수의 측정수준]]을 확인한다.
2. `분석 > 평균 비교` 메뉴에서 연구 설계에 맞는 t 검정을 선택한다.
3. 독립표본 t 검정에서는 집단변수를 지정하고 집단값을 정의한다.
4. 결과표에서 기술통계, Levene의 등분산 검정, t 검정 표를 순서대로 읽는다.

## 해석 체크리스트

- Levene 검정이 유의하면 등분산을 가정하지 않는 행을 읽는다.
- `Sig. (2-tailed)`가 기준보다 작으면 평균 차이가 통계적으로 유의하다고 쓴다.
- 평균 차이와 신뢰구간을 함께 보고 실제 차이의 방향을 확인한다.

## Sources

- [[spss-30-manual]]
- [[spss-practice-nje-workbook-2024]]
- [[spss30-data-catalog]]