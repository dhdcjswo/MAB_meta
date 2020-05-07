# MAB_meta

Multi-armed-Bandit(MAB) 을 이용한 다양한 분석적용.



### 1. dynamic pricing

 	1. TS-base basic algorithm 
     - Thompson-sampling을 이용한 기본 알고리즘
     - 가격제시 단계에서는 rule-base 규칙을 사용
 	2. GP-TS
     - Thompson sampling을 사용한 bayesian optimization 

### 2. recommendation

 	1. cluster-based model
     - 클러스터별 개별 모델 및 개별 기록.
     - 클러스터는 임으로 나누었음. 클러스터를 나누는 기준에 대한 방법론은 고려되지 않음
	2. logistic bandit
    - 유저 정보를 이용한 bandit 선택
    - reward는 0,1 binary로 제공

### 3. Dirichlet-Process





## reference

https://github.com/gdmarmerola/interactive-intro-rl

https://netflixtechblog.com/ml-platform-meetup-infra-for-contextual-bandits-and-reinforcement-learning-4a90305948ef