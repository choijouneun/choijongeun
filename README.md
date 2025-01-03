# Hi there 👋
## Hi there! I'm choi jong eun.
I am a new data analyst who is interested in deriving insights through data analysis.⌨

We will always do our best without stopping to develop.🔥
## My skills
![RStudio](https://img.shields.io/badge/RStudio-4285F4?style=for-the-badge&logo=rstudio&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![SPSS](https://img.shields.io/badge/SPSS-217346?style=for-the-badge&logo=SPSS&logoColor=white)

## Contect
- 데이터분석 프로젝트
- 머신러닝 프로젝트


## My Project

### 데이터분석

<details>
<summary> <b> 노인복지시설 최적입지선정</b></summary><br>
 
<p align="left">
  <img src=https://github.com/user-attachments/assets/6bdf4cfb-3a0f-441b-9043-905ecfd78bce width = "630px">
<p align="left">
  <img src=https://github.com/user-attachments/assets/98e14786-fe96-45ee-9498-7fcd0c6bd16b width = "630px"> 
<p align="left">
  <img src=https://github.com/user-attachments/assets/7ea66a70-fda6-4217-9862-df88d5173c0f width = "630px">

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
   - [노인복지시 heatmap](https://github.com/choijouneun/choijongeun/blob/%EB%85%B8%EC%9D%B8%EB%B3%B5%EC%A7%80%EC%8B%9C%EC%84%A4/%EB%85%B8%EC%9D%B8%EB%B3%B5%EC%A7%80%EC%8B%9C%EC%84%A4%EA%B0%9C%EC%88%98%20heatmap.png)
   - [부동산시세 heatmap](https://github.com/choijouneun/choijongeun/blob/%EB%85%B8%EC%9D%B8%EB%B3%B5%EC%A7%80%EC%8B%9C%EC%84%A4/%EB%B6%80%EB%8F%99%EC%82%B0%EC%8B%9C%EC%84%B8%20heatmap.png)
   - [노인인구 heatmap](https://github.com/choijouneun/choijongeun/blob/%EB%85%B8%EC%9D%B8%EB%B3%B5%EC%A7%80%EC%8B%9C%EC%84%A4/%EB%85%B8%EC%9D%B8%EC%9D%B8%EA%B5%AC%20heatmap.png)
   - [대중교통편의지수 heatmap](https://github.com/choijouneun/choijongeun/blob/%EB%85%B8%EC%9D%B8%EB%B3%B5%EC%A7%80%EC%8B%9C%EC%84%A4/%EB%8C%80%EC%A4%91%EA%B5%90%ED%86%B5%ED%8E%B8%EC%9D%98%EC%A7%80%EC%88%98%20heatmap.png)

</details>


<details>
<summary> <b> 프로야구 투수 연봉예측 회귀분석</b></summary><br>
 
 * 분석 배경
   * 프로야구 선수들은 매년 연봉 책정을 다시하게 되는데 본인의 연봉이 얼마로 책정될지 미리 알고있으면 연봉 협상에 있어서 주도권을 가질 수 있다고 판단하여 분석을 진행하였습니다.
 
 * 분석툴
   * 미니탭
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
   - [프로야구투수연봉예측 프로젝트](https://github.com/choijouneun/choijongeun/blob/%ED%94%84%EB%A1%9C%EC%95%BC%EA%B5%AC-%ED%88%AC%EC%88%98-%EC%97%B0%EB%B4%89%EC%98%88%EC%B8%A1/%ED%94%84%EB%A1%9C%EC%95%BC%EA%B5%AC%20%ED%88%AC%EC%88%98%20%EC%97%B0%EB%B4%89%EC%98%88%EC%B8%A1.pdf)
</details>


<details>
<summary> <b> 카카오톡 텍스트분석을 통한 생활습관개선</b></summary><br>
  
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
   - [텍스트분석 파이썬코드](https://github.com/choijouneun/choijongeun/blob/%EC%B9%B4%EC%B9%B4%EC%98%A4%ED%86%A1-%EB%8C%80%ED%99%94%EB%B6%84%EC%84%9D%EA%B8%B0/kakaotalk%20text%20analysis.ipynb)
   - [워드클라우드 파이썬코드](https://github.com/choijouneun/choijongeun/blob/%EC%B9%B4%EC%B9%B4%EC%98%A4%ED%86%A1-%EB%8C%80%ED%99%94%EB%B6%84%EC%84%9D%EA%B8%B0/wordcloud.ipynb)
</details>
___
### 머신러닝 프로젝트

#### 1. 새로운 AWS 교육 서비스를 진행하기 위한 자료 수집과 분석
* 분석 배경
  * 천재교육이 이번년도  aws공인교육자격증을 얻어 aws교육시장에 진출하려해, aws관련직무를 뽑는 회사에 대한 정보를 수집하기위해 분석을 진행하였다.

* 분석툴
  * 파이썬

* 분석절차
  1. 데이터 수집: 랠릿,원티드,프로그래머스,유데미,
  2. 데이터 전처리: 추출된 데이터프레임을 분석이 가능하도록 전처리를 진행한다.
  3. 데이터 분석: 경력(신입, 주니어, 미들, 시니어)별로 기술스택에 차이가있나, 기업형태(중소기업, 중견기업, 대기업)별로 기술스택에 차이가 있나
  4. 결론
      - 대기업과 중견기업의 요구 기술스택 차이만이 95% 유의수준에서 유의하지 않았고, 중소기업과 대기업, 중소기업과 중견기업의 차이는 유의한 것으로 나타나, 중소기업에서 대기업이나 
          중견기업으로 이직 혹은 취직을 노리는 교육생에게 교육을 진행할 기술스택의 우선순위를 달리 하는 것이 타당하다는 결론을 내렸다
      - 신입, 주니어, 미들, 시니어 네 경력 분류에 대해 모든 비교 결과가 95% 유의수준에서 유의하였다. 즉, 요구하는 경력 별로 요구하는 기술 스택의 차이가 있는 것으로 밝혀졌다.
      -  
  6. 기대효과:경력별로 다르게 타겟을 정해 강의커리큘럼을 정하거나 중소기업->(중견,대)기업으로 이직을 희망하는 사람들을 타겟으로 강의커리큘럼을 만들어 수익을 올릴 수 있다.

* 분석결과
  - 대기업과 중견기업의 요구 기술스택 차이만이 95% 유의수준에서 유의하지 않았고, 중소기업과 대기업, 중소기업과 중견기업의 차이는 유의한 것으로 나타나, 중소기업에서 대기업이나 
  중견기업으로 이직 혹은 취직을 노리는 교육생에게 교육을 진행할 기술스택의 우선순위를 달리 하는 것이 타당하다는 결론을 내렸다
  - 신입, 주니어, 미들, 시니어 네 경력 분류에 대해 모든 비교 결과가 95% 유의수준에서 유의하였다. 즉, 요구하는 경력 별로 요구하는 기술 스택의 차이가 있는 것으로 밝혀졌다.

* 프로젝트 한계점
  - 아직 통계분석에 대한 많은 이해를 하지못해 많은 가설검정을 하지 못했다.
  - 시간관계상 데이터 전처리하는 부분에 있어 제대로 못한것이 아쉬웠다.

* 파이썬 코드
  - [분석보고서](https://github.com/choijouneun/choijongeun/blob/bigdata7%EA%B8%B0-crawing-_project/%EB%B9%85%EB%8D%B0%EC%9D%B4%ED%84%B0%207%EA%B8%B0%2024.03.05%20%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%20%EB%B6%84%EC%84%9D%20%EB%B3%B4%EA%B3%A0%EC%84%9C%20%EC%86%A1%EC%A7%80%ED%99%98%2C%20%EC%B5%9C%EC%A2%85%EC%9D%80%2C%20%EA%B9%80%EC%88%98%EC%A7%84%2C%20%EC%9D%B4%EB%AF%BC%EC%95%84.docx)
  - [crawing_project ppt](https://github.com/choijouneun/choijongeun/blob/bigdata7%EA%B8%B0-crawing-_project/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%20ppt.pptx)
  - [파이썬코드](https://github.com/choijouneun/choijongeun/blob/bigdata7%EA%B8%B0-crawing-_project/crawling_project_code_final.ipynb)

____


#### 2. (캐글) 타이타닉 머신러닝 랜덤포레스트
* 분석 배경
  * 타이타닉의 데이터를 통해 데이터전처리에 대한 부분과 이것을 어떻게 활용하는지에 대한 공부와 머신러닝에 대한 이해를 돕고자 시작하게됐다.

* 분석툴
  * 파이썬
    - pandas, sklearn 패키지를 활용해 데이터 분석
    -  matplotlib, seaborn패키지를 활용해 데이터를 시각화

* 분석절차
  1. 데이터 수집: kaggle
  2. 데이터 전처리: train 데이터와 test데이터의 결측치를 확인하여 결측치가 너무 많고 필요가 없는 정보들은 삭제하고, 쓸만한 데이터는 다른변수들과의 분석을 통해 나온 평균값이나 결측치가 있는 변수의 최댓값, 평균값을 통하여 결측치를 대체하였다.  SibSp 와 Parch 변수를 합쳐서 FamilySize 라는 변수를 새로 만들었다. 범주형데이터들은 더미변수로 바꿔주어 분석에 오류가 나는것을 방지했다.
  3. 데이터 분석: sklearn 패키지를 이용하여 랜덤포레스트로 train 데이터의 독립변수와 종속변수를 두고 학습시켰다. 이것을 바탕으로 test데이터의 생존률을 예측하여 생존률이라는 값을 나타냈다
  4.결론: 예측률은 86 % 높은 예측치가 나왔다 test 데이터의 생존율 또한 35.16으로 train 데이터의 생존율인 38.3%와 많은 차이를 나타내지 않는다.
  5. 기대효과: 이러한 머신러닝을 연습하여 숙지함으로써 실무에 나갔을 때 데이터를 전처리하는 법 어떤 상황에서 랜덤 포레스트를 써야 하는지에 대한 기술을 습득할 수 있습니다


* 분석결과
  - 예측률 86% 

* 프로젝트 한계점
  - kaggle에서 제시해준 데이터라 실무에 있는 데이터들과는 다르게 전처리하기 편하다는 점으로 실무를 경험해보기엔 다소 아쉬웠다.
  - 아직은 데이터 전처리에 대한 부분에 경험을 많이 해보지 못하여 결측치가 많거나 정보가 필요 없다고 생각한 것은 삭제하였지만 경험이 더 풍부했다면 이러한 정보들도 쓸 수 있었을 거 같아 아쉽다. 


 * 파이썬 코드
 - [타이타닉 파이썬코드] 
(https://github.com/choijouneun/choijongeun/blob/main/(%EC%BA%90%EA%B8%80)%ED%83%80%EC%9D%B4%ED%83%80%EB%8B%89_%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D_.ipynb)

___

#### 3. 당뇨병 환자 분류

- 분석 배경
    - 환자들에 대한 데이터를 입력하면 이 환자가 당뇨병인지 아닌지 판별할 수 있는 머신러닝으로 사람들이 굳이 검사를 하지 않고도 당뇨병 자가진단을 할 수 있지 않을까 생각되어 분석을 진행하게됐습니다.
- 분석툴
    - 파이썬
        - plt와sns를 활용해 시각화를 하였다.
        -  라벨 인코딩을 통해 범주형 데이터를 라벨링 하였다.
        -  수치형 변수들은 정규화를 해줬다.
        -  1(당뇨병)인 사람이 0(정상)인 사람에 비해 데이터 값이 현저히 적어 오버샘플링 후 랜덤포레스트를 해줌
           

- 분석절차
    1. 데이터 수집: kaggle
    2. 데이터 전처리: 
        1. 성별의 결측치를 남녀 비율에 맞게 나눠줌 
        2.  흡연여부에서 결측치를 고혈압과 혈당을 이용하여 최빈값으로 결측치를 채워줬다. 
        3. 흡연여부를 다른 범주로 나눠줬다.
    3. 데이터 분석: 랜덤포레스트를 사용하여 머신러닝
    4. 결론: 최적값이 약 97%로 상당히 높게 나왔다
    5. 기대효과: 환자들이 굳이 당뇨병 검사를 하지 않고도 데이터만 넣어서 그 값으로 당뇨병을 판단하여 검사비를 아낄 수 있다.

- 분석결과
    - 예측값이 96.41%로 상당히 높게 나왔다
    - 0(정상)을 예측하는것은 99% ,1(당뇨병)환자를 예측하는것 또한 72%가 나왔다.
    
- 프로젝트 한계점
    - 데이터전처리에서 성별에 대한 부분은 18개로써 10만개의 데이터 중에서 0.001%로 그냥 삭제하고 진행해도 무방했을꺼같다.
    - 흡연여부 결측치에서 또한 아직 데이터전처리에 대한 부분이 미숙하여 제대로 하지 못한거같아 아쉬웠다.


 * 파이썬 코드
 - [당뇨병환자 예측 파이썬 코드] (https://github.com/choijouneun/choijongeun/blob/main/%EB%8B%B9%EB%87%A8%EB%B3%91%ED%99%98%EC%9E%90_%EC%B5%9C%EC%A2%85%EC%9D%80.ipynb)
  

