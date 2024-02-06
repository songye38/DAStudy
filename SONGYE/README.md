## 호텔 리뷰 데이터를 활용한 분류 모델 개발
- 설명: 유저가 계좌 이용을 계속할지, 혹은 해지할지를 예측하는 이진 분류 Kaggle Competition
### 사용한 데이터셋
    - Binary Classification with a Bank Churn Dataset(Playground Series - Season 4, Episode 1)
### 날짜별 진행내용
#### 240128 : 데이터 탐색 및 시각화
- Json 형식 문자열 데이터를 각 칼럼으로 전개 (json_normalize 함수 이용)
- 텍스트 데이터를 word cloud로 시각화
- nltk stopwords를 이용해 불용어를 제거하고 핵심 단어 위주로 시각화
- nltk 라이브러리에서 opinion_lexicon을 이용해 감정 단어만 추출해 word cloud로 시각화
- langdetect의 detect 함수를 이용해 텍스트의 언어를 추출하고 영어로 된 데이터만 사용
- TfidfVectorizer를 이용해 의미없이 반복적으로 출현하는 단어를 제외하고 중요도가 높은 단어만 시각화
#### 240204 : 분류 모델 개발
#### 240218 : ML과 DL을 활용한 분류 모델 개발 및 추천시스템 개발




    - 컬럼별 EDA, 특성에 맞는 전처리 및 스케일링
    - 분류 모델 비교, 적합한 모델 선정, 하이퍼파라미터 튜닝
    - Kaggle Competition 제출
- 사용한 스킬셋
    - pandas
    - matplotlib, seaborn
    - scikit-learn