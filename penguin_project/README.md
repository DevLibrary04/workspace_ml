## 프로젝트 개요
"""
Palmer Penguins 데이터셋을 기반으로 3가지 분류 모델(KNN, Logistic Regression, Naive Bayes)의 성능을 비교하는 실습 프로젝트입니다.
"""
- K-최근접 이웃(K-Nearest Neighbors)
- 로지스틱 회귀(Logistic Regression)
- 나이브 베이즈(Gaussian Naive Bayes)

## 주요 기술
- Python, pandas, scikit-learn
- 분류 문제 (Multi-class Classification)
- 정확도(Accuracy) 평가

## 데이터 전처리 요약
- 결측치는 0으로 대체 (`fillna(0)`)
- `species`는 레이블로 사용, `sex`, `island`, `rowid`는 제거
- 수치형 피처만 사용하여 모델 학습

## 실행 방법
1. penguins.csv 파일을 `data/` 폴더에 넣습니다.
2. Jupyter Notebook 또는 Google Colab에서 `penguin_classification.ipynb` 파일을 실행하세요.

## 과정 및 결과
- 어떻게 했는가?
→ pandas로 전처리 → train_test_split → fit/predict → accuracy_score로 평가

- 결과는?
→ 로지스틱 회귀가 98% 정확도로 가장 우수

## 모델 성능 비교

| 모델 | 정확도 |
|------|--------|
| KNN | 0.79 |
| Logistic Regression | 0.99 |
| Naive Bayes | 0.95 |

📌 참고 자료
Palmer Penguins dataset
https://github.com/allisonhorst/palmerpenguins

scikit-learn Documentation
https://scikit-learn.org/stable/

🙋‍♀️ 만든 이유
- 머신러닝 분류 모델의 비교 실습
- 전처리, 학습, 평가, 시각화 과정을 직접 구현
- 과제 제출용

🧠 추가 아이디어 (Optional)
- 시각화: confusion matrix, feature importance 그래프
- 모델 튜닝: GridSearchCV, StandardScaler 추가
- 오분류 샘플 분석





---------------------------------------------------
## What? Why? How? Result?

|  항목  |	내용  |
|-------|--------------|
|📂 프로젝트 개요|	무엇을 다루는 프로젝트인지   |
|🎯 목적|	왜 이 프로젝트를 했는지    |
|🛠 사용한 기술|	파이썬, sklearn 등 사용한 도구    |
|⚙️ 실행 방법|	어떻게 실행하는지, 순서     |
|🔍 모델 결과 요약|	어떤 알고리즘 썼고, 결과가 어땠는지 (표 형태 추천)    |
|📌 특징|	전처리 방식, 흥미로운 점 등    |
|📁 폴더 구조|	파일 구성 안내   |
|🔗 참고 자료|	데이터셋, 외부 링크 등    |