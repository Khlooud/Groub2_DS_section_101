```python
# Check the Python Version
import sys
print ("WELCOME VER")
print(sys.version)
```

    WELCOME VER
    3.9.7 (default, Sep 16 2021, 16:59:28) [MSC v.1916 64 bit (AMD64)]
    


```python
#Type of 12 
type(12)
```




    int




```python
#Type of 2.14 
type(2.14)
```




    float




```python
# Type of "Hello, Python 101!" 
type("Hello, Python 101!")
```




    str




```python
# Print the type of -1
type(-1)
```




    int




```python
# Print the type of 4
type(4) 
```




    int




```python
# Print the type of 0
type(0)

```




    int




```python
# Print the type of 1.0
type(1.0) # Notice that 1 is an int, and 1.0 is a float
```




    float




```python
#Print the type of 0.5
type(0.5)
```




    float




```python
# System settings about float type
sys.float_info
```




    sys.float_info(max=1.7976931348623157e+308, max_exp=1024, max_10_exp=308, min=2.2250738585072014e-308, min_exp=-1021, min_10_exp=-307, dig=15, mant_dig=53, epsilon=2.220446049250313e-16, radix=2, rounds=1)




```python
# Addition operation expression
43 + 60 + 16 + 41
```




    160




```python
# Subtraction operation expression
50 - 60
```




    -10




```python
# Mathematical expression 
30 + 2 * 60
```




    150




```python
# Sample List
["Michael Jackson", 10.1, 1982, [1, 2], ("A", 1)]
```




    ['Michael Jackson', 10.1, 1982, [1, 2], ('A', 1)]




```python
# Overwrite variable with new value
x = x / 60
x
```




    2.6666666666666665




```python
# Name the variables meaningfully

total_min = 43 + 42 + 57 # Total length of albums in minutes
total_min
```




    142




```python
# Name the variables meaningfully

total_hours = total_min / 60 # Total length of albums in hours
total_hours
```




    2.3666666666666667




```python
# Complicate expression
total_hours = (43 + 42 + 57) / 60 # Total hours in a single expres sion
total_hours
```




    2.3666666666666667




```python
# Create your first tuple
tuple1 = ("disco",10,1.2 )
tuple1
```




    ('disco', 10, 1.2)




```python
# Print the type of the tuple you created
type(tuple1)
```




    tuple




```python
# Print the variable on each index
print(tuple1[0])
print(tuple1[1])
print(tuple1[2])
```

    disco
    10
    1.2
    


```python
# Print the type of value on each index
print(type(tuple1[0]))
print(type(tuple1[1]))
print(type(tuple1[2]))
```

    <class 'str'>
    <class 'int'>
    <class 'float'>
    


```python
# Use negative index to get the value of the last element
tuple1[-1]
```




    1.2




```python
# Concatenate two tuples
tuple2 = tuple1 + ("hard rock", 10)
tuple2
```




    ('disco', 10, 1.2, 'hard rock', 10)




```python
# sample tuple
genres_tuple = ("pop", "rock", "soul", "hard rock", "soft rock", \
                           "R&B", "progressive rock", "disco")
genres_tuple
```




    ('pop',
     'rock',
     'soul',
     'hard rock',
     'soft rock',
     'R&B',
     'progressive rock',
     'disco')




```python
# Create a list
L = ["Michael Jackson", 10.1, 1982]
L
```




    ['Michael Jackson', 10.1, 1982]




```python
# Print the elements on each index

print('the same element using negative and positive indexing:\n Postive:',L[0],
'\n Negative:' , L[-3] )
print('the same element using negative and positive indexing:\n Postive:',L[1],
'\n Negative:' , L[-2] )
print('the same element using negative and positive indexing:\n Postive:',L[2],
'\n Negative:' , L[-1] )
```

    the same element using negative and positive indexing:
     Postive: Michael Jackson 
     Negative: Michael Jackson
    the same element using negative and positive indexing:
     Postive: 10.1 
     Negative: 10.1
    the same element using negative and positive indexing:
     Postive: 1982 
     Negative: 1982
    


```python
# Use extend to add elements to list
L = [ "Michael Jackson", 10.2]
L.extend(['pop', 10])
L
```




    ['Michael Jackson', 10.2, 'pop', 10]




```python
# Change the element based on the index

A = ["disco", 10, 1.2]
print('Before change:', A)
A[0] = 'hard rock'
print('After change:', A)
```

    Before change: ['disco', 10, 1.2]
    After change: ['hard rock', 10, 1.2]
    


```python
# Copy (copy by reference) the list A

A = ["hard rock", 10, 1.2] 
B= A
print('A:', A)
print('B:', B)
```

    A: ['hard rock', 10, 1.2]
    B: ['hard rock', 10, 1.2]
    


```python
print('B[0]:', B[0]) 
A[0] = "hard rock"
print('B[0]:', B[0])
```

    B[0]: hard rock
    B[0]: hard rock
    


