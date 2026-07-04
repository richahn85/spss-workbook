---
title: PROCESS macro 분석 워크플로
category: skills
tags: [process, mediation, moderation, spss]
aliases: [PROCESS macro workflow, 매개 조절 분석 절차]
relationships:
  - target: "[[mediation-moderation-and-conditional-process]]"
    type: uses
  - target: "[[spss-regression]]"
    type: extends
sources:
  - "C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS, AMOS, PROCESS macro를 활용한 매개효과, 조절효과 및 조절된 매개효과분석 OCR.pdf"
summary: PROCESS macro로 매개, 조절, 조절된 매개효과를 분석할 때 모형 선택, 변수 지정, 부트스트랩, 조건부 효과 해석을 진행하는 절차이다.
provenance:
  extracted: 0.7
  inferred: 0.3
  ambiguous: 0.0
base_confidence: 0.57
lifecycle: draft
lifecycle_changed: 2026-07-04
tier: supporting
created: 2026-07-04T22:51:31+09:00
updated: 2026-07-04T22:51:31+09:00
dg-publish: true
---

# PROCESS macro 분석 워크플로

PROCESS macro는 SPSS에서 회귀 기반 매개효과, 조절효과, 조절된 매개효과를 실행하기 위한 도구다. 원문 자료는 통계 프로그램 사용법, 분석 결과물, 통계표, 해석 순서로 사례를 제시한다.

## 절차

1. 연구모형을 먼저 그린다: X, Y, M, W의 역할을 분리한다.
2. [[mediation-moderation-and-conditional-process|매개/조절/조절된 매개]] 중 어떤 질문인지 정한다.
3. PROCESS model 번호를 선택한다.
4. SPSS에서 PROCESS 대화상자에 X, Y, M, W, 공변량을 지정한다.
5. 부트스트랩 표본 수와 신뢰구간 옵션을 설정한다.
6. 출력에서 직접효과, 간접효과, 상호작용항, 조건부 효과를 구분해 읽는다.

## 해석 주의

- 간접효과는 p값보다 부트스트랩 신뢰구간이 0을 포함하는지 여부를 중심으로 판단한다. ^[inferred]
- 조절효과는 상호작용항이 유의한지, 조건부 효과가 어느 수준에서 달라지는지 함께 본다.
- 조절된 매개효과는 조건부 간접효과와 index of moderated mediation을 함께 확인한다. ^[inferred]

## Sources

- [[spss-amos-process-mediation-moderation]]