# 23W-OSSP

## 주제
텐서플로우를 이용하여 특정 종목의 주가를 추정


## 참고 사이트 및 소스
원본소스: https://github.com/NourozR/Stock-Price-Prediction-LSTM

Dataset: https://www.kaggle.com/datasets/artemburenok/sp-500-stock-prices

시계열 예측: https://www.tensorflow.org/tutorials/structured_data/time_series?hl=ko

Github에서 데이터 가져오기: https://thebook.io/080244/part04/unit17/02/

## 진행 중인 기존 소스와 차별점
1. 기존의 선형 회귀를 로지스틱스 회귀로 변경
2. 기존의 Sequencial 모델을 클래스 모델로 구현
3. Dropout 등 과적합을 예방하는데 도움을 주는 부분을 강구
4. Cross Validation을 통해 적합이 제대로 되는지 확인


## 깃허브 작업 로그
log.txt 참고
