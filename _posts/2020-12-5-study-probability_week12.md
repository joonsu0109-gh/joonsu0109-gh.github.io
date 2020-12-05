---
layout: post
title: '[확률 및 통계]week12.Parametric test
Nonparametric test 가설검정방법'
subtitle: '11주차 내용 정리'
categories: study
tags: 2-2

---

![test](/assets/img/test.jpg)

### 1. T-TEST 
#### Hypothesis Testing: t Tests for a Mean
* 모분산을 모르고, n < 30 일 때 평균 비교를 위해 사용.
![t_tset](/assets/mg/t_test.JPG)
* t-table에서 degree -> t값 -> 예상 p 순으로 찾는다.
![t_table](/assets/img/t_table.png)
ex. 간호사 10명의 평균 급여 비교
#### Difference in Means - Small Populations

* 독립적인 두 집단을 비교하고, 정규분포를 따르며, n<30인 경우
* 분산이 동일한지 다른지에 따라 t값 계산식이 달라진다.

#### Difference in Means: Dependent Sample
* 짝이 이뤄진 샘플의 경우  
ex. 전/후 비교
#### p-vlaue vs critical value
* p-value는 영역이고, critical vlaue(임계정)은 그래프 x축 값이다.
* p < α = test statistic > critical value  
(x축 값이 커야 영역이 작으니까)

### 2. CHI-SQUARE TEST

#### Chi-square χ^2 test
* 그리스 문자 χ
* nominal 데이터 이고, 정규분포 따르고, 데이터 카테고리의 선호도를 비교할 경우.
![chi_square_test](/assets/img/chi_test.JPG)
* H_0 : 선호도에 상관 X, H_a : 선호도 상관 O
#### Chi-Square distribution (카이제곱분포)
* 자유도 = option - 1 
* 평균은 문제에 나와있는 값 이용.
* 총 그룹 수 만큼 더해준다.

### 2. NON-PARAMETRIC TEST

#### NON-PARAMETRIC TEST
* 분포가 정규분포를 따르지 않을 경우
* 평균, 분산 등 추정 불가  
ex. chi-square

#### Pros & Cons
* 장점
: nominal & ordinal data 전용. 모수 필요 X, 계산과 이해가 쉽다.
* 단점
: 덜 민감하다(통계적으로 유의미할 확률이 적다.), 적은 정보와 덜 정확한 정보 이용, 따라서 많은 샘플의 수를 필요로해 효율성이 적다.

#### Non-parametric tests(참고)
* 독립적인 샘플
    * paired testing
    : Sign, mann whtney, kruskal-wallis

* 종속적인 샘플
    * paired
    : mann whitney, McNemar, Friedman

#### sign test
* 두 가지의 차이의 크기가 아니라, 단지 그 차이가 (=), (=), 0 인지만 구분