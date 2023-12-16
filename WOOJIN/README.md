### 커피빈의 국가별 실적과 멤버십 충성도 분석
- 설명: 커피빈의 raw data를 분석하여 판매 실적과 멤버십 현황을 파악하고, 보완 및 발전 방향성 제안
- 사용한 데이터셋
    - [Coffee Bean Sales Raw Dataset](https://www.kaggle.com/datasets/saadharoon27/coffee-bean-sales-raw-dataset) (Kaggle)
- 진행 절차 및 내용
    - 3가지 데이터셋 각각의 컬럼별 EDA를 통해 분포 및 특성 확인
    - 국가별 원두별 실적 분석을 통해 **고급화 상품 촉진 전략** 제안
    - 멤버십 데이터에 대한 정규성 검정 및 비모수적 검정 수행
    - 멤버십 효용성 미비를 보완할 대책으로 **충성도 제고 전략** 제안
- 사용한 스킬셋
    - Pandas, Numpy
    - Matplotlib
    - Scipy

### 미국 수제 맥주 산업 분석과 신제품 포지셔닝
- 설명: 미국의 수제 맥주 및 양조장 데이터를 분석하여 수제 맥주 산업을 이루는 요소들을 탐색하고, 가상의 신규 제품을 개발해 보는 과정을 수행
- 사용한 데이터셋
    - [Craft Beers Dataset](https://www.kaggle.com/datasets/nickhould/craft-cans/)(Kaggle): 미국의 캔맥주 2K+, 미국의 500개 이상 양조장 데이터
- 진행 절차 및 내용
    - 수제 맥주 데이터, 양조장 데이터를 로딩하여 **각 컬럼별 EDA 및 결측치 처리**
    - **선형회귀분석**을 통해 핵심 컬럼들 간의 관계를 분석하고 통계적으로 검증
    - **클러스터링**을 통해 가상의 신규 제품 'HONEY DEW'의 시장 내 포지셔닝 진행
- 사용한 스킬셋
    - Pandas, Numpy
    - Matplotlib, Seaborn
    - Scipy
    - Scikit-learn (KMeansClustering)