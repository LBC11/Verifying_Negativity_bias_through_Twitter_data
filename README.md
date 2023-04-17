# Database-Practice-Web-Programming
Team project in Database Practice Web Programming

#### 주제
- 트위터 데이터를 통한 부정 편향성 검증

#### 동기
사람들이 부정적이거나 자극적인 뉴스일수록 많은 관심을 보이는 경향으로 인해, 점점 더 많은 기사들이 부정적인 주제를 다루기 시작하였고 사람들이 과도한 자극으로 인해 염증을 느끼며 오히려 뉴스 보는 것을 꺼리게 되었다는 기사를 본 적이 있다. 그 기사를 통해 부정 편향성(Nagativity Bias) 이라는 개념을 알게 되었다.   

![image](https://user-images.githubusercontent.com/108987773/208585767-e9a810cb-ae09-468d-b312-ce165b75414c.png)  

- 부정 편향성이란?
  - 우리 뇌가 생존에 중요한 정보를 파악하기 위한 진화적으로 발전한 메커니즘 중 하나로 인간의 지각과 판단 과정에서 부정적인 정보에 대해 더 큰 가중치를 두는 경향을 말합니다. 즉, 동일한 강도의 긍정적인 정보와 부정적인 정보가 주어졌을 때, 부정적인 정보에 더 강한 반응을 보이는 것을 의미합니다.
  
#### 가정
1. 트위터 유저들 또한 부정 편향성을 가지고 있고 그에 대한 결과가 Twitter data에 나타날 것이다.
2. 사람들이 부정적으로 인식하는 주제가 Real-time trends 항목에 더 오래 머무를 것이다.

#### 목표
- 사람들이 부정적으로 인식하는 키워드가 더 오래 혹은 더 많이 주목을 받는게 맞는지 검증하고 그 결과를 web으로 표현

#### 파이프 라인
<img width="464" alt="Screenshot 2022-11-12 at 10 03 22 PM" src="https://user-images.githubusercontent.com/108987773/201475299-88b30f88-b98a-4512-ba5f-237de7727ef4.png">

#### 결과
<img width="500" alt="image" src="https://user-images.githubusercontent.com/108987773/208584507-ed73c3a2-31bd-44da-8861-f52ed90937bf.png"><img width="500" alt="Screenshot 2022-12-20 at 1 35 45 PM" src="https://user-images.githubusercontent.com/108987773/208584673-3d880f72-8351-4a02-8b48-27fb4ad006b1.png">

#### 결론
- 트위터에서 활동하는 사람들이 부정 편향성을 가지고 있다고 할만큼 의미있는 반응을 보이지 않았다.

##### 한계점
- 대부분의 트위터를 이용하는 사람들은 20~30살이라서 모든 연령군을 어우르는 결과라고 할 수 없다.
- 긍정 부정 보다는 중립적인 반응을 보이는 사람들이 근소하게 많았다.
- AWS Lamda 서비스의 실행 시간이 15분으로 한정되어 있어 완전히 자동적으로 서비스가 이뤄지지 않았다.
- 데이터의 양이 많으면 스파크의 runtime이 6시간으로 제한되어 있기 때문에 데이터가 업데이트되지 않습니다.

##### 후기
결과가 매우 잘 나오고 구현을 기가 막히게 잘한 것은 아니지만 하나의 분기점이 된 프로젝트이다. 내가 무엇을 할 수 있는지 보다는 어떤 주제가 더 흥미있고 재미있는지, 무엇을 사용해야 더 좋은 결과가 나오는지를 우선순위에 두고 진행한 첫 프로젝트이다. 프로젝트를 시작하기전에는 AWS 등 이 프로젝트에 사용된 기술들를 사용해 본적도 없이 처음부터 공부를 시작해서 진행하였다. 시행착오도 많았고 시간도 오래 걸렸지만 결국 해냈고 실제로 프로젝트 평가에서도 높은 점수를 받았다. 이 프로젝트 이후로 무엇이든 시간만 주어진다면 해낼 수 있다는 자신감이 생겼고 적극적으로 의견을 제시하기 시작했다. 
