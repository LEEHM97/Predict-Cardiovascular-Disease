# Predict Cardiovascular Disease


## 1. Project Introduction

**주제: FLASK API, Bootstrap을 활용한 심혈관 질환 예측 서비스**
<br>
<br>
* 서비스 설명: 나의 건강 데이터를 입력하여 심혈관 질환에 걸릴 확률을 계산해준다.<br><br>
* 데이터 설명: Kaggle dataset - Cardiovascular Disease dataset <br> (https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset)


## 2. Flow chart
![image](https://user-images.githubusercontent.com/67961082/178495491-bcb35300-9f43-4329-b5b7-93e583722f22.png)

## 3. Modeling

* Number of layers: 3
  - 1st: 256 nodes, activation-'elu'
  - 2nd: 256 nodes, activation-'elu'
  - 3rd: 1 node, activation-'sigmoid' <br><br>
* Model performance
  - Loss(cross_entropy): 0.5433
  - Test accuract: 0.7332
  
## 4. Demonstration of the project

![image](https://user-images.githubusercontent.com/67961082/178499940-d96480a7-31fd-4473-8e24-0cc04099e032.png)

