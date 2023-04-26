剑指 Offer 58 - II. 左旋转字符串

```python
#python3: 切片
class Solution:
    def reverseLeftWords(self, s: str, n: int) -> str:
        return s[n:] + s[:n]
# python3: 模 + index
class Solution:
    def reverseLeftWords(self, s: str, n: int) -> str:
        new_s = ''
        for i in range(len(s)):
            j = (i + n) % len(s)
            new_s += s[j]
        return new_s
```

