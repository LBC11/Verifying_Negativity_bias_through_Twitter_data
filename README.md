# Database-Practice-Web-Programming
3학년 과목중 하나인 Database Practice Web Programming 에서 진행한 team project.

#### 주제
- 트위터 데이터를 통한 부정 편향성 검증

#### Motivation
- Negativity Bias. Bad events having a more significant impact on our psychological state than positive events.

![image](https://user-images.githubusercontent.com/108987773/208585767-e9a810cb-ae09-468d-b312-ce165b75414c.png)  

- What is negativity bias?
  - A negativity bias is a cognitive bias that results in adverse events having a more significant impact on our psychological state than positive events. 
  
#### Assumptions
1. Twitter users were also negatively biased, and the results will be in the data collected on Twitter.
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
