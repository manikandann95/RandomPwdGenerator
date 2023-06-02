# RandomPwdGenerator
Creates Random Password with Alpha Numeric and Symbols with custom range

```python
import random
import string

symbols = string.ascii_letters + string.digits + string.punctuation
secure_random = random.SystemRandom()
password = "".join(secure_random.choice(symbols)
for i in range(10))

print(password)
```
