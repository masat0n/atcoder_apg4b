## 問題. [A - Infinite Coins](https://atcoder.jp/contests/abc088/tasks/abc088_a)

<details><summary>私の解答</summary><div>
  
```C++

#include <bits/stdc++.h>
using namespace std;

int main() {
  int N, A;
  cin >> N >> A;

  if (N % 500 <= A) {
    cout << "Yes" << endl;
  }
  else {
    cout << "No" << endl;
  }
}

```

</div></details>
