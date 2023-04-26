# 替换空格

```python
# python3
class Solution:
    def replaceSpace(self, s: str) -> str:
        ater_s = s.replace(' ', '%20')
        return ater_s

# python3
class Solution:
    def replaceSpace(self, s: str) -> str:
        return '%20'.join(s.split(' '))
```

