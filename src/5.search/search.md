#### 검색

- 검색알고리즘이 무엇인지?
- 선형 검색 이란?
  - 일정한 방향을 가지고 이동하면서 한 번에 하나의 항목을 확인한다(모든 항목을 확인).
  - 데이터가 분류되지 않을때 사용한다.
  - O(n)선형시간
- 이진 검색 이란?
  - 이진검색은 특정값을 확일할때마다 남은 항목의 절반을 없엘수 있다.
  - 데이터가 분류되어 있을때 사용한다.
  - 기본적인 컨셉은 분할정복이다.
    - 중간점을 선택하고
    - 찾는값이 중간점 기준 왼쪽에 있을 경우을 확인
    - 찾는값이 중간점 기준 오른쪽에 있을 경우을 확인
    - 검색범위를 변경하면서 검색량의 절반을 제거 할 수 있다.
  - O(logN)로그시간:n의값이 커질수록 실행시간이 logN에 비례해서 증가한다.
- 나이브 문자열 검색 이란?
- KMP 문자열 검색 이란?