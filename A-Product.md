## 問題. [A - Product](https://atcoder.jp/contests/abc086/tasks/abc086_a)

<details><summary>私の解答</summary><div>
  
```C++

#include <bits/stdc++.h>
using namespace std;

int main() {
  int a, b;
  cin >> a >> b;

  if (a * b % 2 == 0) {
    cout << "Even" << endl;
  }
  else {
    cout << "Odd" << endl;
  }
}

```

</div></details>
