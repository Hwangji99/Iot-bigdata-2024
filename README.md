# Iot-bigdata-2024
2024년 IoT 개발자 과정 빅데이

## 1일차(2024-08-01)
### 빅데이터 분석 및 AI
- 빅데이터를 사용하여 사회의 전반적인 문제, 현상, 원인, 해결점 등을 찾아가는 분석방법 
- 사회전반에 모든 곳에서 활용
- 예: 쿠팡에 20대 중반 여자들이 선호하는(트렌드) 화장품
    1. 쿠팡에 20대 중반 여자 - 회원정보를 검색
    2. 회원들이 검색한 내용 중 화장품을 조회
    3. 그 중에서 가장 많이 검색된 화장품 통계
    4. 20대 중반 여자 회원이 로그인
    5. 첫화면에 검색된 화장품 1위 ~ 3위를 디스플레이(사세요~!!) - 빅데이터 분석 마케팅에 적용

- 빅데이터?
    - Big Data - 디지털 환경에서 발생하는 대규모 정형 또는 비정형 데이터
    - 3V - Volumn(데이터 크기, 규모), Variety(다양성), Velocity(속도)
    - 5V - 3V + Veracity(진실성), Value(가치)
    - 7V - 5V + Validity(정확성), Volatility(휘발성 : 데이터가 얼마나 오래 저장되느냐)

- 데이터냐?
    - 정보를 수집자료 자체, 값, 총계 + Value -> 정보(Information)

- 빅데이터 분석 순서 : 생성 -> 수집 -> 저장 -> 분석 -> 표현
    1. 생성 - IoT 센싱값, (쇼핑몰, 포털) 빅데이터 플랫폼을 통해서 생성
    2. 수집 - MQTT로 DB에 저장, 빅데이터 플랫폼(하둡, 카프카..)에서 수집, 크롤링, 네트워크까지 포함
    3. 저장 - 수집과 거의 동일, DB에 저장(카프카, 데이터마이닝, NoSQL..)
    4. 분석 - 통계적 분석, 탐색적 분석(EDA), 머신러닝, 딥러닝, 자연어처리, 이미지 프로세싱, 분석툴(Spark, Tableau, MS PowerBI) 사용
    5. 표현 - 인사이트 도출(시각화, 그리드)

- 데이터 분석 기초
    - 파이썬 - 외 R, 자바, C# 등 다른 언어로도 분석가능. 단, 파이썬이 가장 쉽기 때문에 많이 사용
    - 데이터 분석에 들어가는 라이브러리(모듈)부터 학습
        1. 데이터 처리 - Numpy(수치해석, 계산), Pandas(데이터처리), Scipy(과학계산) ...
        2. 시각화 - Folium(지도), Matplotlib(차트), Seaborn(Matplotlib 고급화) ...
        3. 엑셀 - openpyxl(엑셀 처리)
        4. 크롤링 - Selenium(웹 크롤링 자동화), BeautifulSoup(웹페이지 정제)
        5. 머신러닝/딥러닝 - Script-Learn(가장 간단한 머신러닝), MS CNTK, Theano, Keras(최초의 딥러닝), TensoFlow(제일 유명, Keras 포함), PyTorch(페이스북)

