## 준오는 심술쟁이!!

(대회가 연기되는 바람에 30분만에 나온 문제인 건 비밀) 

제한시간이 1초이기 때문에 단순히 3000 * 3000 * 25 dp를 돌렸다간 시간초과를 받는다.

dp[문자열길이][s의 합] 일 때, 문자열 길이를 p, s 합을 q라고 하면

dp[p][q] = k가 0 ~ min(q, 25)일 때의 모든 dp[p-1][q-k]의 합

으로 점화식을 세워 해결할 수 있다.

나머지 연산 과정에서 음수가 나올 수 있으니 주의한다.