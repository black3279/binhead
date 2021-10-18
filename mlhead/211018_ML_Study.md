### 211018 정석영
### Logistic Regression
- 지도학습이란 Train 데이터와 Test 데이터가 있는 것을 말한다
- Output 이 numerice 혹은 카테고리로 나오는 경우가 있다
- Output Value 를 클래스 혹은 레이블 이라고 한다
- sigmoid 함수를 이용해서 바이너리로 Output 을 분할하여 특정 값을 가질 확률이 얼마나 강한지를 알 수 있다
- 뉴럴 네트워크에서 히든 레이어가 없는 퍼셉트론  모델(선형분류기)에서는 XOR 문제를 풀 수 없는 문제가 있다
- likelihood(우도) 를 최대로 하는 접근을 취하게 된다
- entropy 란 데이터의 혼잡도를 분별해내기 위해서 어느 정도의 비트가 필요한가를 의미하는 measure 의 개념이다