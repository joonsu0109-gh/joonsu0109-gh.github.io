---
layout: post
title: '[확률 및 통계]기말범위 기출풀이'
subtitle: '기출 풀이'
categories: study
tags: 2-2

---

##### 1. Angelina notices that her Ob-Gyn doctor(산부인과 의사) often looks tired. She wants to determine whether sleepdeprived Ob-Gyn residents make more errors when delivering babies than well-rested residents. (수면부족 산부인과 의사들이 더 많은 오류를 내는지 푹쉰 의사보다)

* H_0 : E_d =< E_w , H_1: E_d > E_w 
* nominal, ratio, 평균비교 => t-test
* 만일 IV가 ratio면 correlation 쓰는게 맞음

1-1. What is Independent Variable (IV) of Angelina’s research question and the IV’s data type?  
IV : **수면 부족 여부(부족/충분) (독립변수는 1개 2수준) / 수면 량(4시간...)**
IV’s data type: **nominal/ratio**

1-2. What is Dependent Variable (DV) of Angelina’s research question and the DV’s data type?
DV: **실수 횟수**
DV’s data type: **ratio**

1-3. Which statistical test would be most appropriate to analyze the data?
a. Chi-square **b. t test**
c. Pearson correlation d. F test

##### 2. Jennifer wonders if she really needs an expensive camera with high resolution for her research.(연구에 있어서 고해상도의 카메라가 필요한지) Before she decides to buy the camera, she designs an experiment comparing target detection rates(목표 탐지 비율) when participants are given low, medium or high resolution images respectfully. (저, 중, 고 해상도 이미지 있을 때)

* H_0 : 저 >= 중 >=  고 (차이가 안남), H_a : 저 < 중 < 고 (차이가 남)
* 2 그룹 이상(저, 중, 고 해상도)의 평균 비교 -> ANOVA

2-1. What is IV of Jennifer’s research question and the IV’s data type?  
IV: **resolution(해상도) (1개 3수준(저중고))**
IV’s data type: **nominal/ordinal (둘 다 가능)** 

2-2. What is DV of Jennifer’s research question and the DV’s data type?  
DV: **target detection rates(목표 탐지 비율)**
DV’s data type: **ratio**  

2-3. Which statistical test would be most appropriate to analyze the data?2
**a. ANOVA** b. t test
c. Pearson correlation d. Chi-square

##### 3. Brad wants to examine if people prefer the new touch screen to the traditional QWERTY keyboard.(사람들이 쿼티 키보드보다 터치스크린을 좋아하는지) He is planning to ask yes/no questions after giving each participant an opportunity to use either a touch screen or a QWERTY keyboard. (뭐가 더 좋은지 물어보려고 함)

* H_0 : 선호도 차이가 없다. H_a : 선호도 차이가 있다.
* 대답할 때 어떻게 하는지로 DV 정해야함

3-1. What is IV of Brad’s research question and the IV’s data type?
IV: **키보드 종류(쿼티/터치)**
IV’s data type: **nominal**

3-2. What is DV of Brad’s research question and the DV’s data type?
DV: **선호도(좋다/안좋다)**
DV’s data type: **nominal**

3-3. Which statistical test would be most appropriate to analyze the data?
a. t test **b. Chi-square**
c. Pearson correlation d. ANOVA

##### 4. George wants to determine if his innovative weight loss training is effective. He wants to compare body weight before and after he gives his training to the volunteers. (개발한 트레이닝 방법의 체중 감량 전 후 비교)

* H_0 : W_전 = W_후, H_1 : W_전 != W_후
* 동일한 참가자를 대상으로 비교하기 때문에 paired t-test가 맞음

4-1. What is IV of George’s research question and the IV’s data type?
IV: **트레이닝 전/후(변수는 1개 수준은 2개)**
IV’s data type: **nominal**
4-2. What is DV of George’s research question and the DV’s data type?
DV: **체중**
DV’s data type: **ratio**
4-3. Which statistical test would be most appropriate to analyze the data?
**a. Paired t-test** b. Independent t-test
c. ANOVA d. Pearson correlation3

##### 5. Madonna notices her son often sends/reads text messages while he talks to her. She is unsure if he is fully engaged in their conversation even though he claims to be.(대화하면서 문자 집중이 가능한지 궁금) Thus, she designs a study to see whether multiple communications through different modes are as effective as single communication. She is planning to compare test scores after participants speak to one another vs. speaking & read text messages simultaneously. (다른 모드의 멀티 커뮤니케이션이 싱글 커뮤니케이션만큼 효과적인지)

* H_0 : Score_m =< Score_s, H_1: Score_m > Score_s

5-1. What is IV of Madonna’s research question and the IV’s data type?
IV: **text메세지 사용 여부**
IV’s data type: **nominal**

5-2. What is DV of Madonna’s research question and the DV’s data type?
DV: **Test score**
DV’s data type: **ratio**

