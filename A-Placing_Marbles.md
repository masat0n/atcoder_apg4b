## 問題. [A - Placing Marbles](https://atcoder.jp/contests/abc081/tasks/abc081_a)

<details><summary>私の解答</summary><div>

\```C++
#include <bits/stdc++.h>
using namespace std;

int main() {
  int s, s1, s2, s3, x;
  cin >> s;
  
  // s1の値
  if (s >= 100) {
    s1 = 1;
  } 
  else {
    s1 = 0;
  }
  
  // s2の値
  if (s1 == 1) {
    if (s - 100 >= 10) {
      s2 = 1;
    } else {
      s2 = 0;
    }
  }

  // s3の値
  if (s % 2 == 1) {
    s3 = 1;
  } 
  else {
    s3 = 0;
  }
  
  x = s1 + s2 + s3;
  cout << x << endl;
}
\```
</div></details>