# Machine Learning & Kaggle study

Machine Learning study 공용 저장소입니다
<br><br>
# Since
2022-09-29
<br><br>
# Goal
**Machine Learning 이론을 이해하는 것을 넘어 실제 모델을 구현하고, 좋은 성능을 내는 것에 집중합니다.**
<br><br>
### process
1. 매주 미팅 주관자가 사전에 정해준 문제(Kaggle/Dacon competition)를 가이드라인에 따라 풉니다.
2. competition 점수는 노션에 공유합니다
3. 미팅이 시작되면 주관자는 ML과 관련된 Topic을 공유합니다
4. Topic 공유가 끝나면 차례대로 돌아가면서 코드를 공유하고 생각해볼만한 주제들에 대해 얘기를 나눕니다
5. 다음 주 담당자를 선정하고 마칩니다 
<br><br>
# Schedule
[01주차-09-29] **Data Preprocessing & Basic ML 1** ([서울시 따릉이 예측대회/Dacon](https://dacon.io/competitions/open/235576/data))
- 기온, 풍속, 습도 등의 데이터를 활용해 시간별 따릉이 대여량을 예측하는 regression 문제
- data preprocessing (missing value, feature engineering...)을 적절히 활용

[02주차-10-06] **Data Preprocessing & Basic ML 2** ([Spaceship-titanic/Kaggle](https://www.kaggle.com/competitions/spaceship-titanic))
- space titanic 탑승자 중 transported된 승객을 분류하는 classification 문제
- missing value는 적은 편이나 없지는 않아 적당한 imputing이 필요

[03주차-10-13] **Feature Engineering** ([제주 테크노파크 제주도 도로 교통량 예측/Dacon](https://dacon.io/competitions/official/235985/overview/description))
1. 개요
  - 제주도의 교통 정보로부터 도로 교통량을 예측하는 regression 문제였습니다
  - 다양한 형태의 변수(numericial, categorical, coordinates...)를 적절히 활용해 모델링 할 수 있어야 함

[04주차-10-20] **Binary Classification** ([Catch me if you can/Kaggle](https://www.kaggle.com/competitions/catch-me-if-you-can-intruder-detection-through-webpage-session-tracking2))
1. 개요
  - 각 사이트 접속 시간이 기록되어 있는 세션 데이터가 주어지고, 그 중 사용자가 “Alice”인 세션을 예측하는 binary classification 문제
  - 세션 데이터라는 새로운 형태의 데이터인 만큼 feature engineering이 중요
2. Topic
  - Hashed feature

[05주차-10-27] **Multi-class Classification** ([San Francisco Crime Classification/Kaggle](https://www.kaggle.com/competitions/sf-crime/overview))
1. 개요
  - 샌프란시스코 지역에서 발생한 범죄 데이터로 주어진 시간과 장소에서 발생한 범죄의 종류를 예측하는 multi-class classification 문제
  - 시간정보, 공간정보를 모두 활용 할 수 있어야 함
2. Topic
  - Interpretable ML (LIME, SHAP)

[06주차-11-03] **Regression** ([Restaurant Revenue Prediction/Kaggle](https://www.kaggle.com/competitions/restaurant-revenue-prediction/data))
1. 개요
  - obfuscated data를 바탕으로 restaurant의 revenue를 예측
  - shake up 이 크게 발생한 대회로 robust한 모델링 필요
2. Topic
  - Bias & variance decomposition
  
[07주차-11-10] **Time series Regression** ([팔당댐 홍수 안전운영에 따른 한강 수위예측 AI 경진대회/Dacon](https://dacon.io/competitions/official/235949/overview/description))
1. 개요
  - 팔당댐 유입량, 저수량, 공용량 등의 데이터를 바탕으로 청담대교, 잠수교, 한강대교, 행주대교의 수위를 예측하는 time series forecating 문제
  - time series 데이터의 특성을 이해하고 적절한 feature engineering이 필요
2. Topic
  - Key concepts of hyperparameter optimization theories and frameworks
