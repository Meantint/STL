# algorithm

## sort

### 정의

&nbsp;`[first, last)` 범위를 오름차순 정렬한다.

### 시간 복잡도

&nbsp;평균적으로 `O(N * log N)`의 시간 복잡도를 가진다.

### 사용자 정의 정렬

&nbsp; `sort`는 세번째 인자로 사용자가 설정한 정렬 함수를 사용할 수 있다.

## lower_bound

### 정의

&nbsp;`[first, last)` 범위에서 값의 크기가 `val` 이상인 첫번째 `iterator`를 반환한다.

### 시간 복잡도

&nbsp;`O(log N)`의 시간 복잡도를 가진다.

### 찾는 값이 없을 때

&nbsp;정의에서 말한대로 `val` 이상인 첫번째 `iterator`를 반환한다. `val` 이상인 값이 없을 경우 `last`의 `iterator`를 반환한다.

## upper_bound

### 정의

&nbsp;`[first, last)` 범위에서 값의 크기가 `val` 초과인 첫번째 `iterator`를 반환한다.

### 시간 복잡도

&nbsp;`O(log N)`의 시간 복잡도를 가진다.

### 찾는 값이 없을 때

&nbsp;정의에서 말한대로 `val`을 초과하는 첫번째 `iterator`를 반환한다. `val`을 초과하는 값이 없을 경우 `last`의 `iterator`를 반환한다.
