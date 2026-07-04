---
title: SPSS ANOVA 실행과 해석
category: skills
tags: [spss, anova, statistics]
aliases: [SPSS 분산분석 실행, 일원분산분석 실행]
relationships:
  - target: "[[spss-anova]]"
    type: uses
  - target: "[[spss-output-interpretation-workflow]]"
    type: related_to
sources:
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS 30 매뉴얼 OCR.pdf"
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/20240826_spss_실전_문제집_최종통합본.pdf"
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS30 Data"
summary: SPSS에서 일원분산분석과 확장 ANOVA를 실행한 뒤 기술통계, 등분산 검정, ANOVA 표, 사후검정을 해석하는 절차이다.
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

# SPSS ANOVA 실행과 해석

ANOVA는 집단이 셋 이상일 때 평균 차이를 검정하는 기본 절차다. SPSS에서는 일원분산분석에서 시작해 이원분산분석, 반복측정, 공분산분석으로 확장된다.

## 일원분산분석 절차

1. 종속변수는 척도형, 요인은 명목형 집단 변수인지 확인한다.
2. `분석 > 평균 비교 > 일원배치 분산분석`을 연다.
3. 종속변수와 요인을 배치한다.
4. 옵션에서 기술통계와 등분산 검정을 선택한다.
5. 사후검정에서 Tukey, Scheffe, Bonferroni 등 연구 상황에 맞는 방법을 선택한다.

## 해석 순서

- 기술통계표로 집단별 평균과 표본 수를 확인한다.
- Levene 검정으로 등분산 가정을 점검한다.
- ANOVA 표의 `F`와 `Sig.`로 전체 평균 차이의 유의성을 판단한다.
- 전체 검정이 유의하면 사후검정 표에서 집단쌍별 차이를 읽는다.

## 실습 연결

[[spss30-data-catalog|SPSS30 Data]] 7장은 일원/이원분산분석, 8장은 반복측정과 삼원분산분석, 9장은 공분산분석과 다변량분산분석 실습으로 이어진다.

## Sources

- [[spss-30-manual]]
- [[spss-practice-nje-workbook-2024]]
- [[spss30-data-catalog]]