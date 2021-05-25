---
layout: single
title: "데이터형과 입력"
---

### 데이터형과 입력
---
[문제 상황]  
고속도로를 달리다 보면 서울이나 부산을 시작 기준으로 기점마다 거리를 표시하는 표지판을
볼 수 있습니다. 현재 표지판에 적힌 숫자와 도착지의 거리를 입력하였을 때 도착지까지 남은
거리를 계산하는 프로그램을 작성해 보시오.
~~~python
x= float(input('도착지점의 거리: '))
y= float(input('출발지점의 거리: '))
z=x-y
print('남은 거리는 {0}km 입니다'.format(z))
~~~
출력결과  
도착지점의 거리: 20.7
출발지점의 거리: 3.7
남은 거리는 17.0km 입니다