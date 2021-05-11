## 問題. [A - Libra](https://atcoder.jp/contests/abc083/tasks/abc083_a)

<details><summary>私の解答</summary><div>
  
```C++

#include <bits/stdc++.h>
using namespace std;

int main() {
  int A, B, C, D;
  cin >> A >> B >> C >> D;

  if (A + B > C + D) {
    cout << "Left" << endl;
  }
  else if (A + B == C + D) {
    cout << "Balanced" << endl;
  }
  else {
    cout << "Right" << endl;
  }
}

```

</div></details>
