# 데이터 augnmentation 실습 

## ACC 방법과 confusion matrix 방법의 차이를 알고 사용할수 있다 
Q1: Acc 방법과 Confuison matrix 방법의 성능 분석 비교

A2: confusion matrix는 각 클래스 별 정밀도와 재현율을 보여줌을 통해 acc 방법으로 정확성만 나타내는 것에 비해 훨씬더 자세한 정보를 제공할수 있습니다

Q2: 논문 사용시 acc 방법보다 confusion matrix를 사용하는 이유

A2: 각 augmentation 방법이 어떠한 클래스에서 좋은 성능을 보이는지 알고, 분석하여 어떤 클래스에서 오류가 많이 발생하는지, 어떤증강 기법이 특정 클래스의 성능을 향상 시키는지 확인할수 있습니다. 

Q3: 논문 작성시 loss acc를 잘 사용하지 않는 이유 

A3: task 특성, 데이터셋, 연구 목적에 맞는 다양한 평가 지표를 사용하여 모델의 성능을 더 정확하고 포괄적으로 평가 해야 하기 때문에 loss acc 방법만으로는 사용된 기법의 성능 평가에 적합하지 않습니다 


### 참조 
