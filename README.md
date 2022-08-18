# 2022년 나의 데이터 분석
 2022년 데이터에 대한 분석 내용 정리


## [IRIS 데이터 분석해 보기]
  * 데이터 참조 : https://www.kaggle.com/datasets/uciml/iris
  * 이미지 
  * 내용 : 머신러닝 논문에 사용된 IRIS 데이터 셋에 대해 EDA, 기본 모델을 만들어보고 모델 평가까지 해본다.
    * IRIS EDA [html](https://sim-yeonsoo.github.io/MyDataAnalysis/IRIS_BASIC01.html)
	  * IRIS 기본 모델 만들기 [html]()
	  * IRIS 모델 평가 [html]()
	  <br>
	<br>
-----
<br>
	  
## [DACON 데이터 분석해 보기]

<div align="center">
	<h2 align="center"> 🍷 와인 품질(Quality) 분류 경진대회</h3>
	<img src="https://sim-yeonsoo.github.io/MyDataAnalysis/Wine_Quality/wine_pic.jpg" width=500>
</div>
<br>

  * 데이터 참조 : https://dacon.io/competitions/open/235610/overview/description <br>
  
  * 내용 :  와인 성분 데이터에 대해 EDA, 기본 모델을 만들어보고 모델 평가까지 해본다.
    * [Ipynb](https://github.com/Sim-Yeonsoo/MyDataAnalysis/blob/main/Wine_Quality/Wine_Quality_EDA.ipynb) [html](https://sim-yeonsoo.github.io/MyDataAnalysis/Wine_Quality/Wine_Quality_EDA.html)
	  * EDA
	  	* 'index' 컬럼 삭제
	  	* 'type' 변수의 데이터타입이 문자 -> 라벨인코딩 진행

	  * 기본 모델 만들기
	  	* ensemble 모델, LogisticRegression
	  	* RandomForestClassifier 선택
	  * 모델 평가
	  	* 교차검증
  
  * ~~flask를 이용한 웹 서비스 구현~~
