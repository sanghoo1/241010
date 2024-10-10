# grid

그리드는 플렉스와 비슷하게 grid container와 grid item을 역할을 하게 구성이 되어있다.

gird-template-columns는 1개의 값만 쓰면 1열을 만든다.
gap은 셀의 크기에 포함이 안되고 margin은 셀의 크기로 들어간다.

gird-template-columns: 1fr 100px 2fr;
에서 1fr 값은 너비값에서 100px를 뺀 나머지의 1/3

행과 열을 만들때 나머지 한개때문에 밑으로 내려간것은 행으로 치는 게 아니라 남는 값이다.

flex는 가로가 row 세로가 column 이지만
그리드는 가로가 column 세로가 row이다.