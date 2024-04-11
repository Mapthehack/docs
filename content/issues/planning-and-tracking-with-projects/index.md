---```python
import random

def generate_powerball_numbers():
    white_balls = random.sample(range(1, 70), 5)
    power_ball = random.randint(1, 26)
    return white_balls, power_ball

# Exa'''dmple usage:
white_balls, power_ball = generate_powerball_numbers()
print("White Balls:", white_balls)
print("Power Ball:", power_ball)
```

This code will generate a set of 5 random white ball numbers between 1 and 69, and a random power ball number between 1 and 26. You can run this code to generate your own random Powerball numbers.
  
