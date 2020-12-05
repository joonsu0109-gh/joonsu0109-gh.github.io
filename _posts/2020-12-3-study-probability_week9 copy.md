---
layout: post
title: '[확률 및 통계]week9 Population and Sample Central Limit Theorem'
subtitle: '9주차 내용 정리'
categories: study
tags: 2-2
use_math: true

---


### 1. POPULATION AND SAMPLE (모집단과 표본)
* population = 모집단, Paramter = 모수   모수 = 모집단의 특성을 나타내는 수치  
ex. 모평균, 모분산, 모표준편차  
    모집단은 전체 집합이기에 전수조사를 한다는 것이 불가능하다. ->  표본을 선정해 조사
ex. 대한민국 전체 남자의 평균 키  
    <br/>
![모수와 통계량 기호](/assets/img/sign.JPG)   

* Sample = 표본, Statistic = 통계량  
통계량 = 표본으로 산출 된 것, 확률변수 (sampling을 할 때 마다 그 집단이 달라지기 때문. 그렇기에 표본평균이 확률변수이다.)
<br/>

* [parameter vs sample 영상](https://ko.khanacademy.org/math/statistics-probability/sampling-distributions-library/sample-means/v/statistics-sample-vs-population-mean?modal=1)

* [표본평균 영상](https://ko.khanacademy.org/math/statistics-probability/sampling-distributions-library/what-is-a-sampling-distribution/v/introduction-to-sampling-distributions?modal=1)

### 2. CENTERAL LIMT THEOREM (중심 극한 정리)

* 중심극한정리(CLT) : **표본의 개수가 충분하면**, **모집단에 관계 없이**, 표본 통계량으로 정규분포 구성가능(표본 평균의 분포가 정규분포에 가까워진다.)  
<br/>

* [중심극한정리 영상](https://ko.khanacademy.org/math/statistics-probability/sampling-distributions-library/sample-means/v/central-limit-theorem)  
<br/>

* 표본이 20개 이상일 때 중심극한정리에 따라 표본평균이 정규분포에 근사한다. ![표본평균](/assets/img/statistic.JPG)  
<br/>

* [표본평균이 정규분포 따름 영상](https://ko.khanacademy.org/math/statistics-probability/samplingdistributions-library/sample-means/v/standard-error-of-the-mean)  
<br/>

* 유용성  
 : 범용적, 평균과 분산만 알면 된다, 계산용이, Z_n의 CDF가 Z로 수렴한다, 표본이 대칭성이 어느정도 있으면, 그 수가 적어도 정규분포로 수렴 가능하다.  
<br/>
  
* binomial(이항분포)에서의 적용  
 : 이항분포의 평균, 분산 공식(평균 = np, 분산 = np(1-p))를 이용하여 더욱 쉽게 표준화할 수 있다.

### 3. SAMPLE MEAN AND VARIANCE (표본평균과 표본분산)

* 표본평균이 확률변수가 되어 표본평균의 평균과 분산을 구한다.
</br>

![표본분산](/assets/img/variance.JPG)  

* 다만, 분산의경우 n이 아닌 n-1로 나눠준다.  
(모집단을 샘플링하면 상대적으로 중앙값이 많이 포함된다. 따라서 표본은 모집단에 비해 편향된, 즉 더 분산이 작은 값이 나올 수 밖에 없다. 따라서 n이 아닌 n-1로 나눠줌으로서 편향되지 않도록 해준다.)
</br>

* [n-1로 나눠야 분산과 같아지는 수학적 증명](https://hsm-edu.tistory.com/15)  
</br>

* [표본 평균 수학적 증명](https://j1w2k3.tistory.com/1309)

### 4. SAMPLING (표분추출)

* 표본 추출 방법  
    * simple random sampling : 동일한 확률로 랜덤 샘플링
    * statified sampling : 층화 샘플링, 그룹을 나눠 그룹 별로 랜덤 샘플링
    * clustered sampling : 군집으로 나눈 뒤, 랜덤으로 군집 샘플링. 그 뒤 군집 조사
</br>

* 각 표본마다 다른 결과를 가져오는 변동성이 있다.  
* sampling의 정확도는 표본의 크기에 달려있다. 모집단(population)의 크기와 상관 없다.
* 신뢰구간(confidence intervals)  
모수가 실제로 포함될 것으로 에측되는 범위.  
샘플의 수가 클 수록 신뢰구간의 크기는 줄어든다(=신뢰도는 증가)  
* 다만, 샘플 수가 늘어남에 따른 비용증가를 고려해야한다.  
![표본 크기에 따른 신뢰도](/assets/img/sample_size.JPG)
* 위 자료를 보면 95%구간에서는 샘플의 사이즈가 커져도 신뢰도의 차이는 그에 비해 미미하다. 95%정도에서는 샘플의 수가 100만 되도 충분하다고 한다.