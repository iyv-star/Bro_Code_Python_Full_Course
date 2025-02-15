## 🖨️ 1. Print (aka making the computer talk)

```python
print("i like pizza!")  # obviously.
print("it's my favorite food!")  # valid statement.
# this is my first python program. it's all downhill from here.
```

---

## 🎭 2. Variables (aka giving things names so i don’t forget them)

```python
# 📝 strings (aka words, names, and things i yell at my computer)
first_name = "pavan"  # identity crisis begins here  
last_name = "mudigonda"  # sounds fancy  
food = "pizza"  # the only thing keeping me alive  
email = "bro123@fake.com"  # this is fake. don’t email it. or do. idk.  

print(first_name)  # proving it exists  

# 🔢 integers (whole numbers, aka math that doesn’t involve decimals)  
age = 20  # this will change. unfortunately.  
quantity = 3  # number of pizzas i wish i had rn  
num_of_students = 100  # why are there so many  

# 🔬 floats (numbers with decimal points. precision matters, apparently.)  
pi = 3.14  # math nerds will tell me this isn’t precise enough. idc.  

# 🤔 booleans (true or false. no in-between.)  
is_student = True  # when does this nightmare end  
for_sale = False  # i am not for sale. yet.  
is_online = True  # stalking mode activated  

# 💬 printing things like a civilized person  
print(f"hello, {first_name} {last_name}")  # full name reveal moment  
print(f"i like {food}!")  # obvious but necessary information  
print(f"i am {age} years old")  # unfortunately  
print(f"i am buying {quantity} pizzas")  # probably not enough  
print(f"there are {num_of_students} students in the class")  # chaos  
print(f"the value of pi is {pi}")  # mathematically questionable  

# 🧠 decision making (aka if-else, aka making my code judge me)  
print(f"is the person a student? {is_student}")  # let’s find out  

if is_student:  
    print(f"{first_name} is a student")  # tragedy  
else:  
    print(f"{first_name} is not a student")  # lucky them  

if for_sale:  
    print("item is for sale")  # capitalism  
else:  
    print("item is not for sale")  # rebellion  

if is_online:  
    print("user is online")  # lurking  
else:  
    print("user is offline")  # touch grass challenge  

```
___
## 🎭 3. Type Casting (aka forcing variables to change their identity)

```python
# 🔮 variables with assigned fates  
name = "pavan"  # still human  
age = 25  # might as well be ancient  
is_student = False  # finally free  
gpa = 3.5  # surprisingly decent  

# 🕵️‍♂️ revealing their true identities  
print(type(name))  # <class 'str'>  
print(type(age))  # <class 'int'>  
print(type(is_student))  # <class 'bool'>  
print(type(gpa))  # <class 'float'>  

# 🎭 plot twist: age is now a float  
age = float(age)  # can't escape numbers  
print(age)  # now with decimals, completely unnecessary  

# 🎩 magic trick: gpa turns into an int  
print(int(gpa))  # say goodbye to decimal accuracy  
```

---

## 🎤 4. User Input (aka letting the user make bad choices)

### 📏 **area.py** (aka finding out if you suck at geometry)

```python
length = input("enter the length of the rectangle: ")  # do math, peasant  
width = input("enter the width of the rectangle: ")  # no, it can’t be negative  
area = float(int(length) * int(width))  # math happens  
print(f"the area of the rectangle is {area}cm²")  # flex your knowledge  
```

### 🏷️ **main.py** (aka asking basic questions)

```python
name = input("what is your name? ")  # say your name, coward  
age = int(input("what is your age? "))  # no lying  
print(f"hello {name}!")  # friendly  
print(f"you are {age} years old.")  # unfortunate  
```

### 🛒 **shopping.py** (aka realizing you're broke)

```python
item = input("what would you like to buy? ")  # impulse purchase incoming  
price = float(input("what is the price of the item? "))  # inflation is wild  
quantity = int(input("how many would you like to buy? "))  # don't be greedy  
total = price * quantity  # capitalism intensifies  
print(f"the total cost is ${total:.2f}.")  # regret sets in  
```

---

## 🎭 5. `Madlibs` Game (aka structured chaos)

```python
# 🤡 welcome to my literary disaster  
adjective1 = input("enter an adjective (description): ")  # why are we doing this? no idea  
noun1 = input("enter a noun (person, place, thing): ")  # please pick something cursed  
adjective2 = input("enter another adjective (description): ")  # make it worse  
verb1 = input("enter a verb ending in 'ing': ")  # EXCITING ACTION!!  
adjective3 = input("last adjective, do your worst: ")  # make it emotional damage  

# 📜 behold, the masterpiece  
print(f"today i went to a {adjective1} zoo.")  
print(f"in an exhibit, i saw a {noun1}.")  # why is it there? who put it there?  
print(f"it was {adjective2} and {verb1}.")  # nightmare fuel  
print(f"i was {adjective3}.")  # obviously   
```
🤡 Example Run:

```plaintext
Enter an adjective (description): cursed
Enter a noun (person, place, thing): chicken
Enter an adjective (description): demonic
Enter a verb ending with 'ing': breakdancing
Enter an adjective (description): traumatized

today i went to a cursed zoo.
in an exhibit, i saw a chicken
chicken was demonic and breakdancing
i was traumatized
```
---

**this code is holding on by a thread. like me.** 🚀🔥
