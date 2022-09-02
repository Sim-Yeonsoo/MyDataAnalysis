# 2022년 나의 데이터 분석
 2022년 데이터에 대한 분석 내용 정리
 
 -----
<br>


## [Kaggle 데이터 분석해 보기]
<br>

<div align="center">
	<h2 align="center"> 🌾 Paddy Doctor: Paddy Disease Classification</h3>
	<img src="https://raw.githubusercontent.com/paddydoc/paddydoc.github.io/main/assets/img/paddy-disease-farmer.jpg" width=500> <br><br>
	<p> 데이터 참조 : https://www.kaggle.com/competitions/paddy-disease-classification</p>
</div>
<br>

  * 내용 : 대회에서 제공하는 데이터셋을 EDA, 기본 모델을 만들어보고 모델 평가까지 해본다.
    * EDA [html]
	  * 기본 모델 만들기 [html]()
	  * 모델 평가 [html]()
	  <br>
	<br>
-----
<br>


<div align="center">
	<h2 align="center"> 🧭 American Express - Default Prediction</h3>
	<img src="https://thumbs.dreamstime.com/b/american-express-amex-platinum-marriott-rewards-card-white-table-american-express-amex-platinum-card-marriott-hotels-155218226.jpg" width=500> <br><br>
	<p> 데이터 참조 : https://www.kaggle.com/competitions/amex-default-prediction/overview</p>
</div>
<br>

  * 내용 : 대회에서 제공하는 데이터셋을 EDA, 기본 모델을 만들어보고 모델 평가까지 해본다.
    * EDA [html]
	  * 기본 모델 만들기 [html]()
	  * 모델 평가 [html]()
	  <br>
	<br>
-----
<br>
<br>

	  
## [DACON 데이터 분석해 보기]
<br>

<div align="center">
	<h2 align="center"> 🍷 와인 품질(Quality) 분류 경진대회</h3>
	<img src="https://sim-yeonsoo.github.io/MyDataAnalysis/Wine_Quality/wine_pic.jpg" width=500> <br><br>
	<p> 데이터 참조 : https://dacon.io/competitions/open/235610/overview/description</p>
</div>
<br>
  
  * 내용 :  와인 성분 데이터에 대해 EDA, 기본 모델을 만들어보고 모델 평가까지 해본다.

	  * 🚩 EDA
		* 'index' 컬럼 삭제
		* 'type' 변수의 데이터타입이 문자 -> 라벨인코딩 진행
		* 'density' 변수와 'quality' 간의 상관관계가 없어보임 -> 'density' 변수는 모델링에서 제거

	  * 🚩 기본 모델 만들기
		* ensemble 모델, LogisticRegression
		* RandomForestClassifier 선택
	  * 🚩 모델 평가
		* 교차검증
		
	[<p align="center">:computer: Notebook 코드](https://github.com/Sim-Yeonsoo/MyDataAnalysis/blob/main/Wine_Quality/Wine_Quality_EDA.ipynb)
	[<p align="center">📑 html 변환 코드](https://sim-yeonsoo.github.io/MyDataAnalysis/Wine_Quality/Wine_Quality_EDA.html)

  
  * ~~flask를 이용한 웹 서비스 구현~~
