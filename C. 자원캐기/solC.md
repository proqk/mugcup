## 자원 캐기

우선 WOOK은 오른쪽이나 아래쪽으로 이동할 수 있으므로, 한 지점에서 이동할 수 있는 경우의 수는 두 가지이다. 아래쪽으로 내려가서 수집할 수 있는 자원의 개수와 오른쪽으로 가서 수집할 수 있는 자원의 개수와 비교하여 큰 값을 현재 칸에 있는 칸에 있는 자원의 개수에 더하여 반환시켜 주는 깊이 우선탐색을 해주면 된다.

총 시간 복잡도는 (N+M-1)^2 이다.

### 분류
깊이 우선탐색, 동적 계획법
