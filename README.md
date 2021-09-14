# PVforecast_Quantile

대회링크<br/>
https://dacon.io/competitions/official/235680/overview/description<br/>
<br/>
태양광 발전량 예측 대회입니다.<br/>
과거 7일 데이터를 기반으로 미래의 2일에 대한 발전량 예측을 목표로 모델링 했으며<br/>
외부 데이터 사용이 불가함에 따라 (과거 기상 데이터) + (과거 발전량) -> (미래 발전량) 형태의<br/>
데이터 input 과 target을 구성하여 참가하였습니다.<br/>
<br/>
feature engineering을 다양하게 시도했고<br/>
모델 fine tuning에는 시간을 투자하지 못해 부족함이 많지만<br/>
LGBM, RandomForest, MLP, CNN, LSTM, CNN-LSTM 을 stacking ensemble 하여<br/>
최종 예측을 산출했습니다.<br/>
