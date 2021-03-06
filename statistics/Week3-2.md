# Week3-2

# 1. 상관관계

- 상관계수 : 두 변수 사이에 존재하는 **선형관계**의 **방향과 강도**를 측정하는 통계량
- -1 ≤ r ≤ +1 사이에 있다
- 상관관계가 될 수 있는 것은 **선형관계일 때만 가능**하다
- 곱으로 늘어난 관계를 선형으로 바꾸기 위해서는 로그로 변환해준다

이변량 자료의 요약 통계량

- x의 평균과 표준편차
- y의 평균과 표준편차
- x와 y의 상관계수 (r로 표기)

## 상관계수 구하는 절차

1. 각 변수를 평균으로부터의 편차로 변환한다
2. 두 편차를 서로 곱하여 합친 뒤 자유도n-1로 나누어 공분산을 구한다 (rmse)
3. 두 표준편차를 곱한다
4. 위 2.에서 구란 값을 위 3.에서 구한 값으로 나눈다

## 공분산 (Covariance)

- 공통으로 변하는 부분
- x의 편차와 y의 편차들의 곱의 **대략적**(자유도로 나눠줬기 때문)인 평균
- 단위와 상관없이 독립적으로 정의하기 위해 상관계수로 나타냄
    - 몸무게 단위 kg, g, pound에 따라 공분산은 달라진다
    - 공분산을 각각의 표준편차의 곱으로 나눠주면 단위가 상쇄되어 단위와 관계없이 정의가 된다

## 상관계수의 해석

- ‘상관계수=0.8’은 산포도 상에서 80%의 점들이 하나의 선 주위에 빽빽하게 밀집해 있다는 것을 의미하지 않는다
- ‘상관계수=0.8’은 상관계수가 0.4일 때보다 선형관계의 강도가 강하기는 하지만 정확히 두배로 강하다는 것을 의미하지도 않는다
- 상관계수가 유용하지 않은 경우
    - 이탈값이 있을 때
    - 두 변수간 관계가 비선형인 경우
- 상관계수가 0이라는 것은 두 변수 사이에 선형관계는 존재하지 않는다는 것
    - 두 변수 사이에 아무런 관계도 존재하지 않는 다고 말하면 잘못된 해석

## 변수 변환

- 적절한 변수변환을 통하여 비선형 관계를 선형관계로 근사시킴
- 로그 변환
- 시간이 지남에 따라 곱으로 변화하는 변수들에 적용
    - 로그임금과 경력, 로그 임금과 교육연수