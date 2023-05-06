# <핵심만 요약한 통계와 머신러닝 파이썬 > 정오표
1. pg 26: QM 함수 정의 내 오탈자 'np.sum'을 'np.mean'으로 수정한다.
2. pg 57: "Test F1-score를 기준으로, K-means SMOTE 데이터(0.92)가 다른 데이터들보다 가장 높은 분류 성능을 나타냈다. 이는 오버샘플링 하기 전 원본 데이터(0.91)보다도 더 높은 수치이다. 반면, Borderline SMOTE 데이터(0.80)는 가장 낮은 분류 성능을 나타냈다."로 본문의 내용을 수정한다. 코드 블럭 내 data_title의 내용을 'BorderlineSMOTE'를 추가한 "['no oversampling', 'RandomOverSampler', 'SMOTE', 'BorderlineSMOTE', 'KMeansSMOTE', 'SVMSMOTE', 'ADASYN']"으로 수정한다.
3. pg 60~65: 주석의 'feature 표준화'를 'feature scaling'으로 수정한다. '표준화 전후 데이터 분포 비교 시각화'를 'scaling 전후 데이터 분포 비교 시각화'로 수정한다. 
4. pg 68: 주석의 'np.log1m(y)를 통해 원래대로 되돌릴 수 있다'를 'np.expm1()'으로 수정한다. 
5. pg 117~118: 코드 상의 "표본 크기"를 "표본 규모로 수정한다.
