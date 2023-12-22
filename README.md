# 강화학습을 이용한 주식, 가상화폐 트레이딩 프로젝트
강화학습을 주식, 가상화폐 거래에 활용하는 것을 주제로 스터디 형식으로 진행한 팀 프로젝트입니다.  
코드는 기존에 가이드가 나와있던 코드를 참조하였습니다.

참조 코드 : https://pylessons.com/RL-BTC-BOT-backbone  
해당 코드를 사용자들이 사용하려면 각자 로컬 환경에 맞게 변환하는 작업이 필요합니다.  
저희 팀은 해당 코드를 간편하게 어느 환경에서든 실행해 볼 수 있도록, 해당 참조 코드를 Google colab 환경에 클론 코딩 하는 프로젝트를 진행했습니다.  
이것만으로 바로 실제 거래에 사용할 수는 없겠지만 강화 학습, 또는 AI를 활용한 트레이딩에 관심 있는 분들이 보다 쉽게 강화학습의 기본 개념을 이해하고 간편하게 코드를 구동해 볼 수 있도록 하는 것을 목표로 진행했습니다.  

프로젝트 진행기간 : 23.11.15 ~ 23.11.24

------

## 프로젝트 구조
프로젝트는 크게 6단계로 구성되어 있습니다.  
1. 추가 개발, 테스트 및 실험을 수행할 수 있는 맞춤형 거래 환경을 위한 단계별 기반을 작성합니다.
2. 이전 단계에서 작성한 코드를 확장하고 Matplotlib 및 Python을 사용하여 트레이딩 봇과 차트를 시각화합니다.
3. 수익성 있는 거래 전략을 위해 트레이딩 봇을 학습시킵니다.
4. 더 나은 강화학습 보상 전략을 사용하고 Dense, CNN, LSTM 3가지 모델을 각각 적용해 테스트 해봅니다.
5. SMA, Bollinger Bands, Parabolic SAR, MACD, RSI와 같은 다양한 기술적 지표를 적용하여 테스트 합니다.
6. 암호화폐 거래소 API를 사용해 실제 데이터로 트레이딩 봇을 학습시킵니다.

------

## 사용기술 및 환경
Google Colab, Python, TensorFlow  

------

## 테스트  
<a href="https://github.com/yuzy1022/Trading-of-using-reinforcement-learning/blob/main/src/%5BRL%5DTrading_with_RL_forAll.ipynb.zip">[RL]Trading_with_RL_forAll.ipynb.zip</a> 파일을 다운로드 받아 압축을 푼 후, Google Colab (GPU 사용) 혹은 (컴퓨터 자원이 충분하다면) Local PC에서 Jupyter Notebook을 사용해 실행합니다.  
파일은 용량 문제 때문에 압축하여 업로드하였습니다.

------

## 팀원
MicroSoft AI School 3기 9팀 : <a href="https://github.com/ICHBINLUCASKIM">김루카스</a>, 전수형, <a href="https://github.com/yuzy1022">박상원</a>, 임수헌, 송주훈

------

## 결과
<img src="https://github.com/yuzy1022/Trading-of-using-reinforcement-learning/blob/main/Visualization.jpg">
<img src="https://github.com/yuzy1022/Trading-of-using-reinforcement-learning/blob/main/setting.jpg">
강화학습을 1000개의 캔들(약 42일)의 기간동안 암호화폐 거래에 적용했을 때, 1000$ 에서 시작한 잔액이 약 1200$로 증가했습니다.