```python
# Write your code below and press Shift+Enter to execute
a_list = [1, 'hello', [1,2,3], True]
a_list
```




    [1, 'hello', [1, 2, 3], True]




```python
# Write your code below and press Shift+Enter to execute
a_list[1]
```




    'hello'




```python
# Write your code below and press Shift+Enter to execute
a_list[1:4]
```




    ['hello', [1, 2, 3], True]




```python
# Write your code below and press Shift+Enter to execute
A=[1,'a']
B=[2,1,'d']
C=A+B
C
```




    [1, 'a', 2, 1, 'd']




```python
# Question sample dictionary
soundtrack_dic = {"The Bodyguard":"1992", "Saturday Night Fever":"1977"}
soundtrack_dic
```




    {'The Bodyguard': '1992', 'Saturday Night Fever': '1977'}




```python
# Write your code below and press Shift+Enter to execute
soundtrack_dic.keys() # The Keys are "The Bodyguard" and "Saturday Night Fever"
```




    dict_keys(['The Bodyguard', 'Saturday Night Fever'])




```python
# Write your code below and press Shift+Enter to execute
soundtrack_dic.values()  # The values are '1992'and '1977'
```




    dict_values(['1992', '1977'])




```python
# Write your code below and press Shift+Enter to execute
SetX = {'rap','house', 'electronic music', 'rap'}
print(SetX)

listY = ['rap','house', 'electronic music', 'rap']
SetY = set(listY)
print(SetY)

SetZ = set(['rap','house', 'electronic music', 'rap'])
print(SetZ)
```

    {'house', 'rap', 'electronic music'}
    {'house', 'rap', 'electronic music'}
    {'house', 'rap', 'electronic music'}
    


```python
# Write your code below and press Shift+Enter to execute
A = [1, 2, 2, 1]
B = set([1, 2, 2, 1])
print(sum(A))
print(sum(B))
```

    6
    3
    


```python
 # Write your code below and press Shift+Enter to execute

album_set1 = set(["Thriller", 'AC/DC', 'Back in Black'])
album_set2 = set([ "AC/DC", "Back in Black", "The Dark Side of the Moon"])
album_set3 = album_set1.union(album_set2)
album_set3
```




    {'AC/DC', 'Back in Black', 'The Dark Side of the Moon', 'Thriller'}




```python
# Write your code below and press Shift+Enter to execute
album_set1.issubset(album_set3)
```




    True




```python
# Condition statement example 

album_year = 1990

if(album_year < 1980) or (album_year > 1989):
    print ("Album was not made in the 1980's")
else:
    print("The Album was made in the 1980's ")
```

    Album was not made in the 1980's
    


```python
# Condition statement example
album_year = 1983

if not (album_year == '1984'):
    print ("Album year is not 1984")
```

    Album year is not 1984
    


```python
# Condition statement example 

album_year = 1983
#album_year = 1970

if album_year > 1980:
    print("Album year is greater than 1980")
else:
    print("less than 1980")
print('do something..')
```

    Album year is greater than 1980
    do something..
    


```python
# Else statement example

age = 8
# age = 19

if age > 18:
    print("you can enter" )
else:
    print("go see Meat Loaf" )
print("move on")
```

    go see Meat Loaf
    move on
    


```python
# For loop example

dates = [1982,1980,1973]
N = len(dates)

for i in range(N):
            print(dates[i])
```

    1982
    1980
    1973
    


```python
# Example of for loop 

for i in range(0, 8):
    print(i)
```

    0
    1
    2
    3
    4
    5
    6
    7
    


```python
# Loop through the list and iterate on both index and element value

squares=['red', 'yellow', 'green', 'purple', 'blue']

for i, square in enumerate(squares): 
    print(i, square)
```

    0 red
    1 yellow
    2 green
    3 purple
    4 blue
    


```python
# Write your code below and press Shift+Enter to execute
for i in range(-4, 5):
    print(i)
```

    -4
    -3
    -2
    -1
    0
    1
    2
    3
    4
    


```python
# Write your code below and press Shift+Enter to execute 
Genres = ['rock', 'R&B', 'Soundtrack', 'R&B', 'soul', 'pop'] 
for Genre in Genres:
    print(Genre)
```

    rock
    R&B
    Soundtrack
    R&B
    soul
    pop
    


```python
# Write your code below and press Shift+Enter to execute
PlayListRatings = [10, 9.5, 10, 8, 7.5, 5, 10, 10]
i=0
Rating = PlayListRatings[0]
while(i < len(PlayListRatings) and Rating >= 6): 
    Rating = PlayListRatings[i]
    print(Rating)
    i=i+1
```

    10
    9.5
    10
    8
    7.5
    5
    


```python
#  function that divides the first input by the second input:
def divide(a,b):
    c=a/b
    return c
c=divide(10,5)
print("function that divides the first input by the second input:",c)

```

    function that divides the first input by the second input: 2.0
    


```python
# the con function we defined before be used to add to integers or strings?
con("python","programming")
con(2,3)
```




    5


