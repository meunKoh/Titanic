데이터 탐색 : 각 특성 간의 관계성 파악
- matplotlib
- seaborn


데이터 전처리 :
- Sex, Pclass, Embarked : 원핫인코딩
- Title : Name 컬럼에서 Mr.Mrs.Miss. 등등을 추출하여 Title에 저장하고, Mr, Mrs, Miss, Master, Royalty, Officer로 나눔 - 원핫인코딩
- Age : 결측치는 Title별 median 값으로 채우고 구간 범주로 나눔
- tgroup : 티켓 번호로 그룹핑해서 동행자가 몇명인지 저장
- Deck : A,B,C,D,E,F,T로 나누고 그룹별로 같은 Deck을 사용했다고 가정하고 결측치 채움
- Fare : Fare을 동행자로 나누어 Fare_per_person 컬럼을 생성하고 구간 범주로 나눔
