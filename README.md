# python_DA


### 코로나 바이러스 데이터
https://github.com/CSSEGISandData/COVID-19

- 국가별 코로나 바이러스 daily 현황 자료
- Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE) 에서 작성
- 데이터 소스는 https://github.com/CSSEGISandData/COVID-19/tree/master/who_covid_19_situation_reports 에 명시
- 실제 데이터 분석에서는 raw data를 어떻게 가져왔는지에 대해서도 세세히 알필요가 있을 때가 있음
- PDF로 만들어진 공식 문서에서 추출한 데이터와 공식 웹페이지를 크롤링해서 얻은 자료를 CSV 파일로 생성한 것으로 보임

### 속성간 상관관계 이해하기
- corr(method=상관계수): 각 속성간 상관 관계 확인하기 (피어슨 상관계수가 디폴트임)
- 피어슨 상관계수는 선형 상관 관계를 조사하며, 일반적으로
  - +1에 가까우면, 양의 선형 상관 관계 (1에 가까울 수록 선에 가까운 데이터가 많고, 한 변수값이 증가하면, 다른 변수값도 증가)
  - 0에 가까우면 상관관계가 없고
  - -1에 가까우면 음의 선형 상관 관계를 가진다 (-1에 가까울 수록 선에 가까운 데이터가 많고, 한 변수값이 증가하면, 다른 변수값은 감소) 라고
  해석됨
  
  
> 참고: 피어슨 상관계수 관계   <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/34/Correlation_coefficient.png/600px-Correlation_coefficient.png">
> 출처: [위키피디아]( https://ko.wikipedia.org/wiki/%ED%94%BC%EC%96%B4%EC%8A%A8_%EC%83%81%EA%B4%80_%EA%B3%84%EC%88%98)
