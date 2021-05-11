## 問題. [A - Parking](https://atcoder.jp/contests/abc080/tasks/abc080_a)

<details><summary>私の解答</summary><div>
  
```C++

#include <bits/stdc++.h>
using namespace std;

int main() {
  int N, A, B;
  cin >> N >> A >> B;

  if (N * A < B) {
    cout << N * A << endl;
  }
  else {
    cout << B << endl;
  }
}

```

</div></details>
