# DataStructure

* [Sort]
  * Selection Sort
  * Insertion Sort
  
  
  </br>
  
  #### Sort
  ##### Selection Sort
  * 가장 작은 데이터를 찾아 가장 앞의 데이터와 교환해나가는 방식
  * 시간복잡도 : O(n^2)
  
  * 장점 : 자료 이동 횟수가 미리 결정 </br> 데이터의 양이 적을 때 성능이 좋음
  * 단점 : 같은 인덱스끼리도 교환 연산 발생 가능 </br> 데이터의 양이 많아지면 속도가 급격히 떨어짐

  ##### Insertion Sort
  * 이미 정렬 된 부분의 적절한 위치에 삽입해 가며 정렬
  * 시간복잡도 : O(n^2)
  
  * 장점 : 정렬되어 있을 경우 교환이 한번도 일어나지 않고 비교만 n-1번 </br> 그래서 속도가 빠르다
  * 단점 : 역순으로 정렬 되어 있을 때는 최악

