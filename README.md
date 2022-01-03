# housing_predict
<html>
	<head>
		<meta charset="utf-8"/>
		<title>房價預測</title>
	</head>
	
	<body>
		<h1>房價預測</h1>
		<h3>房屋特色</h3>
		<form action="/submit" method="post">
			<!-- <select name="feature1"> -->
				<!-- <option value="1"/>1 -->
				<!-- <option value="2"/>2 -->
				<!-- <option value="3"/>3 -->
			<!-- </select> -->
			<!-- <select name="feature2"> -->
				<!-- <option value="1"/>1 -->
				<!-- <option value="2"/>2 -->
				<!-- <option value="3"/>3 -->
			<!-- </select> -->
			<!-- <select name="feature3"> -->
				<!-- <option value="1"/>1 -->
				<!-- <option value="2"/>2 -->
				<!-- <option value="3"/>3 -->
			<!-- </select> -->
			<div class="box">地上居住面積</div>
			<input name="GrLivArea" type="text"></input>
			<label name="GrLivArea" type="text"></label>
			<div>地下室總面積</div>
			<input name="TotalBsmtSF" type="text"></input>
			<label name="TotalBsmtSF" type="text"></label>
			<div>建造年份</div>
			<input name="YearBuilt" type="text"></input>
			<label name="YearBuilt" type="text"></label>
			<div>整體房屋品質</div>
			<input name="OverallQual" type="text"></input>
			<label name="OverallQual" type="text"></label>
			<div>車庫車位</div>
			<input name="GarageCars" type="text"></input>
			<label name="GarageCars" type="text"></label>
			<div>一樓面積</div>
			<input name="1stFlrSF" type="text"></input>
			<label name="1stFlrSF" type="text"></label>
			<div>全套衛浴</div>
			<input name="FullBath" type="text"></input>
			<label name="FullBath" type="text"></label>
			<input type="submit" value="送出">
		</form>
	</body>	
</html>
