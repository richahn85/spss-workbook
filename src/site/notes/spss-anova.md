---
title: SPSS 분산분석 ANOVA
category: concepts
tags: [spss, statistics, anova]
aliases: [ANOVA, 일원분산분석, 이원분산분석]
relationships:
  - target: "[[spss-data-types]]"
    type: uses
  - target: "[[spss-running-anova]]"
    type: related_to
sources:
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS 30 매뉴얼 OCR.pdf"
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/20240826_spss_실전_문제집_최종통합본.pdf"
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS30 Data"
summary: ANOVA는 셋 이상 집단의 평균 차이를 검정하는 분석 틀이며, SPSS에서는 일원, 이원, 반복측정, 공분산분석으로 확장된다.
provenance:
  extracted: 0.8
  inferred: 0.2
  ambiguous: 0.0
base_confidence: 0.9
lifecycle: draft
lifecycle_changed: 2026-07-04
tier: supporting
created: 2026-06-28
updated: 2026-07-04T22:51:31+09:00
dg-publish: true
---

# SPSS 분산분석 ANOVA

분산분석(ANOVA)은 셋 이상 집단의 평균 차이가 우연한 표본 변동으로 설명될 수 있는지 검정하는 방법이다. SPSS 실습에서는 집단 간 분산과 집단 내 분산의 비율인 F 통계량을 확인하고, 유의하면 어떤 집단 사이가 다른지 사후비교를 확인한다.

## 주요 형태

- **일원분산분석**: 독립변수 1개, 집단 3개 이상, 종속변수는 척도형일 때 쓴다.
- **이원분산분석**: 독립변수 2개의 주효과와 상호작용을 함께 본다.
- **반복측정 ANOVA**: 같은 대상에게 여러 조건이나 시점의 측정값이 있을 때 쓴다.
- **공분산분석 ANCOVA**: 집단 차이를 보되 사전점수 같은 공변량을 통제한다.

## 해석 포인트

- Levene 검정은 등분산 가정을 점검한다.
- ANOVA 표의 `Sig.`가 기준 유의수준보다 작으면 전체 집단 평균이 모두 같다는 영가설을 기각한다.
- 전체 검정이 유의해도 어느 집단끼리 다른지는 사후검정(Tukey, Scheffe, Bonferroni 등)을 별도로 본다.

## 실습 데이터 연결

[[spss30-data-catalog|SPSS30 Data]]의 7-9장 파일은 일원/이원/반복측정/공분산/MANOVA 실습으로 연결된다.

## Sources

- [[spss-30-manual]]
- [[spss-practice-nje-workbook-2024]]
- [[spss30-data-catalog]]