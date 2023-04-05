# Database-Practice-Web-Programming
Database Practice Web Programming, ITM 3학년 과목, 에서 진행한 team project.

#### 주제
- 트위터 데이터를 통한 부정 편향성 검증

#### 동기
- 사람들이 부정적이거나 자극적인 뉴스일수록 많은 관심을 보이는 경향으로 인해, 점점 더 많은 기사들이 부정적인 주제를 다루기 시작하였고 사람들이 과도한 자극으로 인해 염증을 느끼며 오히려 뉴스 보는 것을 꺼리게 되었다는 기사를 본 적이 있다. 그 기사를 통해 부정 편향성(Nagativity Bias) 이라는 개념을 알게 되었다.   

![image](https://user-images.githubusercontent.com/108987773/208585767-e9a810cb-ae09-468d-b312-ce165b75414c.png)  

- 부정 편향성이란?
  - 우리 뇌가 생존에 중요한 정보를 파악하기 위한 진화적으로 발전한 메커니즘 중 하나로 인간의 지각과 판단 과정에서 부정적인 정보에 대해 더 큰 가중치를 두는 경향을 말합니다. 즉, 동일한 강도의 긍정적인 정보와 부정적인 정보가 주어졌을 때, 부정적인 정보에 더 강한 반응을 보이는 것을 의미합니다.
  
#### Assumptions
1. Twitter users were also negatively biased, and the results will be in the data collected on Twitter.
2. Keywords that people react negatively to will stay longer in real-time trends.

#### 가정
1. 트위터 유저들 또한 부정 편향성을 .
2. Keywords that people react negatively to will stay longer in real-time trends.

#### Goal
- Checking this phenomenon on Twitter to see if the number of tweets(keywords) that people reacted negatively is really higher and demonstrating on web.

#### Pipeline
<img width="464" alt="Screenshot 2022-11-12 at 10 03 22 PM" src="https://user-images.githubusercontent.com/108987773/201475299-88b30f88-b98a-4512-ba5f-237de7727ef4.png">

#### Result
<img width="500" alt="image" src="https://user-images.githubusercontent.com/108987773/208584507-ed73c3a2-31bd-44da-8861-f52ed90937bf.png"><img width="500" alt="Screenshot 2022-12-20 at 1 35 45 PM" src="https://user-images.githubusercontent.com/108987773/208584673-3d880f72-8351-4a02-8b48-27fb4ad006b1.png">

#### Conclusion
- It is shown that reactions of people did not significantly affect negativity bias on Twitter.

##### Limitation
- It does not show reactions of all age groups.
- Probability of neutralization was slightly higher.
- When the execution time exceeded 15 minutes in Lambda, it causes an error not achieving full automation.
- If data volumes are high, the data will not be updated because spark runs for 6 hours.
