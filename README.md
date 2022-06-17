# Simple-Linear-Regression

## 단순선형회귀분석 (Simple-Linear-Regression-Analysis) 의 정의
선형회귀 분석은 독립 변수(independent)와 종속(dependent) 변수 간의 관계를 찾는 통계적 방법이다.
## 단순선형회귀 (Simple-Linear-Regression-Analysis) 를 위한 용어정리
  H(x) = Wx+b
  -파라미터(parameter)  
    1.독립변수 x     
    2.종속변수 y    
  - 모수  
    1.기울기 W   
    2.절편 b
## 단순선형회귀 (Simple-Linear-Regression-Analysis) 를 위한 기본개념
  -비용함수  
  예측값과 실제값의 오차라고 할 때, ![3](https://user-images.githubusercontent.com/101388180/174298748-1a811e35-5c47-4750-a6a5-66827e7a8f0d.PNG) 비용함수를 위와같이 정리 할수있다. 이는 평균 제곱 오차를 사용해 구할수있다. (m은 데이터 개수)

  -경사하강법(Gradient Descent)  
 경사 하강법는 비용 함수(Cost function)를 미분하여 현재 W에서의 접선의 기울기를 구하고, 접선의 기울기가 낮은 방향으로 W의 값을 변경하고 다시 미분하고 이 과정을 접선의 기울기가 0인 곳을 향해 W의 값을 변경하는 작업을 반복하는 것이다. 비용이 최소화되는 지점은 cost가 최소화되는지점 즉 접선의 기울기가 0이 되는 지점이다.
![4](https://user-images.githubusercontent.com/101388180/174299305-827646f1-063b-4844-b907-5f1f72316cd4.PNG)
### 작동 원리

### 유전 알고리즘에서 돌연변이 발생
    단순 선형회귀에서의 돌연변이 방식에서 확률은 기울기값을 변경시킬때 얼마나 크게 변경할지를 결정하는 것이다.  
    확률과 기울기값차는 비례한다.
### 유전 알고리즘에서 돌연변이에 따른 상황
    단순선형회귀에서 지나치게 높은 돌연변이가 발생하면 학습속도가 느려진다. 반대로 낮은 돌연변이 발생 확률은 학습속도는 빠르나 정확도가 낮다 따라서 시간에 따라 적당한 돌연변이가 중요하다.
### 모수값 추정(추정된 모수 값이 적절한지 검증)
  -최소제곱법 (Least Squares method)  
  
### 최적화 과정에 대한 분석 (최적화되는과정에서 에러가 감소하는 경향 표현)
## 함수 및 매개변수 값들에 대한 설명
![image](https://user-images.githubusercontent.com/101388180/174302902-184e1cd1-1c4b-4846-b015-53d66286111c.png)

x축 즉 독립변수는 연도 y축은 남성선수들의 기록이다.
![5](https://user-images.githubusercontent.com/101388180/174302692-000f71e0-f215-4960-b356-46f08c563c78.PNG)
