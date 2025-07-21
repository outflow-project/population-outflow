# 지역 인구 유출 분석 프로젝트

## 프로젝트 개요
공공데이터를 활용하여 지역 인구 유출를 분석하고, 나아가 일자리 유치 전략을 도출하는 데이터 기반 프로젝트입니다.

## 목표
- 인구 유출이 심각한 지역을 데이터 기반으로 식별
- 인구 유출이 시급한 지역을 시각화
- 일자리 유치 전략을 수립

## 사용 기술
- Python, Pandas
- Tableau, Streamlit (시각화, 대시보드)
- QGIS (공간 분석)
- GitHub (협업 관리)
- 공공데이터 포털 등에서 수집한 데이터

## 폴더 구조(예시)
```markdown
population-outflow/
├── data/ # 원본 및 처리된 데이터 저장
│ ├── raw/
│ └── processed/
├── notebooks/ # Jupyter 노트북 분석 파일
├── src/ # Python 스크립트 (전처리, 분석, 시각화)
│ ├── preprocessing/
│ ├── analysis/
│ └── visualization/
├── results/ # 분석 결과물 및 지도
├── docs/ # 발표 자료, 회의록 등 문서
├── README.md
├── requirements.txt
└── .gitignore
```

##  팀원
| 이름       | 역할                |
|------------|---------------------|
| 김종현     | 조장 |
| 오수성     | 디스코드 관리 |
| 강호현     | 코드 관리 |
| 조재홍     | 리서치 |
| 이대현     | 서포터, 일정 관리 |

##  데이터 출처
- [국가통계포털](https://kosis.kr/index/index.do)
- 예정

## 브랜치 전략 요약
- main: 최종 결과물 저장용
- analysis : 기능 통합용 분석 브랜치
- feature/*: 각 작업 단위 브랜치 (예: feature/EDA, feature/데이터수집)
