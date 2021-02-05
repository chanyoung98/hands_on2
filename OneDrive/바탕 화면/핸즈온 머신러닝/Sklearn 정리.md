출처 : [사이킷런 scikit-learn 제대로 시작하기]([(10) 사이킷런 scikit-learn 제대로 시작하기 - YouTube](https://www.youtube.com/watch?v=eVxGhCRN-xA))

# Sklearn

### scikit-learn 특징

- 다양한 머신러닝 알고리즘을 구현한 파이썬 라이브러리
- 심플하고 일관성 있는 API, 유용한 온라인 문서, 풍부한 예제

 ```python
sklearn.datasets   #내장된 예제 데이터 세트
sklearn.preprocessign   #다양한 데이터 전처리 기능 제공(변환, 정규화,스케일링 등)
sklearn.feature_selection  #특징(feature)을 선택할 수 있는 기능 제공
sklearn.feature_extraction  #특징(feature) 추출에 사용
sklearn.decomposition  #차원 축소 관련 알고리즘 지원(PCA, NMF, Truncated SVD 등)
sklearn.model_selection  #교차 검증을 위해 데이터를 학습/테스트용으로 분리, 최적 파라미터를 추출하는 API 제공(GridSearch 등)
sklearn.metrics  #분류, 회귀, 클러스터링, Pairwise에 대한 다양한 성능 측정 방법 제공 (Accuracy, Precision, Recall, ROC-AUC, RMSE 등)
sklearn.pipeline  #특징 처리 등의 변환과 ML 알고리즘 학습, 예측 등을 묶어서 실행할 수 있는 유틸리티 제공
sklearn.linear_model  #선형 회귀, 릿지(Ridge), 라쏘(Lasso), 로지스틱 회귀 등 회귀 관련 알고리즘과 SGd(Stochastic Gradient Descent) 알고리즘 제공
sklearn.svm  #서포트 벡터 머신 알고리즘 제공
sklearn.neighbors  #최근접 이웃 알고리즘 제공(k-NN 등)
sklearn.naive_bayes  #나이브 베이즈 알고리즘 제공(가우시안 NB, 다항 분포 NB 등)
sklearn.tree  #의사 결정 트리 알고리즘 제공
sklearn.ensemble  #앙상블 알고리즘 제공 (Random Forest, AdaBoost, GradientBoost 등)
sklearn.cluster  #비지도 클러스터링 알고리즘 제공(k-Means, 계층형클러스터링, DBSCAN 등)
 ```

### estimator API

- 일관성 : 모든 객체는 일관된 문서를 갖춘 제한된 메서드 집합에서 비롯된 공통 인터페이스 공유
- 

