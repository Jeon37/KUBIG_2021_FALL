# 따릉이 🚲 이용 예측 모델 만들기!!

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1HfV7i1MzvgYRKH2BncXkXNLjrNXqoaTN) 

☝️open code by colab

## 프로젝트 소개
- 여러 환경 변수들을 바탕으로 서울시 따릉이 이용량을 예측하는 모델을 만들자!!
- 팀원 : 임형우, 남이량, 임혜리, 김수경 

## 프로젝트 개요 
 1.  ` 데이터 셋 `: https://dacon.io/competitions/open/235576/data
 2.  ` 전처리 기법`: 결측치 처리 - IterativeImputer, 이상치 처리 - IQR, 더미변수 추가, Polynomial 사용한 변수 중요도 조정
 3.  ` 학습 모델`: ScikitLearn - ExtraTreesRegressor
 4.  ` 하이퍼 파라미터 튜닝`: Optuna 사용

## 프로젝트 진행 일정  
|   주차   |   일정   |   내용   |   과제 및 논의   |   비고   |
|:----------------------------|:----------------------------:|:--------------------:|:-------------------:|:-----------------:|
|  1주차  | 2021.08.05 | EDA 및 데이터 전처리 | 각자의 EDA 진행 후 향후 방향 논의 | |
|  2주차  | 2021.08.12 | 데이터 전처리 | 결측치, 이상치 제거 방법 논의 및 실습 | |
|  3주차  | 2021.08.19 | 모델 선정 | 방학 세션간 배운 모델들에 데이터 학습 진행 | | 
|  4주차  | 2021.08.26 | 하이퍼파라미터 튜닝 | GridSearchCV, Optuna 등 이용, 하이퍼파라미터 계산 | |
|  5주차  | 2021.09.02 | 최종발표 | | [PPT](https://github.com/KU-BIG/KUBIG_2021_FALL/blob/main/2.%20KUBIG%20Contest/1.%20ML/3%EC%A1%B0/%E1%84%86%E1%85%A5%E1%84%89%E1%85%B5%E1%86%AB%E1%84%85%E1%85%A5%E1%84%82%E1%85%B5%E1%86%BC3%E1%84%8C%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%20ppt%20(1).pdf) | 
