# 2. Gradient Descent & Learning rate

## **2.4 미분과 기울기, 그리고 경사 하강법의 개념**

![Untitled](Gradient%20Descent%20&%20Learning%20rate/Untitled.png)

### 기본적인 미분

- 기울기 구하는 법
    

![IMG_7956.jpg](./Gradient%20Descent%20&%20Learning%20rate/IMG_7956.jpg)    

    

- basic 미분
    
    ![IMG_7957.jpg](Gradient%20Descent%20&%20Learning%20rate/IMG_7957.jpg)
    

정점을 향해서 (극한) 무수히 많은 점이 가기 위한 기울기..

## 연쇄법칙(chain rule)

어떤 함수 y를 x에 대해 미분할 때, 매개변수 t를 대입하여 미분할 수 있는 것이다.

![Untitled](Gradient%20Descent%20&%20Learning%20rate/Untitled%201.png)

## 경사하강법

x_2의 위치에서 x 가 증가하면 y 도 증가하므로 접선의 기울기는 양수이다. 따라서 x_2 에서 음의 방향으로 움직이면 목적함수를 줄일 수 있다. 즉 f^′ (x_2 )의 반대 방향인 〖-f〗^′ (x_2 )로 이동한다

![Gradient.png](Gradient%20Descent%20&%20Learning%20rate/Gradient.png)

**기울기가 우리가 구하고자하는 최솟값 경사의 기울기가 줄어드는 방향으로 X값을 구하는 방법**

## **2.5 편미분과 기울기**

편미분

- 둘 이상의 변수들을 가지는 함수 f가 있을 경우, 이 함수를 각각의 벼수에 대해서 독립적으로 미분을 하는 방식, **변수에 대해서 하나에 대해 미분을 하고 하나는 상수로 취급(없어짐)**
- x_ ,y**두 변수로 이루어진 함수** f(x,y)=x^2+xy+y^2**가 있을 경우 x, y에 대한 편미분은 다음과 같이 각각 구할 수 있음.**

![Untitled](Gradient%20Descent%20&%20Learning%20rate/Untitled%202.png)

                                                          계산하기 전 중요한 미분의 기초

![IMG_7958.jpg](Gradient%20Descent%20&%20Learning%20rate/IMG_7958.jpg)

기울기 벡터

![Learning_rate.png](Gradient%20Descent%20&%20Learning%20rate/Learning_rate.png)

- **그림에서**∂f(x_1,y_1 )∕∂ x**는 목적함수의** f(x_1,y_1 )**에 닿는 접선이** x **축 방향으로 갖는 기울기를 의미한다. 비슷하게** ∂f (x_1,y_1 )∕∂ y**는** y **축 방향 기울기이다.** x∈R^n **의 벡터를 입력으로 하는 함수** f(x) **의 기울기 벡터** ∇f(x)**는 모든 차원의 기울기를 원소로 하는 벡터로 다음과 같이 정의된다.**

![Untitled](Gradient%20Descent%20&%20Learning%20rate/Untitled%203.png)

### 학습률

![Learning_rate1.png](Gradient%20Descent%20&%20Learning%20rate/Learning_rate1.png)

**전체적인 기울기가 기울기 값이 줄어드는 방향으로 값을 바꿔주게 되면 z의 최솟값이 구할 수 있게된다.** 

-(임의의 상수값)기울기f(x_1,y_1) = 학습률 / z = f(x,y)
