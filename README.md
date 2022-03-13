# 대출 사기 위험도 측정 모델 및 파이프라인 구축 PoC
kaggle lending club 데이터 기반 대출 사기 위험도 측정 모델 및 준실시간 예측(5분단위 배치) 파이프라인 구축 프로젝트입니다.



## MODELING
<ol style="list-style-type:decimal" start="0">                       
0. <a href="https://seulbiso.github.io/fraud-scoring-model-PoC/Modeling/0. 데이터 전처리.html">데이터 전처리</a><br>
1. <a href="https://seulbiso.github.io/fraud-scoring-model-PoC/Modeling/1. 변수 선정.html">변수 선정</a><br>
2. <a href="https://seulbiso.github.io/fraud-scoring-model-PoC/Modeling/2. 모델 선정.html">모델 선정</a><br>
3. 하이퍼파라미터 최적화<br>
  <ol style="list-style-type:decimal" start="1">
  3-1. <a href="https://seulbiso.github.io/fraud-scoring-model-PoC/Modeling/3-1. 하이퍼파라미터 최적화_그리드서치(LightGBM).html">하이퍼파라미터 최적화_그리드서치(LightGBM)</a><br>
  3-2. <a href="https://seulbiso.github.io/fraud-scoring-model-PoC/Modeling/3-2. 하이퍼파라미터 최적화_베이지안(LightGBM).html">하이퍼파라미터 최적화_베이지안(LightGBM)</a><br>
  3-3. <a href="https://seulbiso.github.io/fraud-scoring-model-PoC/Modeling/3-3. 하이퍼파라미터 최적화_베이지안(Catboost).html">하이퍼파라미터 최적화_베이지안(Catboost)</a><br>
  3-4. <a href="https://seulbiso.github.io/fraud-scoring-model-PoC/Modeling/3-4. 하이퍼파라미터 최적화_베이지안(Xgboost).html">하이퍼파라미터 최적화_베이지안(Xgboost)</a><br>
  </ol>
</ol>

## PIPELINE
<ol style="list-style-type:decimal" start="0"> 
0. <a href="https://seulbiso.github.io/fraud-scoring-model-PoC/Pipeline/0. 사전 준비.html">사전 준비</a><br>
1. <a href="https://seulbiso.github.io/fraud-scoring-model-PoC/Pipeline/1. 초기설정.html">초기설정</a><br>
  <ol style="list-style-type:decimal" start="1">
  1-1. <a href="https://seulbiso.github.io/fraud-scoring-model-PoC/Pipeline/1-1. 테이블 생성.html">테이블 생성</a><br>
  1-2. <a href="https://seulbiso.github.io/fraud-scoring-model-PoC/Pipeline/1-2. 모델 로드.html">모델 로드</a><br>
  </ol>
2. <a href="https://seulbiso.github.io/fraud-scoring-model-PoC/Pipeline/2. 예측 파이프라인.html">예측 파이프라인</a><br>
  <ol style="list-style-type:decimal" start="1">
    2-1. <a href="https://seulbiso.github.io/fraud-scoring-model-PoC/Pipeline/2-1. DakeLake(T0) 수집.html">T0 수집</a><br>
    2-2. <a href="https://seulbiso.github.io/fraud-scoring-model-PoC/Pipeline/2-2. Mart(T1) 전처리.html">T1 전처리</a><br>
    2-3. <a href="https://seulbiso.github.io/fraud-scoring-model-PoC/Pipeline/2-3. 예측.html">예측</a><br>
  </ol>
</ol>
