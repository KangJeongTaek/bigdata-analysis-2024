## 2일차 학습
### 빅데이터 학습

- #### Pandas 학습 (이어서)

    3. 데이터 통합(merge,concat)
        - !중요 pandas2 버전에서는 append가 사라졌으므로 pandas.concat으로 사용할 것! [관련 링크](https://pandas.pydata.org/docs/whatsnew/v2.0.0.html)

            ![concat 결과](https://raw.githubusercontent.com/KangJeongTaek/bigdata-analysis-2024/main/images/ba002.png)

    4. (Pivot)피벗 테이블
        - 통계를 내면서 테이블을 세로로된 DataFrame을 가로로 바꿔주는 기능
            - aggfuc 옵션
                mean : 평균
                sum : 합계
                min : 최솟값
                median : 중앙값
                max : 최댓값
                count : 개수
                nunique : 중복을 제거한 후 개수(원소 개수)

- #### Numpy 학습
    - Numpy는 행렬처리 수치 계산을 손쉽게 할 수 있도록 도와주는 계산관련 라이브러리, 생각보다 많이 사용 안 됨
    - Scipy는 과학쪽에 특화된 계산관련 라이브러리
            - DataFrame에서 수치적으로 처리할 게 있으면 numpy로 변경한 다음, 계산 처리한 뒤에 다시 DataFrame으로 변경

- #### Matplotlib / Seaborn
    - Matplotlib, Seaborn은 데이터 시각화 라이브러리
    - Matplotlib 기본, Seaborn은 Matplot.lib 확장버전

- #### Selenium(웹 크롤링 자동화 라이브러리)
    - 웹 크롤링 자동화 라이브러리
    - 크롬 드라이버 필수 [링크](https://googlechromelabs.github.io/chrome-for-testing/#stable)

        1. 자신의 크롬 버전에 맞는 드라이버 설치
            
            ![크롬 버전](https://raw.githubusercontent.com/KangJeongTaek/bigdata-analysis-2024/main/images/ba003.png)

        2. 특정 폴더 압축해제

        3. 시스템 속성 > 고급 > 환경변수 등록(sysdm.cpl)
            - Path 맨 마지막에 크롬 드라이버 경로 추가

        4. 셀레니움과 연동, 실행

            ![셀레니움연동](https://raw.githubusercontent.com/KangJeongTaek/bigdata-analysis-2024/main/images/ba004.png)

