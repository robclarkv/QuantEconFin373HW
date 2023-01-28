Excercise 1


```python
z = 3
z = z + 4
print("z is", z)

#The value of z will become 7
```

    z is 7


Excercise 2


```python
x=("Mo and Robert")
len(x)
```




    13



Excercise 3


```python
import time
# Your code goes here
time.localtime()
#I called the function "localtime()" while importing "time" in order to access it.
#I found the function by clicking <Tab> to open the "methods".
```




    time.struct_time(tm_year=2023, tm_mon=1, tm_mday=26, tm_hour=18, tm_min=10, tm_sec=1, tm_wday=3, tm_yday=26, tm_isdst=0)



Excercise 4


```python
import time as t

t.localtime()
#It worked
```




    time.struct_time(tm_year=2023, tm_mon=1, tm_mday=26, tm_hour=18, tm_min=14, tm_sec=52, tm_wday=3, tm_yday=26, tm_isdst=0)



Question 5


```python
D=float(10000)
r=float(.025)
T=int(30)
```

Excercise 6


```python
D=float(10000)
r=float(.025)
T=int(30)

PDV=(D/((1+r)**T))
print(PDV)
```

    4767.426851809713


Excercise 7


```python
import math
x = 1.05
y = 1.02

z=((x-y)/x)

a=(math.log(x)-math.log(y))

print(z,a)
```

    0.028571428571428595 0.02898753687325232


Excercise 8


```python
x = 'What\'s wrong with this string'
print(x)
#The string is wrong as you can't use a " ` " if
#it does not have a " \ " before
```

    What's wrong with this string


Excercise 9


```python
x="Hello"
y="World"
print(x,y)
```

    Hello World


Excercise 10


```python
test = "abc"
replaced=(test.replace("c", "d"))
print(replaced)
```

    abd


Excercise 11


```python
price = "$6.50"

cleaned=(price.replace("$",""))
clean_num=(float(cleaned))
print(clean_num)
```

    6.5


Excercise 12 and 13


```python
my_string = "Mexico had ${GDP} billion in {year}"

gdp_2021=1.27
this=2021
last=2020
gdp_2020=1.09

print(my_string.format(GDP=gdp_2020, year=last))

print(my_string.format(GDP=gdp_2021, year=this))
```

    Mexico had $1.09 billion in 2020
    Mexico had $1.27 billion in 2021


Excercise 14


```python
# Your code goes here

my_string= "The {quarter} quarter revenue was ${million}M"

first="1st"
second="2nd"
third="3rd"
fourth="4th"

mon1="110"            #I formatted my string so I could reuse it
mon2="95"             #for different values in the same place of
mon3="100"            #the string.
mon4="130"

print(my_string.format(quarter=first, million = mon1))

print(my_string.format(quarter=second, million = mon2))

print(my_string.format(quarter=third, million = mon3))

print(my_string.format(quarter=fourth, million = mon4))

```

    The 1st quarter revenue was $110M
    The 2nd quarter revenue was $95M
    The 3rd quarter revenue was $100M
    The 4th quarter revenue was $130M


Excercise 15


```python
x = 2
y = 2
z = 4

# Statement 1
print(x > z)

# Statement 1
print(x == y)

# Statement 3
print((x < y) and (x > y))

# Statement 4
print((x < y) or (x > y))

# Statement 5
print((x <= y) and (x >= y))

# Statement 6
print(True and ((x < z) or (x < y)))
```

    False
    True
    False
    False
    True
    True


Excercise 16


```python
all([True, True, True]) #True
```




    True




```python
all([False, True, False]) #False
```




    False




```python
all([False, False, False]) #False
```




    False




```python
any([True, True, True]) #True
```




    True




```python
any([False, True, False]) #True
```




    True




```python
any([False, False, False]) #False
```




    False




```python

```
