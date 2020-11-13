# spotify famous song
‘test1’은 2018년 발매된 곡 중 Spotify 인기 곡을 뽑아 그 특성을 기술한 데이터입니다.<br>
<br>
(기본 전처리)<br>
‘artists’ 값이 없는 데이터를 제거하시오.<br>
<br>

1. 가수별로 등록된 곡수를 집계해보고, 5곡 이상의 인기곡을 보유한 가수들을 출력 하시오.
2. Valence 값이 0.5 이상인 곡들에 대해 Danceability와 Energy 변수 간 피어슨 상관계수를 출력하시오.
3. ‘danceability’, ‘energy’, ‘loudness’, ‘speechiness’, ‘acousticness’, ‘instrumentalness’, ‘liveness’, ‘valence’, ‘tempo’ 의 9개 변수를 사용해 ‘duration_ms’를 예측하는 다중선형회귀 모델을 생성하시오. (학습 데이터는 100 개의 데이터를 모두 사용할 것)
4. 가수별로 ‘danceability’, ‘energy’, ‘loudness’, ‘acousticness’, ‘tempo’, ‘duration_ms’ 6개 변수의 평균값을 집계 후 해당 데이터를 이용하여 K-means Clustering 기법으로 5개 군집으로 분류하시오. 또한 군집 분석 결과 aritist명 ‘Sam Smith’와 같은 군집에 속한 가수들을 출력하고, 이 가수들의 Normalized 된 평균 Danceability 값의 합을 출력하시오. (Normalization은 Min-Max Scaling 이용)