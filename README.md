# 선형회귀분석 프로젝트

## Goals
KBO 프로야구 타자 연봉 예측

## Technical Skills
- 사용언어: python
- 데이터 크롤링: beautifulsoup, selenium
- 데이터 전처리: pandas
- 시각화: plotly
- 선형회귀: statsmodels

## Data
[statiz](http://www.statiz.co.kr/main.php)의 데이터 사용

#### train
    시즌 2010 ~ 2017 데이터

#### test
    시즌 2018 데이터

## Procedure
<img width="650" alt="lr1" src="https://user-images.githubusercontent.com/57264003/87558203-cbfe1380-c6f3-11ea-90b1-3605180511f3.png">

#### 모델1
    야구선수기록에 시즌, 나이를 카테고리화 하여 나누고, 변수들에 scaling 하여 분석

#### 모델2
    종속변수인 '연봉'에 로그를 취하여 분석

#### 모델3
    추가하여 분석

#### 모델4
    FA계약 데이터 추가, 연봉의 현재 가치 반영하여 분석

## Result

<img width="1020" alt="스크린샷 2020-07-12 오후 5 03 31" src="https://user-images.githubusercontent.com/57264003/87558452-167f9000-c6f4-11ea-872a-723cca03fd61.png">
<img width="1018" alt="스크린샷 2020-07-12 오후 5 03 19" src="https://user-images.githubusercontent.com/57264003/87558458-18e1ea00-c6f4-11ea-97ce-fda641ee68a6.png">


$R^2$  **0.868** 
$ MSE$  **0.13** 
