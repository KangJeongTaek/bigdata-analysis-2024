## 7일차 학습
### 빅데이터 학습

- #### 데이터 분석 실습
    - 스타벅스 입지 분석 [학습링크](https://github.com/KangJeongTaek/bigdata-analysis-2024/blob/main/day07/da16_스타벅스_매장_입지분석.ipynb)
        - 웹 크롤링으로 데이터 수집, 지도 시각화, 분석

            ![스타벅스 매장 위치 지도 시각화](https://raw.githubusercontent.com/KangJeongTaek/bigdata-analysis-2024/main/images/ba010.png)

            ![스타벅스 구별 서클 마커](https://raw.githubusercontent.com/KangJeongTaek/bigdata-analysis-2024/main/images/ba011.png)


        - 구별 스타벅스 매장 수와 구별 사업체수와 구별 인구수 비교 지도 시각화

            ![비교](https://raw.githubusercontent.com/KangJeongTaek/bigdata-analysis-2024/main/images/ba015.png)

        - 결론
            - 스타벅스는 인구수와 별개로 직장인이 많이 분포하는 구에 매장을 많이 오픈한다.

    
    - 무선 청소기 인기상품 비교분석 [학습링크](https://github.com/KangJeongTaek/bigdata-analysis-2024/blob/main/day07/da17_무선청소기_인기상품_분석.ipynb)
        1. 다나와 사이트(https://www.danawa.com)
        2. 무선청소기 검색
        3. 셀레니움으로 웹크롤링


## 8일차 학습
### 빅데이터 학습

- #### 데이터 분석 실습
    - 무선 청소기 인기상품 비교분석(이어서) [학습링크](https://github.com/KangJeongTaek/bigdata-analysis-2024/blob/main/day08/da18_무선청소기_인기상품_분석.ipynb)
        1. 다나와 크롤링 중 들어온 값이 이상한 데이터들

            ![예시](https://raw.githubusercontent.com/KangJeongTaek/bigdata-analysis-2024/main/images/ba016.png)

        2. 전처리
            - 결측치, 이상치 처리(수동,fillna(),dropna() 등)
        
        3. 무선 청소기 Top 20 분석 시각화

            ![예시](https://raw.githubusercontent.com/KangJeongTaek/bigdata-analysis-2024/main/images/ba017.png)

