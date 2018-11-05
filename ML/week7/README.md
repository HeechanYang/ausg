## 순전파

1. 신경망을 통과해서 도달한 결과값은 오차를 포함한다.
2. 최종적으로 나온 오차는 여러 계산 과정들을 거치며 합산된 값이다.
3. 각 계산 과정마다 어느 정도의 오차가 발생했는지를 관찰해서 계산과정을 다시 수정해준다.
4. 즉, 오차가 많이 발생되게 한 요인들은 큰 폭으로 값을 변화시킨다.
5. 수치미분 대신 오차역전파 사용으로 효율을 좋게 한다. 

계산그래프란?
- 계산과정을 그래프로 나타냄
- 노드와 에지로 표현

국소적 계산이란?
- 노드에 직접 관계된 정보만으로 계산
- 노드입력(100,2)으로 출력(200) 생성