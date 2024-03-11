## 1일차 학습

### 빅데이터 학습
##### VS Code 문제확인
1. Jupyter Notebook 실행 속도 느려지는 문제 -> Pylance와의 충돌
    - Ctrl + ,(설정) > Jupyter > Logging: Level -> off or Verbose로 변경(debug 기본값)
2. Intellisense로 느려짐
    - Ctrl + ,(설정) > TypeScript, Editor > Suggest 모두 해제
    - 필요한 것만 체크해서 사용


- #### 빅 데이터 개요
    - ##### 정의
        * 디지털 환경에서 발생하는 대규모의 데이터
        * 대량의 데이터를 수집, 저장, 관리 분석하는 하드웨어/소프트웨어, 유통과 활용까지 포함

    - ##### 특징
        * [빅데이터 특징 3V,5V,7V](https://velog.io/@garam/DE-%EB%B9%85%EB%8D%B0%EC%9D%B4%ED%84%B0%EC%9D%98-%ED%8A%B9%EC%A7%953V-5V-7V) 설명 링크

    - ##### 기술
        * 데이터 생성 -> 수집 -> 저장 -> 분석(EDA,머신러닝, 딥러닝) -> 표현(시각화)

        * 생성 : IoT, 빅데이터 플랫폼
        * 수집 : 빅데이터 플랫폼 (ex : 하둡, Kafka etc)
        * 저장 : 빅데이터 플랫폼 (ex : Kafka etc)
        * 분석, 표현 : 통계, 머신러닝, 딥러닝, 자연어처리, 패턴인식, 이미지 프로세싱(ex : Spark,Power BI, Tablueau etc)
        * 표현 : Visualization (ex : Power BI, Tablueau etc)

- #### 학습교재
    - ##### 직장인을 위한 데이터 분석 실무 파이썬, 위키북스
        * 실습 자료 : https://github.com/Play-with-data/datasalon/tree/master

- #### 데이터 분석 기초
    - ##### 데이터 분석을 위한 라이브러리 학습

        - ###### Pandas(데이터 처리 라이브러리)
        - ###### Numpy(수치해석, 계산용 라이브러리)
        - ###### openpyxl(Excel,csv,JSON용 라이브러리)
        - ###### Selenium(웹 크롤링 자동화 라이브러리)
        - ###### BeautifulSoup(웹 데이터 정제 라이브러리)
        - ###### Matplotlib(차트 표현 라이브러리)
        - ###### Seaborn(시각화 라이브러리)
        - ###### Folium(지도 시각화 라이브러리)
        - ###### TensorFlow(머신러닝 라이브러리)
        - ###### PyTorch(머신러닝,딥러닝 라이브러리)
        - ###### Kaggle.com (데이터 분석 및 머신러닝에 대한 학습 플랫폼이자 경쟁할 수 있는 플랫폼)

- #### Pandas 학습
    - 데이터 분석(로딩, 처리) 라이브러리

    1. Pandas 자료구조

        ![자료구조](https://raw.githubusercontent.com/KangJeongTaek/bigdata-analysis-2024/main/images/ba001.png)

    2. 데이터 프레임, 시리즈

        - [데이터프레임 사용법](https://github.com/KangJeongTaek/bigdata-analysis-2024/blob/main/day01/da01_pandas_basic.ipynb)

    3. 데이터 통합(merge,append)

