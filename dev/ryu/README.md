# 비트코인 상승/하락 시계열 분류 예측

비트코인 네트워크 데이터, 시장 데이터를 이용하여 다음 시점에 등하락을 예측

## 파일 구성

- **EDA.ipynb**: 데이터에 대한 탐색적 데이터 분석(Exploratory Data Analysis, EDA)을 수행하는 노트북 파일입니다. 데이터의 기본 구조를 파악하고, 통계적 분석 및 시각화를 통해 인사이트를 도출합니다.
  
- **rolling+shift_LGBM.ipynb**: 롤링 윈도우와 시프트 기법을 적용한 데이터를 바탕으로 LGBM 모델만을 적용한 노트북 파일입니다.

- **rolling+shift_XGBoost.ipynb**: 롤링 윈도우와 시프트 기법을 적용한 데이터를 바탕으로 XGBoost 모델만을 적용한 노트북 파일입니다.

- **rolling+shift_LGBM+XGBoost.ipynb**: 롤링 윈도우와 시프트 기법을 적용한 데이터를 바탕으로 LGBM과 XGBoost 모델을 앙상블한 모델을 적용한 노트북 파일입니다.
