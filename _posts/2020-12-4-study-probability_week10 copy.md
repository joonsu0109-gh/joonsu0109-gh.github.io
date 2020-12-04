---
layout: post
title: '[확률 및 통계]week10.Estimation
Hypothesis testing
Significance level/p-value'
subtitle: '10주차 내용 정리'
categories: study
tags: 2-2

---

### 1. Estimation (추정)
#### 점추정과 구간추정
* Etimation(추정) : 표본을 대산으로 도출된 통계량
* 점추정 : 
* 구간추정 : 
#### 구간추정 & 신뢰구간
![신뢰구간](/assets/img/confidence.JPG)
* 표준 정규분포로 나타낼 수 있음을 확인할 수 있다.
#### 표준오차 vs 표준편차
* 표준오차 (standard error)  
: '표본평균들 간'의 산포
* 표준편차 (standard deviation)
: 표본 평균으로 부터 '표본들이' 흩어져 있는 정도  
* 표준오차가 작다 = n개의 표본의 평균들이 모여있다는 것 
표준편차가 작다 = 1개의 표본에대해 표본들이 평균에 모여있다는 것
#### 모평균의 구간추정(신뢰구간)
![신뢰구간](/assets/img/confidence2.JPG)
* 표준편차를 이용해 표준오차 구할 수 있다.

    ### α
    * 신뢰구간 = 1-α. 신뢰구간으로 90%, 95%, 99%, 99.9% 주로 이용.

### 2. 유의수준 & P-VALUE
#### significance leve α (유의수준)
* Type 1 error(틀릴확률)이 나올 최대 확률.  
ex.  α = 0.05 =-> 95% 올바른 결정.
* 0.05와 0.01 주로 이용. 하지만 α 는 연구자가 결정. α를 너무 크게 잡으면 trade-off 위험.

#### p-value
* p-value  
: 우연의 확률. 귀무가설이 맞는데 틀렸다고 결론을 내릴 확률.
ex. 사과&오렌지, 사과&수박 중에서 사과&수박의 크기가 같을 확률이 더 낮음  
= 우연의 확률 p-value가 더 낮음
* p와 α를 비교하여, p가 더 작으면 귀무가설 기각  
* α의 크기를 작게 설정 = 왠만하면 귀무가설 기각 X
* 연구자는 자신의 가설(대립가설)이 지지되기를 원하기 때문에 낮은 p-value 원함.