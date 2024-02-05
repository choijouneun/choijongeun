# Hi there 👋
## Hi there! I'm choi jong eun.
I am a new data analyst who is interested in deriving insights through data analysis.⌨

We will always do our best without stopping to develop.🔥
## My skills
![RStudio](https://img.shields.io/badge/RStudio-4285F4?style=for-the-badge&logo=rstudio&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![SPSS](https://img.shields.io/badge/SPSS-217346?style=for-the-badge&logo=SPSS&logoColor=white)
## My Project

#### 1. 노인복지시설 최적입지선정
* 분석 배경
  * 점점 고령화 인구가 증가하면서 노인복지시설의 부족함으로 인한 문제가 대두되고 있어 노인복지시설 건축이 가장 시급한 지역을 알기 위해 분석을 진행하였습니다.

* 분석툴
  * 파이썬
    - pandas, geopandas 패키지를 활용해 데이터 분석
    - folium 패키지를 활용해 히트맵 시각화
  * SPSS
    - 군집분석을 위해 Elbow-Method, Silhouette 계수를 추출하여 최적 군집 수 결정
    - K-means, Gaussian, Agglomerlative 군집분석 진행

* 분석절차
  1. 데이터 수집: 공공데이터포털인 열린데이터광장과 빅데이터캠퍼스에서 노인 관련 데이터 수집
  2. 데이터 전처리: 법정동명을 행정동명으로 통일화, MIN-MAX 정규화를 통해 데이터 표준화
  3. 데이터 분석: 히트맵을 통해 행정동별 데이터 시각화 후 군집 분석 진행, 각각의 군집분석 결과의 교집합인 행정동을 최적입지로 선정
  4. 결론: 최적입지로 선정된 행정동 중 인구와 현재의 노인복지시설 개수를 고려하여 최종입지선정
  5. 기대효과: 점점 늘어날 것으로 추정되는 고령화 인구에 대비해 미리 노인복지시설을 건축하여 미래 노인의 삶의 질 향상

* 분석결과
  - 각각의 군집분석을 통해 추출된 행정동 중 교집합에 해당하는 21개 행정동 추출, 이 중 노인복지시설이 1개 이하인 행정동 9개를 추출하여 최적입지로 선정하였습니다.

* 프로젝트 한계점
  - 네 개의 노인복지시설을 모두 합한 후 분석을 진행하여 도출된 결과이기 떄문에 해당하는 행정동에 어떤 노인복지시설이 필요한지 모른다는 한계점
  - 분석에서 고려한 변수들로 최적입지를 선정하기엔 분석의 타당도가 떨어진다는 한계점
 
* 파이썬 코드
  - [히트맵 파이썬코드](https://github.com/choijouneun/choijongeun/blob/main/heatmap%20code.ipynb)
  - [노인복지시설개수 heatmap](https://github.com/choijouneun/choijongeun/blob/main/%EB%85%B8%EC%9D%B8%EB%B3%B5%EC%A7%80%EC%8B%9C%EC%84%A4%EA%B0%9C%EC%88%98%20heatmap.png)
  - [부동산시세 heatmap](https://github.com/choijouneun/choijongeun/blob/main/%EB%B6%80%EB%8F%99%EC%82%B0%EC%8B%9C%EC%84%B8%20heatmap.png)
  - [노인인구 heatmap](https://github.com/choijouneun/choijongeun/blob/main/%EB%85%B8%EC%9D%B8%EC%9D%B8%EA%B5%AC%20heatmap.png)
  - [대중교통편의지수 heatmap](https://github.com/choijouneun/choijongeun/blob/main/%EB%8C%80%EC%A4%91%EA%B5%90%ED%86%B5%ED%8E%B8%EC%9D%98%EC%A7%80%EC%88%98%20heatmap.png)

___

#### 2. 프로야구 투수 연봉예측 회귀분석
* 분석 배경
  * 프로야구 선수들은 매년 연봉 책정을 다시하게 되는데 본인의 연봉이 얼마로 책정될지 미리 알고있으면 연봉 협상에 있어서 주도권을 가질 수 있다고 판단하여 분석을 진행하였습니다.

* 분석툴
  * 미니텝
    - 상관분석을 통한 상관관계 확인
    - 회귀분석 진행

* 분석절차
  1. 데이터 수집: KBO기록실, STATIZE 에서 투수들의 성적 및 연봉 데이터 수집
  2. 데이터 전처리: 더미변수인 '투수 포지션' 을 기준으로 선수를 분류한 후 각각의 포지션에 부합하는 변수를 분류
  3. 데이터 분석: 다중공선성 문제를 예방하기 위해 상관분석을 통해 상관관계가 높은 변수를 제거한 후 회귀분석 진행
  4. 결론: 각 포지션 별 최종 회귀모형 도출, 실제 선수들의 연봉과 비교
  5. 기대효과: 선수들이 구단과의 연봉 협상에 있어서 주도권을 가질 수 있으며, 다른 구단과의 계약에 있어서도 큰 도움이 될 것이라 예상

* 분석결과
  - 최종 회귀모형을 도출하여 실제 선수들의 연봉과 비교해본 결과 80% 부합하는 것을 확인하였습니다.

* 프로젝트 한계점
  - 선수들의 성적과 연봉 외에는 다른 변수를 고려하지 않아 다른 외적 변수가 작용할 수 있다는 한계점 (ex: 나이, 성장가능성 등)
  - 각 구단의 제정 상태에 따라 책정되는 금액이 상이할 수 있다는 한계

* 프로젝트
  - [프로야구투수연봉예측 프로젝트](https://github.com/choijouneun/choijongeun/blob/main/%ED%94%84%EB%A1%9C%EC%95%BC%EA%B5%AC%20%ED%88%AC%EC%88%98%20%EC%97%B0%EB%B4%89%EC%98%88%EC%B8%A1.pdf)

___

#### 3. 카카오톡 텍스트분석을 통한 생활습관개선
* 분석 배경
  * 대한민국 사람들이 가장 많이 사용하는 '카카오톡'에 사람들의 생활습관 및 대화습관이 녹아있다고 생각하여 카카오톡 텍스트 분석을 통해 평소의 문제점을 확인하기 위해 분석을 진행하였습니다.

* 분석툴
  * 파이썬
    - numpy, pandas 패키지를 활용해 데이터 분석
    - matplotlib, seaborn, wordcloud 패키지를 활용해 데이터 시각화

* 분석절차
  1. 데이터 수집: '카카오톡 내보내기' 기능을 이용해 카톡방 텍스트 추출
  2. 데이터 전처리: 추출된 텍스트 파일을 엑셀을 활용하여 분석 가능하도록 전처리 진행
  3. 데이터 분석: 가장 활발히 대화가 이루어지는 시간, 대화 빈도수 등 분석 결과 도출
  4. 결론: 비속어 사용 빈도수, 시간 별 대화 빈도수 등을 통해 사람들의 안좋은 대화 및 생활습관 확인
  5. 기대효과: 분석을 통해 발견한 안좋은 대화 및 생활 습관을 개선함으로서 생활의 질 향상

* 분석결과
  - 대화가 가장 활발한 시간, 카톡 전송 횟수 등 다양한 데이터 분석을 통해 저를 포함한 팀원들이 늦은 시간까지 활동하는 것을 확인하였습니다.
  - 느낌표 사용 횟수, 자주 웃는 순위 등을 통해 팀원들의 SNS에서의 대화 습관을 확인하였습니다.

* 프로젝트 한계점
  - PC 카카오톡과 핸드폰 카카오톡의 내보내기 기능을 통해 추출받은 데이터의 양식이 다르고 저장되는 내용에 차이가 있어 따로 분석해야한다는 한계점
  - 워드클라우드의 큰 의미없는 단어를 모아놓는 불용어사전 제작 부분에서 사람들마다 사용하는 텍스트가 달라 표준화된 불용어사전 제작의 한계점

* 파이썬 코드
  - [텍스트분석 파이썬코드](https://github.com/choijouneun/choijongeun/blob/main/kakaotalk%20text%20analysis.ipynb)
  - [워드클라우드 파이썬코드](https://github.com/choijouneun/choijongeun/blob/main/wordcloud.ipynb)


