---
layout: post
title: '[확률 및 통계]week13. ANOVA(Analysis of variance)'
subtitle: '11주차 내용 정리'
categories: study
tags: 2-2

---
### 1. F-test
#### F-disribution(F-분포)
* 두 개의 분산에 대한 추론. 2개의 자유도를 가진다.
#### F-test
* 독립적인 샘플, 정규분포에서 분산을 비교하기 위한 검정
* 자유도
: Num : n_1-1, Den : n_2 -1
![f_test](/assets/img/f_table)

### 2. ANOVA 분산분석법
#### ANOVA 경우
* 2그룹보다 많은 대상을 비교할 때  
(그룹이 많은데 2그룹씩 비교하면 틀릴 확률이 올라가, 유의수준 허용치를 넘음.type 1 error 위험)
#### ANOVA 비교 2가지
* 그룹 안에서(error varience)
: 그룹 안 요소들과 그룹의 평균을 비교
* 그룹 들 간에(systematic variance)
: 그룹들 간의 평균 비교
* 그룹 내부와 그룹간의 변동성을 한 번에 비교하기 어렵기 때문에 나눠서 비교
* F-test의 값(분산)을 통해 그룹들의 평균을 비교할 수 있다. 그래서 평균을 비교하지만, 분산분석법.
![anova](/assets/img/anova.JPG)
![anoava_model](/assets/img/anova_model.JPG)
#### One-way ANOVA review
![f-test](/assets/img/f-test.JPG)
* 비교 하나일 때
* DOF
– Num: Number of groups -1(SSTR 그룹간 비교에)  
– Den: total number of subjects – number of group(SSE 그룹내 비교에)

#### Multi Factor ANOVA/MANOVA
* 여러 독립적인 변수들이 미치는 영향을 조사할 때  
ex. 2x3(남/여, 20대/30대/40대)
* MANOVA : 여려 종속적인 변수들을 조사할 때
ex. 만족도 뿐만 아니라 성능, 가격 등을 조사할 때
* 표본의 수가 동일 하지 않을 때 사용

### 3. DESIGN OF EXPERIMENT
#### DOE(Design of Experiment) Terminology
* Independent Variables : 조작하는 것
* Dependent Variables : 측정하는 것
![variables](/assets/img/variables.JPG)
* 변수의 종류에 따라 test 선택
![example](/assets/img/example.JPG)