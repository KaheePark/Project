### Project description

### 주제
라이브커머스 피드백 개선을 위한 채팅문장 분석 대시보드 구축


### 기간
2022년 4월 4일 ~ 6월 15일


### 구성요소

|구분|도구명|버전|
|:---:|:---:|:---:|
|개발환경|Linux|Ubuntu 18.04|
||Python|3.8|
||Azure Virtual Machine|
|사용 Tool|Pandas|1.1.5|
||Tensorflow|2.2|
||Pytorch|1.11|
||Keras|2.8|
||Scikit-learn|0.22.1|
||Docker|20.10.14|
||Kafka|2.8.1|
||Spark|3.1.2|
||Logstash|8.1.2|
||MongoDB|5.0.8|
||InfluxDB|1.7|
||Django||
||Grafana|8.2.0|
||Git/ Git-flow||
||Visual Studio Code||
||Airflow|1.10.7|



### 주요 역할 및 활동 (인원: 총 5명)
#### 1. 데이터 파이프라인 구축
- Docker 기반 시스템 설계
- Kafka, Spark, Logstash, MongoDB, InfluxDB, Airflow 파이프라인 구축

#### 2. 문장 분석 모델 개발 및 적용
- 모델을 학습할 채팅 데이터셋, 댓글/리뷰 데이터셋 수집 및 전처리
- 머신러닝, 딥러닝 모델 개발 (KoBERT, BERT, LSTM, BiLSTM, CNN...)
- 하이퍼 파라미터 튜닝 및 분석 모델 고도화

#### 3. 실시간 데이터 시각화
#### 4. 파이프라인 모니터링
- Grafana, Django로 대시보드 구현 및 파이프라인 모니터링


### 맡은 파트

```
1. Airflow docker 이미지 빌드 및 DAGs 파일 생성
2. 비속어 분류 머신러닝 모델 생성
```


