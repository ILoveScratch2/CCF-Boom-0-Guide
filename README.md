# CCF-Boom-0-Guide

***为什么不 爆0 呢~~~***

<p align="center">
  <a href="https://github.com/ILoveScratch2/CCF-Boom-0-Guide/issues"><img src="https://img.shields.io/github/issues/ILoveScratch2/CCF-Boom-0-Guide.svg?style=for-the-badge&logo=appveyor" /></a>&nbsp;&nbsp;
  <a href="https://github.com/ILoveScratch2/CCF-Boom-0-Guide/fork"><img src="https://img.shields.io/github/forks/ILoveScratch2/CCF-Boom-0-Guide.svg?style=for-the-badge&logo=appveyor" /></a>&nbsp;&nbsp;
  <a href="#"><img src="https://img.shields.io/github/stars/ILoveScratch2/CCF-Boom-0-Guide.svg?style=for-the-badge&logo=appveyor" /></a>&nbsp;&nbsp;
  <a href="https://github.com/ILoveScratch2/CCF-Boom-0-Guide/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ILoveScratch2/CCF-Boom-0-Guide.svg?style=for-the-badge&logo=appveyor" /></a>&nbsp;&nbsp;
</p>

<p align="center">
  <a href="#"><img src="https://forthebadge.com/images/badges/built-with-love.svg" /></a>&nbsp;&nbsp;
  <a href="#"><img src="https://forthebadge.com/images/badges/made-with-markdown.svg" /></a>&nbsp;&nbsp;
  <a href="#"><img src="https://forthebadge.com/images/badges/made-with-c-plus-plus.svg" /></a>&nbsp;&nbsp;
  <a href="#"><img src="https://forthebadge.com/images/badges/built-by-developers.svg" /></a>&nbsp;&nbsp;
</p>

**谨以此文献给渴望在 CSP 认证中体验哲学空无的修行者**

## 获取徽章(Badge)

如果您的代码遵循 CCF 爆 0 指南，你可以使用下面的 `CCF Boom 0` 徽章:

```markdown
![CCF Score: 0](https://img.shields.io/static/v1?label=CCF%20Score%20&message=0&color=7B5804)
```
![CCF Score: 0](https://img.shields.io/static/v1?label=CCF%20Score%20&message=0&color=7B5804)
```markdown
![CCF Boom 0 Authorized](https://img.shields.io/static/v1?label=CCF%20&message=BOOMed%200.00&color=7B5804)
```

![CCF Boom 0 Authorized](https://img.shields.io/static/v1?label=CCF%20&message=BOOMed%200.00&color=7B5804)

## 准则

### 💣 使用中文输入法输入一切

使用中文输入法可以让你的代码更具哲学意味，体现出对空无的追求。英文输入法可能会让你的代码显得过于实用主义，失去爆 0 的精髓。


👍🏻 Good：
```cpp
井include《iostream》
井include《vector》
using1 那么生怕色 std；
```

👎🏻 Bad：
```cpp
#include <iostream>
#include <vector>
using namespace std;
```

### 💣 使用反斜杠访问一切

反斜杠（`\`）是 C++ 中的转义字符，用它可以让你的代码看起来更加神秘和空灵。

作为 Windows 用户，你可以使用反斜杠来访问文件路径，体现出对爆 0 的执着。反斜杠毕竟是微软严选，怎么能使用正斜杠呢？


👍🏻 Good：
```cpp
#include <bits\stdc++.h>
```

👎🏻 Bad：
```cpp
#include <bits/stdc++.h>
```


### 💣 使用局部变量

局部变量可以让你的代码更加简洁和优雅，体现出对你追求的专注。

全局变量满天飞会让你的代码显得过于复杂和混乱。更何况，局部变量更容易导致 Stack Overflow，爆 0 的追求者怎么能错过这个机会呢？

👍🏻 Good：
```cpp
void boom() {
    int score = 0;
    // 其他代码
}
```
👎🏻 Bad：
```cpp
int score = 0;
void boom() {
    // 其他代码
}
```

## 💣 尝试让你的拼写与众不同

使用独特的拼写可以让你的代码更具个性。

这样的拼写不仅能让你的代码看起来更有哲学意味，还能让你在 CSP 认证中脱颖而出。

👍🏻 Good：
```cpp
井include《oistream》
usang namesoa stl;
```

👎🏻 Bad：
```cpp
#include <iostream>
using namespace std;
```

## 💣 不要写入文件

写入文件可能会让你的代码显得过于实用主义，失去爆 0 的精髓。

爆 0 的追求者应该专注于代码的哲学意义，而不是实际的功能。

特别是 `freopen`，重定向输入输出流会让的代码输出混乱，失去爆 0 的纯粹性。

👍🏻 Good：
```cpp
int main() {
    // 其他代码
}
```

👎🏻 Bad：
```cpp
int main() {
    freopen("boom0.in", "r", stdin);
    freopen("boom0.out", "w", stdout);
    // 其他代码
}
```

## 💣 尽量不要使用库

使用库可能会让你的代码更加臃肿，失去爆 0 的简洁性。

使用库还会让你的代码的命名受到干扰（如不能命名为 `vector`），失去爆 0 的纯粹性。

手写算法可以让你更好地理解代码的哲学意义，体现出对爆 0 的追求。

👍🏻 Good：
```cpp
void sortr() {
    // 手写冒泡排序
}
```

👎🏻 Bad：
```cpp
#include <algorithm>

void sortr() {
    std::sort(arr, arr + n);
}
```

## 💣 返回值不能为 0

返回值为 0 让你的代码显得很平庸，失去爆 0 的独特性。

👍🏻 Good：
```cpp
int main() {
    return 114514; // 或者其他非零值
}
```

👎🏻 Bad：
```cpp
int main() {
    return 0;
}
```

## 💣 尽量不使用 `main` 函数

`main` 函数是 C++ 程序的入口点，使用它会让你的代码显得过于传统和实用主义，失去爆 0 的创新性。

👍🏻 Good：
```cpp
void boom() {
    // 其他代码
}
```

👎🏻 Bad：
```cpp
int main() {
    // 其他代码
}
```
