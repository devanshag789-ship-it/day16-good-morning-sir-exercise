# #DAY 16 — Exercise 2- Good Morning, Sir

# Good Morning, Sir

### 🎯 Greeting According to Local Computer Time

Write a program that greets the user according to the **local time of their computer**.

- If it is morning → print **Good Morning, Sir.**
- If it is afternoon → print **Good Afternoon, Sir.**
- If it is evening → print **Good Evening, Sir.**
- Otherwise → print **Good Night, Sir.**

## 🕒 Using `strftime()`- Time Module

```python
import time

Mytime = time.strftime("%H:%M:%S")
print(Mytime)
Hour = time.strftime("%H")
print(Hour)
Min = time.strftime("%M")
print(Min)
Sec = time.strftime("%S")
print(Sec)
```

✅ End of Exercise.
