# 001 - Weird Algorithm

# Ý tưởng
- Bài toán mô phỏng theo quy luật Collatz.
- Quy luật:
  - Nếu n chẵn → n /= 2
  - Nếu lẻ → n = 3n + 1
- Dừng khi n = 1

---

# Template rút ra
```cpp
while (n != 1) {
    if (n % 2 == 0) n /= 2;
    else n = 3 * n + 1;
}