- 빅데이터 학습
    - 실습자료, 빅데이터 분석 기초학습
    - [넘파이](https://github.com/Hwangji99/Iot-bigdata-2024/blob/main/day01/bda01_numpy_basic.ipynb)
    - [판다스](https://github.com/Hwangji99/Iot-bigdata-2024/blob/main/day01/bda02_pandas_basic.ipynb)
    - [맷플롭립](https://github.com/Hwangji99/Iot-bigdata-2024/blob/main/day01/bda03_matplotlib_basic.ipynb)

## 2일차(2024-08-02)
- 빅데이터 학습
    - 기초학습, 크롤링 관련
    - 셀레니움 + 뷰티풀수프 같이 진행
    - [뷰티플수프](https://github.com/Hwangji99/Iot-bigdata-2024/blob/main/day02/bda04_beautifulsoup_basic.ipynb)
    - [셀레니움](https://github.com/Hwangji99/Iot-bigdata-2024/blob/main/day02/bda05_selenium_basic.ipynb)

- 빅데이터 실습
    - 스타벅스 입지 분석
    - [스벅입지분석](https://github.com/Hwangji99/Iot-bigdata-2024/blob/main/day02/bda06_starbucks_analysis.ipynb)

## 3일차(2024-08-05)
- 개인 토이 프로젝트
    - 깃허브 리포지토리, 빅데이터, 머신러닝, 딥러닝 레퍼런스를 참조 -> 클로닝 형태
    - 리포지토리 10개 정도 리스트업 또는 리포지토리 검색해서 진행

- 빅데이터 실습
    - 스타벅스 입지 분석 (계속)
    - 지난주 최종으로 만든 데이터 csv파일 다시 로드
    - [스타벅스입지분석](https://github.com/Hwangji99/Iot-bigdata-2024/blob/main/day03/bda07_starbucks_analysis.ipynb)

- 빅데이터 활용방안
    - [자바2024](https://github.com/hugoMGSung/bigdata-analysis-2024)
    - [강사나머지교안](https://github.com/hugoMGSung/works-need-it-data-analysis)
    - [멀티캠퍼스서울2021](https://github.com/ckiekim/DataAnalysis-2021-3)
    - [위키북스_데이터분석실무](https://github.com/CityHopper/playwithdata)

    - 수집방법, 데이터 전처리, 분석/시각화 어떤 알맞은 방법을 쓰는지 선별
    - 단순 빅데이터 분석방법은 깃헙에서 참조만 해도 많을 것을 찾아볼 수 있음

- 빅데이터 분석가의 작업순
    1. 수집, 저장 동시 - 크롤링, OpenAPI, DB, 엑셀 다운로드...
    2. 데이터 전처리(핵심) - 자동화 어려움, 분석 일정 50%를 차지
    3. 분석 -> EDA/통계기반 분석, 머신러닝, 딥러닝 활용
    4. 시각화 - 경영진이 확인하고 비즈니스, 결정에 도움을 주기 위해서

- 일반적인 빅데이터 분석 예
    - 코로나 사태로 외국인 관광객 수 변경 추세
    - 인스타그램 크롤링으로 제주도 핫플레이스 시각화
    - 스타벅스 입지 분석
    - 다나와 크롤링으로 인기있는 무선청소기 순위 분석
    - 전국 휘발유 가격 인상현황

- 머신러닝, 딥러닝이 들어가면 예측, 예상
    - 이전에는 예측, 예상을 기존의 EDA 방식으로 사용했음
    - 머신러닝, 딥러닝이 예측값의 정확도가 훨씬 높기 때문에 사용

## 4일차(2024-08-06)
- 머신러닝, 딥러닝
    - 인공지능 개념 학습
    - 파이토치 기본설명과 CPU/GPU 라이브러리 설치
    - [개념](https://github.com/Hwangji99/Iot-bigdata-2024/blob/main/day04/bda08_ml_dl_concept.ipynb)
    - [파이토치개요및설치](https://github.com/Hwangji99/Iot-bigdata-2024/blob/main/day04/bda09_pytorch_start.ipynb)

## 5일차(2024-08-07)
- 머신러닝, 딥러닝
    - ML(Machine Learning) -> DL(Deep Learning) -> NLP(Natural Language Processing) ...
    - [파이토치기본](https://github.com/Hwangji99/Iot-bigdata-2024/blob/main/day05/bda10_pytorch_basic.ipynb)
    - 타이타닉 생존자 예측
    - [ML회귀분석](https://github.com/Hwangji99/Iot-bigdata-2024/blob/main/day05/bda11_linear_regression.ipynb)

## 6일차(2024-08-08)
- 머신러닝, 딥러닝
    - 타이타닉 생존자 예측(계속)
    - 사이킷런(로지스틱), 파이토치 생존자 예측 비교
    - [ML회귀분석](https://github.com/Hwangji99/Iot-bigdata-2024/blob/main/day05/bda11_linear_regression.ipynb)
    
## 7일차(2024-08-09)
- 머신러닝, 딥러닝
    - CNN(Convolution NN)
    - [이미지분류](https://github.com/Hwangji99/Iot-bigdata-2024/blob/main/day06/bda12_image_class.ipynb)

## 8일차(2024-08-12)
- 머신러닝, 딥러닝
    - 객체탐지(Object Detection)
    - OpenCV, Yolov8
    - [YOLOv8](https://github.com/Hwangji99/Iot-bigdata-2024/blob/main/day07/bda13_object_detection.ipynb)

    <img src="https://github.com/Hwangji99/Iot-bigdata-2024/blob/main/day07/20240812_151755471.jpg?raw=true" width="700">

    

    https://github.com/user-attachments/assets/d28676ed-d522-448a-b573-8a0e0cff9cdd



## 9일차(2024-08-13)
- 머신러닝, 딥러닝 개인 클로닝
    - 예제 리포지토리, Cloning
    
