---
layout: post
title: "[c++]시간복잡도&공간복잡도"
order: 31
---

# 시간 복잡도

|연산 횟수(N)|허용 시간 복잡도|
|:---:|:---:|
|N<12|O(N!)|
|N<26|O(2^N)|
|N<100|O(N^4)|
|N<500|O(N^3)|
|N<3000|O(N^2 * logN)|
|N<5000|O(N^2)|
|N<1백만|O(NlogN)|
|N<1천만|O(N)|

# 공간 복잡도

공간복잡도의 경우 512MB는 1.2억개의 int(4B)를 저장 가능.