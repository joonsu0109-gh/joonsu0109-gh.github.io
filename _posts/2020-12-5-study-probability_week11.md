---
layout: post
title: '[확률 및 통계]week11.Hypotehssi Testing 가설 검정'
subtitle: '11주차 내용 정리'
categories: study
tags: 2-2

---

### 1. Hypotehssi Testing (가설 검정)
#### 통계학적 추론
* 모수 추정
    1. 점추정 : 특정 모수 직접 추정
    2. 구간추정 : 모수가 포함 될 신로구간 범위 추정
#### 연구 절차
: 이론 세우기 -> 문헌 검토 -> 가설 세우기 -> 연구 계획&데이터 모으기 -> 데이터 분석하&가설검성 -> 출판 심사 -> 이론 세우기(순환)  
모래시계 모양으로 구체화 된다.
#### Hypothesis 가설
* 주어진 사실이나 조사하고자 하는 사실, 모수가 어떠하다 대한 추측  
* 귀무가설(H_0)와 대립가설(H_1 or H_a)로 나뉘어 서로 보완한다.
#### 귀무가설&대립가설
* Null hypothesis 귀무가설  
: 차이가 없다. 같다에 대한 내용. 등호(=)가 들어가야한다.
ex. 오렌지크기 = 사과크기
* Alternative hypothesis 대립가설, 연구가설
: 귀무가설과 다른 가설. 귀무가설이 거짓이라면 참이 되는 가설.  
ex. 오렌지 크기 ≠ 사과크기  
* 둘 중 하나가 선택되게 된다.
#### 예제
* 주사위는 공정하지 못하다.
: H_0 = P = 1/6, H_1 = P ≠ 1/6
이런식으로 주장에 대해서 귀무가설과 대립가설로 나눌 수 있어야한다.

### Type 1 error and Type 2 error
* Type 1 error (제 1종 오류)
: 가설검정 뒤 귀무가설을 기각했지만, 실제로는(사실은) 채택해야할 때
: flase alarm  

* Type 2 error (제 2종 오류)
: 가설검정 뒤 귀무가설을 채택했지만, 실제로는 기각해야할 때  
: mised detecton  
* Tradeoff
: Type 1과 Type 2 eror은 시소 관계이다.
![tradeoff](/assets/img/tradeoff.JPG)  
* 표본으로 부터 얻는 정보를 바탕으로 하기 때문에 오류가 있을 수 밖에 없다.

* 예제
    1. Before conducting inferential statistics, Tim selects the 
probability level required for statistical significance. 
This level is referred to as the _____ of the test.  
(alpha (α) level)
    2. Jenny reports that individuals who follow her diet plan 
lose more weight than individuals who follow Richard’s 
diet plan. In actuality, there is no difference in weight 
loss between those on Jenny’s versus those on 
Richard’s plan. Jenny’s claim illustrates a _____ error  
(Type I)
    3. Fred has concluded that there is no difference in 
driving ability between drivers who have consumed 1 
versus 3 cans of beer. However, there really is a 
difference in ability between the drivers. Fred has 
made a(n) _____ error.  
(Type II)
    * 풀이 방법
    : 독립/종속 나누기 -> 변수 유형 파악(nominal...) -> H_0, H_1 나누기 -> 주장/실제 나누기 -> error type 파악

#### significance leve α (유의수준)
* α = 0.05 의 의미
: 귀무가설 H_0이 타당함에도 불구하고 H_0을 기각하는 오류를 범할 위험이 20번을 조사했을 때 최대 1회까지는 허용되는 것을 의미
: Type 1 error을 범할 확률
* 구분
    * p < α = H_0 기각, H_1 채택
    * p > α = H_0 채택, H_1 기각
* α는 우연의 기준이라 할 수 있다.
* Power of test (검정력)
: Type 2 error을 범하지 않을 확률 1 – β
(중요도 낮음)
![Decision](/assets/img/decision.JPG)

#### (참고)SOC curve

#### Hypothess & Tails
* Two-tailed 양측검정
: 가설이 같다/같지않다로 나뉘는경우  
ex. 한 쪽 당 α/2
* One-taled 하단측검정/상단측검정  
: 하단측은 귀무가설이 왼쪽 부등호, 상단측 부분은 오른쪽 부등호  
ex. 한 쪽이 α
#### Hypothesis testing procedure 가설 검증 절차
1. 가설세우기
: 귀무가설과 대립가설로 나누어,구체적으로. +) two-tailed인지 one-tailed인지
2. 상황에 맞는 검정법 사용
3. p-value 찾기
4. p와 α를 비교하여 귀무가설 채택/기각 여부 결정
5. 결론 요약

#### 결론 의미
* 귀무가설 기각의 의미 
: 귀무가설의 기각은 거짓이라는 의미가 아니다.  
    오류가 있을 수도 있고, 귀무가설에 대한 충분한 증거가 없어 채택할 수 없다는 의미.
* statiscally significant 통계적으로 유의미하다
: p-value가 낮다 = 평균 확률이 일어날 확률이 낮다. = 우연이 일어날 확률이 낮다 = 우연히 같은 확률이 낮다.

#### 예제
* A researcher claims the average salary of new employees at Company A > $42,000. Is this true?   Sample of 30 has a mean salary of $43,260, σ = $5,230 (α = .05)

1. H_0 : mean <= $42000, H_1 : mean > $42000, ratio value
2. z-vlaue = 1.32, p value - 0.0934  
(z니까 표준정규분포 표 이용)
3. p > α. can not reject the null.
4. No. cannot claim the average salary of new employees at company A > $42000
