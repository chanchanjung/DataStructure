# List 와 ArrayList의 차이

회사에서 개발하는 주문 서비스에서 history를 DB에서 JSON Array 형태로 저장하도록 설계하였다.(History 데이터가 적은 이유로 table을 분리하는 대신 하나의 column에 저장하게 되었다.)
데이터를 저장하기 위해 history를 `Collections.emptylist()`로 초기화 하였더니 list에 데이터를 추가하는 `add()`함수를 사용할 수 없었다.

