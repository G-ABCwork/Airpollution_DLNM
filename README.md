# [학술연구] 빅데이터를 이용한 미세먼지 건강영향평가
- 발주기관: 질병관리청
- 수행기관: 가천대 길병원 가천의생명융합연구원 인공지능빅데이터융합센터
- Distributed lag non linear model을 이용하여 상대위험도(relative risk, RR)를 기반으로 대기오염원 건강영향평가를 수행합니다.
- 2016-2020년 대도시별 질환 입원, 발생에 관한 6종의 대기오염원 건강영향평가를 수행합니다.
- 2016-2019년과 코로나19 이후 시기인 2020년 간의 대기오염원 건강영향평가 비교를 수행합니다.

## 평가 질환

-   신경과 질환
-   정신과 질환
-   안과 질환
-   호흡기 질환

## 분석 방법론

-   Distributed lag non linear model
    -   [스터디 노트](https://github.com/be-favorite/Paper_archive)

## 분석 툴
### SAS SQL
- 주요 프로시저: SQL
### R
- 주요 라이브러리: tidyverse, fpp3, dlnm, foreach, parallel, furrr, tidytext

## 데이터

-   건강보험공단 빅데이터 맞춤형 연구DB
-   에어코리아 대기오염원 DB
-   우리나라 휴일 정보 OPEN API
-   [에어코리아 대기오염원 DB, 우리나라 휴일 정보 OPEN API 데이터 제공](https://github.com/G-ABCwork/Data_Useful)

## 분석 결과 예시
- 데이터 및 연구 프라이버시를 고려하여 질환명은 마스킹하여 제공합니다.

<p align="center">
<img src = "./Figure for portfolio/merged_figure.png" width = "600"> 
</p>
