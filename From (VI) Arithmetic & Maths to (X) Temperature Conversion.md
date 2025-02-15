## 🧮 6. Arithmetic & Maths (aka making numbers suffer)

### 🔢 **Basic Operations**

```python
friends = 5  # fake number, i have none  

friends = friends + 1  # made a new friend, suspicious  
friends += 1  # another one? this is unrealistic  

friends = friends - 2  # back to reality  
friends -= 2  # now we’re in the negatives  

friends = friends * 3  # cloning people, very ethical  
friends *= 3  # too many people, help  

friends = friends / 2  # why am i dividing friends?  
friends /= 2  # oh god, fractions of friends  

friends = friends ** 2  # squared friendships, infinite suffering  
friends **= friends  # okay that’s too much  

remainder = friends % 3  # what’s left after friendship division  
remainder = friends % 2  # are friendships even or odd?  

# 🔼 useful for checking if a number is even or odd (but who cares, really)
```

### 🏗 **Built-in Functions**

```python
x = 3.14  # pi but we rounded up, blasphemy  
y = -4  # why is this negative? idk, just go with it  
z = 5  # the normal one  

result1 = round(x)  # 3, i ruined pi  
result2 = abs(y)  # 4, no more negativity  
result3 = pow(4,3)  # 4³, big number  
result4 = max(x, y, z)  # which number is superior? z  
result5 = min(x, y, z)  # which number is the biggest loser? y  

print(result1, result2, result3, result4, result5)  # behold, numbers  

```

### 📚 **Math Library Magic**

```python
import math  

x = 9  # boring  

print(math.pi)  # 3.141592653589793, too long, didn't read  
print(math.e)  # 2.718281828459045, who even uses this?  
print(math.sqrt(x))  # 3.0, the lazy way to find square roots  

x = 9.2
print(math.ceil(x))  # rounds up, liar  
print(math.floor(x))  # rounds down, more honest    
```

### 🎯 **Calculate Circle Circumference & Area**
👶 **Age Check (Do you qualify for existence?)**

```python
import math

radius = float(input('Enter the radius of a circle: '))
circumference = 2 * math.pi * radius
print(f"The circumference is : {round(circumference, 2)}cm")

area = math.pi * pow(radius, 2)
print(f"The area of the circle is: {round(area, 2)}cm^2")
```

#### 🛠 **Example Run**

```plaintext
Enter the radius of a circle: 10.5
The circumference is : 65.97cm
The area of the circle is: 346.36cm^2
```

### 📏 **Pythagoras Theorem to Find Hypotenuse**

$$c=\sqrt{a^2+b^2}$$

```python
import math

a = float(input("Enter side A: "))
b = float(input("Enter side B: "))

c = math.sqrt(pow(a,2) + pow(b,2))

print(f"Side C = {c}")
```

#### 🛠 **Example Run**

```plaintext
Enter side A: 3
Enter side B: 4
Side C = 5.0
```


## 🤔 7. If Statements (aka making life decisions with code)

### 👶 **Age Check (Do you qualify for existence?)**

```python
age = int(input("Enter your age: "))  # do you even age, bro?  

if age >= 100:
    print("You are too old to sign up. Also, respect.")
elif age <= 0:
    print("You are not born yet. Are you a time traveler?")
elif age == 17:
    print("You are 17 years old, you can sign up next year. Patience.")
elif age >= 18:
    print("Congratulations! You are now signed up.")
else:
    print("You are a minor, therefore not eligible to sign up. Sucks to be you.")
```

---

### 👤 **Name Check (aka do you even exist?)**

```python
name = input("What is your name? ")  # this is where you give me your fake identity  

if name == "":
    print("You did not enter a name. Are you a ghost?")
else:
    print(f"Hello, {name}! Nice to meet your imaginary self.")
```

---

### 🏷️ **Boolean Conditions (aka the simplest way to lie)**

#### 🔹 **For Sale**

```python
for_sale = True  # capitalism  

if for_sale:
    print('For sale, take my money!')
else:
    print('Not for sale, let me cry in peace.')
```

---

#### 🔹 **User Online Status (aka stalking people)**

```python
online = True  # toggle your existence  

if online:
    print('the user is online. time to bother them.')
else:
    print('the user is offline. they are safe for now.')
```

---

### 🍽️ **Response (Do You Want Food? Choose wisely.)**

```python
response = input("Would you like some food: Y/N: ")  # say yes, don't be dumb  

if response == "Y":
    print("Here is your food. You chose wisely.")
elif response == "N":
    print("No food for you. Starvation it is.")
else:
    print("Invalid response. Try again, fool.")
```
# 🔢 8. Python Calculator (aka basic math but make it dramatic)

```python
# 🤔 what are we calculating? idk, let's just do stuff  
operator = input("Enter an operator (+ - * /): ")  # pick your weapon  
num1 = float(input("Enter the 1st number: "))  # number one, the chosen one  
num2 = float(input("Enter the 2nd number: "))  # number two, the rival  

if operator == '+':
    result = num1 + num2  # addition, yay  
    print(round(result, 3))  # rounded, because decimals are annoying  
elif operator == '-':
    result = num1 - num2  # subtraction, for when you want less  
    print(round(result, 3))  
elif operator == '*':
    result = num1 * num2  # multiplication, aka making numbers bigger  
    print(round(result, 3))  
elif operator == '/':
    if num2 == 0:
        print("Division by zero? Really? Are you okay?")  # smh  
    else:
        result = num1 / num2  # division, breaking things apart  
        print(round(result, 3))  
else:
    print(f"{operator} is not a valid operator.")  # just say you can't do math and go  
```

---

# ⚖️ 9. Weight Conversion (aka how much do you weigh in different units?)

```python
# 🎭 identity crisis: lbs or kg?  
weight = float(input("Enter your weight: "))  # judgment-free zone  

unit = input("(L)bs or (K)g: ")  # pick wisely  

if unit.upper() == "L":
    weight_kg = weight * 0.45  # lbs to kg, the betrayal  
    print(f"You are {weight_kg} kilos")  # now you're lighter  
elif unit.upper() == "K":
    weight_lbs = weight / 0.45  # kg to lbs, the revenge  
    print(f"You are {weight_lbs} pounds")  # suddenly heavier  
else:
    print(f'Invalid unit: {unit}')  # pick a side, coward  
```

---

# 🌡️ 10. Temperature Conversion (aka why does the world have two systems?)

```python
# 🔥 is it hot or cold? who knows  
unit = input("Enter the unit of temperature (F/C): ")  # pick a side  
temp = float(input("Enter the temperature: "))  # how cooked are you?  

if unit.upper() == "F":
    temp = round(((temp - 32) * 5) / 9)  # fahrenheit to celsius, aka making sense  
    print(f'The temperature in Celsius is {temp}°C')  
elif unit.upper() == "C":
    temp = round(((temp * 9) / 5) + 32)  # celsius to fahrenheit, aka chaos  
    print(f'The temperature in Fahrenheit is {temp}°F')  
else:
    print("Invalid unit. You failed science.")  # shame  
```

---
