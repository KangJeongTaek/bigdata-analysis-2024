## 9일차 학습
### 빅데이터 학습

- #### 빅데이터 실습
    - OpenAPI 기반 크롤링 실습 [학습링크](https://github.com/KangJeongTaek/bigdata-analysis-2024/blob/main/day09/da19_데이터포털_OpenAPI활용.ipynb)
        - [공공데이터포털]https://data.go.kr 링크

        ```python
        year = 2023
        month = 12
        touristDatas = []
        for day in tqdm(range(1,32)):
            reqYmd = f'{year}{month}{day:02d}'
            if getTouristDataService(reqYmd) == None:
                resList = []
            else:
                resList = getTouristDataService(reqYmd)
    
        touristDatas = touristDatas + resList
        ```

        100%|██████████| 31/31 [03:35<00:00,  7.66s/it]

    - 통계 분석 리뷰
        - 그래프를 사용한 기술 통계 분석

        - 히트맵을 사용한 상관 분석

    - 와인품질 분석 [학습링크](https://github.com/KangJeongTaek/bigdata-analysis-2024/blob/main/day09/da20_와인품질등급_분석예측.ipynb)

        - [자료 링크](https://archive.ics.uci.edu/dataset/186/wine+quality)
