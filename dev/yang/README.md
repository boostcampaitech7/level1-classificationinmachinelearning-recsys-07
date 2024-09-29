# README



<br/>

## Libs

python 3.9

```
Boruta==0.4.3
lightgbm==4.5.0
matplotlib==3.7.5
numpy==1.26.4
pandas==2.1.4
scikit-learn==1.5.2
seaborn==0.13.2
torch==2.4.1
torchaudio==2.4.1
torchvision==0.19.1
tqdm==4.66.5
xgboost==2.1.1
```



<br/>

## Done

- 제공받은 Base 코드에서 칼럼을 참고하여 데이터 전처리 진행함(Rolling, Shift 등)
  - data_preprocessing1.ipynb
- LLM(Perplexity)를 이용한 논문(Bi-LSTM) 구현 후 모델 학습 및 테스트
- 결측치가 하나라도 있는 칼럼 제외 후 모델 학습 및 테스트
- 팀원이 선택한 칼럼 이름('buy_volume', 'sell_volume', 'reciver', 'long_liquidations', 'short_liquidations')이 포함되 칼럼 선택 후 XGB 모델 학습 및 테스트
- Pycaret 라이브러리를 이용한 여러 모델 비교
  - 파일명: train_automl.ipynb
- Grid Search를 이용한 파이퍼파라미터 튜닝
  - 파일명: train_xgb2.ipynb



<br/>

## Reference

- A Data-driven Deep Learning Approach for Bitcoin Price Forecasting(https://arxiv.org/abs/2311.06280)

  











