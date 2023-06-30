# wine_quality_prediction

winequality_white.csv 데이터셋에서 fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density,	pH,	sulphates, alcohol, quality 13개의 변수 중 1-9점으로 주어진 quaility를 예측 하기 위한 MLP 모델을 구축하였습니다. 

각 layer에서 활성화 함수는 ReLU를 마지막 layer에선 Sigmoid를 사용하였으며, optimizer는 adam, 손실함순는 mse로 설정하였습니다.

예측 정확도가 75프로 정도 였으며, 예측 정확도를 시각적으로 확인하기 위해 seaborn을 활용하여 행렬식을 시각화였습니다. 

![image](https://github.com/Shoon9/wine_quality_prediction/assets/120291668/84042916-9487-47cb-a209-6d88dee5aced)
