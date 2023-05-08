# <핵심만 요약한 통계와 머신러닝 파이썬 > 정오표
1. pg 26: QM 함수 정의 내 오탈자 'np.sum'을 'np.mean'으로 수정한다.
2. pg 44: 세번째 줄에 다음의 보충 설명을 추가한다. "아래의 정상적인 데이터의 범위를 벗어난 데이터 포인트들을 이상치로 본다."
3. pg 52: RandomOverSampler 코드블럭 14행 파라미터로, "style='y', markers=['s', 'X']"를 추가한다. 
4. pg 57~58: "Test F1-score를 기준으로, K-means SMOTE 데이터(0.92)가 다른 데이터들보다 가장 높은 분류 성능을 나타냈다. 이는 오버샘플링 하기 전 원본 데이터(0.91)보다도 더 높은 수치이다. 반면, Borderline SMOTE 데이터(0.80)는 가장 낮은 분류 성능을 나타냈다."로 본문의 내용을 수정한다. 코드 블럭 내 data_title의 내용을 'BorderlineSMOTE'를 추가한 "['no oversampling', 'RandomOverSampler', 'SMOTE', 'BorderlineSMOTE', 'KMeansSMOTE', 'SVMSMOTE', 'ADASYN']"으로 수정한다.
5. pg 60~65: 주석의 'feature 표준화'를 'feature scaling'으로 수정한다. '표준화 전후 데이터 분포 비교 시각화'를 'scaling 전후 데이터 분포 비교 시각화'로 수정한다. 
6. pg 68: 주석의 'np.log1m(y)를 통해 원래대로 되돌릴 수 있다'를 'np.expm1()'으로 수정한다.
7. pg 70: 코드 블럭 내 scores로 시작하는 17행의 위치를 19, 19행 다음인 20행으로 수정한다. 24, 25행의 pred_train, pred_test는 삭제해도 무방하다.
8. pg 85: sys_sampling 코드 블럭 내 "intoin = index-0"의 5행을 삭제한다.
9. pg 379: 다음의 코드 블럭 실행 결과를 추가한다. "log: ADF p-value 0.001, KPSS p-value 0.100, box-cox: ADF p-value 0.000, KPSS p-value 0.100"
