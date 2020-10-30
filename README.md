1. sklearn 라이브러리를 사용하여 데이터 변환
2. train_test_split를 사용해 훈련, 데이터 세트 분리
   (국민건강검진 공공데이터를 사용)
3. MinMaxScaler()를 사용해 데이터셋의 최소, 최대값 분석
4. fit()를 사용해 데이터셋 스케일 조정
5. transform()을 사용해 데이터셋 변환
6. SVC모델을 사용해 데이터 스케일 조정
7. SVC모델의 매개변수 C를 사용해 경계 허용정도 설정
8. score()를 사용해 테스트 세트 정확도 계산
9. StandardScaler()를 사용해 위와 같은 방법으로 데이터 스케일 조정

개발환경: python3.6.7(32bit), Windows 10
