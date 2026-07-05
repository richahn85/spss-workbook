---
{"dg-publish":true,"permalink":"//spss30-data-catalog/","title":"SPSS30 Data 카탈로그","tags":["spss","dataset","practice"],"dg-note-properties":{"title":"SPSS30 Data 카탈로그","category":"references","tags":["spss","dataset","practice"],"aliases":["SPSS30 Data","SPSS 실습 데이터"],"relationships":[{"target":"[[references/spss-30-manual]]","type":"related_to"},{"target":"[[projects/spss-practice-workbook]]","type":"related_to"}],"sources":["C:/Users/USER/Documents/Obsidian Vault/SPSS문제집 Wiki/_sources/SPSS 실전 문제집/SPSS30 Data"],"summary":"SPSS 30 매뉴얼 실습용 데이터 폴더의 장별 파일 카탈로그로, 90개 SAV 파일과 SPS, XLSX, TXT 보조 파일을 분석 주제별로 묶는다.","provenance":{"extracted":0.78,"inferred":0.2,"ambiguous":0.02},"base_confidence":0.57,"lifecycle":"draft","lifecycle_changed":"2026-07-04","tier":"supporting","created":"2026-07-04T22:51:31+09:00","updated":"2026-07-04T22:51:31+09:00"}}
---


# SPSS30 Data 카탈로그

`SPSS30 Data` 폴더에는 97개 파일이 있으며, 이 중 90개는 `.sav` 파일이다. 모든 `.sav` 파일은 메타데이터 읽기에 성공했다. 일부 변수명은 원본 SAV의 legacy encoding 영향으로 깨져 보이는 항목이 있다. ^[ambiguous]

## 장별 데이터 묶음

| 장 | 주제 | SAV 파일 수 | 대표 파일 |
|---|---:|---:|---|
| 2 | 데이터 입력과 변수 정의 | 9 | `(2)변수.sav`, `(2)연습문제-xlsx.sav` |
| 3 | 기술통계와 데이터 탐색 | 5 | `(3)데이터 탐색.sav`, `(3)빈도분석-단일응답.sav` |
| 5 | t 검정과 비율 검정 | 8 | `(5)대응T.sav`, `(5)독립두집단평균.sav` |
| 6 | 카이제곱 검정 | 7 | `(6)x2독립성.sav`, `(6)x2적합도.sav` |
| 7 | 분산분석 | 7 | `(7)일원분산분석.sav`, `(7)이원분산분석.sav` |
| 8 | 반복측정과 다원 분산분석 | 6 | `(8)분산-피실험자내.sav`, `(8)삼원분산분석.sav` |
| 9 | 공분산분석과 MANOVA | 5 | `(9)공분산분석.sav`, `(9)다변량분산분석.sav` |
| 10 | 상관분석 | 6 | `(10)상관관계.sav`, `(10)편상관관계.sav` |
| 11 | 회귀분석 | 4 | `(11)다중회귀분석.sav`, `(11)연습문제(직무성적).sav` |
| 12 | 로지스틱 회귀분석 | 3 | `(12)로지스틱.sav`, `(12)연습문제(불면증).sav` |
| 13 | 신뢰도와 요인분석 | 4 | `(13)Cronbach's Alpha.sav`, `(13)요인분석.sav` |
| 14 | 판별분석 | 3 | `(14)판별분석.sav` |
| 15 | 군집분석 | 3 | `(15)군집분석.sav`, `(15)연습문제(시장세분화).sav` |
| 16 | 다차원척도법 | 3 | `(16)다차원척도법.sav` |
| 17 | 컨조인트 분석 | 9 | `(17)컨조인트데이터.sav`, `(17)컨조인트설계.sav` |
| 18 | 비모수 검정 | 8 | `(18)Mann-Whitney(독립 두표본).sav`, `(18)Wilcoxon(대응 두표본).sav` |

## 활용 원칙

- 파일명 앞의 장 번호는 [[references/spss-30-manual\|SPSS 30 매뉴얼]]의 장 구성과 맞물린다.
- 실습 노트를 만들 때는 `데이터 파일 -> 분석 설계 -> SPSS 메뉴 -> 출력표 -> 논문식 해석` 순서로 연결한다.
- 장별 데이터는 [[synthesis/spss-practice-curriculum-map\|SPSS 실습 커리큘럼 지도]]에서 단계형 학습 로드맵으로 재배치할 수 있다. ^[inferred]

## Sources

- `SPSS30 Data/`