5-3. Which statistical test would be most appropriate to analyze the data?
a. Pearson correlation b. Chi-square
**c. t test** d. F test

#### 6. Bruce is interested in studying whether responses to lowering the legal age of drinking alcohol (for or against) varies by gender (male or female). (술을 마실수 있는 법적인 나이를 내리는 것에 대해 성별에 따라 나뉘는지)

* H_0 : 주장에 대해 성별과는 독립적이다. , H_1 : 주장에 대해 성별에 종속적이다.
* 이런 주장에 대한 것은 independent와 dependent로 가설을 나눠줄 수 있다. 그리고 독립적인 것이 귀무가설로 온다.

6-1. What is IV of Bruce’s research question and the IV’s data type?
IV: **성별(1개 2수준)**
IV’s data type: **nominal**

6-2. What is DV of Bruce’s research question and the DV’s data type?
DV: **선호(좋다/나쁘다)**
DV’s data type: **nominal**

6-3. Which statistical test would be most appropriate to analyze the data?
**a. Chi-square** b. ANOVA
c. t test d. Pearson correlation

##### 7. Alex wants to determine if cholesterol level is lower for vegetarians versus non-vegetarians. Which statistical test would be most appropriate to analyze the data?(채식주의자들의 콜레스트롤 레벨이 비채식주의자들보다 낮은지)

* H_0 : C_v >= C_n, H_1 : C_v < C_n
* 

7-1. What is IV of Alex’s research question and the IV’s data type?
IV: **채식주의자 여부**
IV’s data type: **nominal**

7-2. What is DV of Alex’s research question and the DV’s data type?
DV: **콜레스테롤 레벨**
DV’s data type: **ratio**

7-3. Which statistical test would be most appropriate to analyze the data?
a. ANOVA **b. t test**
c. Pearson correlation d. Chi-square

#### (살짝 햇갈림) 8. John wants to examine the relationship between temperature and number of ice cream cones sold during the month of July? (7월의 온도와 아이스크림 판매량이 관련이 있는지)

* H_0 : independent 관련X, H_1 : dependent 관련 o
* correlation 상관성 -> 상관선 분석으로.

8-1. What is IV of John’s research question and the IV’s data type?
IV: **온도**
IV’s data type: **interval(21도는 7도보다 3배 더운게 아니다.)**

8-2. What is DV of John’s research question and the DV’s data type?
DV: **7월 아이스크림 판매량**
DV’s data type: **ratio** 

8-3. Which statistical test would be most appropriate to analyze the data?
a. Chi-square b. ANOVA
c. t test **d. Pearson correlation**

#### 시험에서는 독립변수 1개만 나옴.

#### 9. What is the difference between descriptive(서술하다) and inferential(추정하다) statistics? Descriptive statistics ______, while inferential statistics ______.(기술통계와 추정통계의 차이점)

* 가설검정 = 추정(pvalue = 우연의 확률. 결과의 우연에 대한 확률 결정), desriptive는 내가 가진 정보를 서술(같은 자료를 가지고도 잘 알아볼 수 있도록).

A) use ratio data; use nominal data  
B) use nominal data; use ratio data  
**C) summarize data; determine the probability that results are due to chance**
D) determine the probability that results are due to chance; summarize data

##### 10. A researcher employs inferential statistics to examine the difference in mean scores obtained by fourth grade boys and girls on a standardized math test. Inferential statistics(4개의 학년에서 남자와 여자들이 얻은 점수의 평균의 차이 추정통계 채택.)

A) summarize and describe the important characteristics of the data. (determinant)
**B) test the research hypothesis.**
C) indicate the strength of the relationship between boys and girls math scores.(위 예제는 상관성을 보는것은 아님)
D) indicate the probability that the difference between means reflect random error.(D도 관점에 따라 답 가능)

##### 11. Brandon found no significant difference in amount of money spent on entertainment between students who live on versus off campus. Based on this finding, Brandon would (기숙사와 기숙사 아닌 학생들 사이의 지출에 있어서, 유의미한 차이가 없다 = 귀무가설 채택)

**A) accept the null.**(can not reject null)
B) reject the null.
C) accept a Type I error.
D) reject a Type I error.

##### 12. How do you calculate the systematic variance? 

* anova(분산분선법에서) systemic variance, error variance나왔었음

A) Find the deviation of the individual scores about the group mean. (표본평균과 표본들의 차이 error variance)
**B) Find the deviation of the group means about the grand mean.**(표본평균들과 전체 평균의 차이 systemic variance)
C) Find the deviation of error variance about the group mean.
D) Find the deviation of error variance about the grand mean.

##### 13. Error variance is the deviation of
**A) the individual scores about the group mean.**
B) the group means about the grand mean.
C) error variance about the group mean.
D) error variance about the grand mean

 