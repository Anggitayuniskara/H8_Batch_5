```python
print(1111112222233333+1)
```

    1111112222233334
    


```python
print(10)
print(type(10))
```

    10
    <class 'int'>
    


```python
print(4.2)
print(type(4.2))

print(4.)

print(.2)

print(.4e7)

print(4.2e-4)
```

    4.2
    <class 'float'>
    4.0
    0.2
    4000000.0
    0.00042
    


```python
print("Hacktiv8")
print(type("Hacktiv8")
```


      Cell In[4], line 2
        print(type("Hacktiv8")
                              ^
    SyntaxError: incomplete input
    



```python
print("Hacktiv8")
```

    Hacktiv8
    


```python
print(type("Hacktiv8"))
```

    <class 'str'>
    


```python
print('')
```

    
    


```python
print("This string contains a single quote (') character.")
print('This string contains a double quote (") character.')
```

    This string contains a single quote (') character.
    This string contains a double quote (") character.
    


```python
display('Hello World')
print('Hello World')
print(type("apa"))
print('"Hello World"')
print("Can't")
print('"She" knows')
print('''"She" knows she can't do it"''')
```


    'Hello World'


    Hello World
    <class 'str'>
    "Hello World"
    Can't
    "She" knows
    "She" knows she can't do it"
    


```python
print(type(True))
print(type(False))
```

    <class 'bool'>
    <class 'bool'>
    


```python
print(True)
print(False)

print(True+False)
print(True+True)
print(False+False)
```

    True
    False
    1
    2
    0
    


```python
n = 300
print(n)
```

    300
    


```python
n
```




    300




```python
n = 1000
print(n)




n
```

    1000
    




    1000




```python
a = b = c = 300
print(a, b, c)
```

    300 300 300
    


```python
var = 23.5
print(var)

var = "Now I'm a String"
print(var)
```

    23.5
    Now I'm a String
    


```python
a = 'a'

a
```




    'a'




```python
name = "Hacktiv8"
Age = 54
has_laptops = True

print(name, Age, has_laptops)
```

    Hacktiv8 54 True
    


```python
9_kepala_naga = True
```


      Cell In[26], line 1
        9_kepala_naga = True
         ^
    SyntaxError: invalid decimal literal
    



```python
age = 1
Age = 2
aGe = 3
AGE = 4
a_g_e = 5
_age = 6
age_ = 7
_AGE_ = 8

print (age, Age, aGe, AGE, a_g_e, _age, age_, _AGE_)
```

    1 2 3 4 5 6 7 8
    


```python
a = 10
b = 20 
print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a // b)
```

    30
    -10
    200
    0.5
    0
    


```python
a = 9
b = 10
print(a + b) # penjumlahan
print(a - b) # pengurangan
print(a * b) # perkalian
print(a / b) # pembagian desimal
print(a // b) # pembagian integer
print(a ** b) # pangkat
print(a % b) # modula
print(a + b + 10)
```

    19
    -1
    90
    0.9
    0
    3486784401
    9
    29
    


```python
10 / 5
```




    2.0




```python
a = 10
b = 20
print(a == b) # sama dengan

print(a != b) # tidak sama dengan

print(a <= b)

print(a >= b)
```

    False
    True
    True
    False
    


```python
a = 30
b = 30

print(a == b) # sama dengan
print(a <= b) # kecil dari sama dengan
print(a >= b) # besar dari sama dengan
```

    True
    True
    True
    


```python
q = 'Py'
w = 'thon'
print(q + w)
print('Hacktiv' + '8')
print(q * a)
print(q in 'Python')
print(w in 'Zodiac')
```

    Python
    Hacktiv8
    PyPyPyPyPyPyPyPyPyPy
    True
    False
    


```python
s = 'foo'
t = 'bar'
u = 'baz'

print(s + t)
print(s + t + u)
print('Hacktiv8 ' + 'PTP')
```

    foobar
    foobarbaz
    Hacktiv8 PTP
    


```python
s = 'foo.'

s * 3
```




    'foo.foo.foo.'




```python
s = 'foo'

print(s in 'food for us')
print(s in 'good for us')
```

    True
    False
    


```python
s = 'Hacktiv8' 

print(s.capitalize())

print(s.lower())

print(s.swapcase())

print(s.title())

print(s.upper())
```

    Hacktiv8
    hacktiv8
    hACKTIV8
    Hacktiv8
    HACKTIV8
    


```python
a = ['foo', 'bar', 'baz', 'qux']

print(a)
```

    ['foo', 'bar', 'baz', 'qux']
    


```python
a = ['foo', 'bar', 'baz', 'qux']
b = ['baz', 'qux', 'bar', 'foo']
a == b
```




    False




```python
a = [21.42, 'foobar', 3, 4, 'bark', False, 3.14159]
print(a)
```

    [21.42, 'foobar', 3, 4, 'bark', False, 3.14159]
    


```python
a
```




    [21.42, 'foobar', 3, 4, 'bark', False, 3.14159]




```python
#index ke 0  1  2    3    4           5            6    7   8  9  10 
daftar = [1, 2, 43, 'a', True, ['b', 300, False], 4.6, 1+1, a, q, w]
#index minus                                               -3 -2 -1
print(daftar)
print(type(daftar))
print(daftar[3])
print(daftar[5])
print(daftar[7])
print(daftar[-3])
print(daftar[1:6])
print(daftar + ['python', 'KS'])
```

    [1, 2, 43, 'a', True, ['b', 300, False], 4.6, 2, [21.42, 'foobar', 3, 4, 'bark', False, 3.14159], 'Py', 'thon']
    <class 'list'>
    a
    ['b', 300, False]
    2
    [21.42, 'foobar', 3, 4, 'bark', False, 3.14159]
    [2, 43, 'a', True, ['b', 300, False]]
    [1, 2, 43, 'a', True, ['b', 300, False], 4.6, 2, [21.42, 'foobar', 3, 4, 'bark', False, 3.14159], 'Py', 'thon', 'python', 'KS']
    


```python
a =  ['foo', 'bar', 'baz', 'qux', 'quux', 'corge']
#index 0       1      2      3       4       5 
#index -6     - 5    -4     -3      -2      -1 
print(a)
```

    ['foo', 'bar', 'baz', 'qux', 'quux', 'corge']
    


```python
print(a[0])
print(a[5])
```

    foo
    corge
    


```python
print(a[-1])
print(a[-6])
```

    corge
    foo
    


```python
a = ['foo', 'bar', 'baz', 'qux', 'quux', 'corge']
a[2:5]
```




    ['baz', 'qux', 'quux']




```python
print(a)

print(a + ['grault', 'garply'])
print(a * 2)
```

    ['foo', 'bar', 'baz', 'qux', 'quux', 'corge']
    ['foo', 'bar', 'baz', 'qux', 'quux', 'corge', 'grault', 'garply']
    ['foo', 'bar', 'baz', 'qux', 'quux', 'corge', 'foo', 'bar', 'baz', 'qux', 'quux', 'corge']
    


```python
print(a)
print(len(a))
print(min(a))
print(max(a))
```

    ['foo', 'bar', 'baz', 'qux', 'quux', 'corge']
    6
    bar
    qux
    


```python
a = ['foo', 'bar', 'baz', 'qux', 'quux', 'corge']

print(a)
a[2] = 10
a[-1] = 20

print(a)
```

    ['foo', 'bar', 'baz', 'qux', 'quux', 'corge']
    ['foo', 'bar', 10, 'qux', 'quux', 20]
    


```python
del a[3]
```


```python
print(a)
```

    ['foo', 'bar', 10, 'quux', 20]
    


```python
daftar = [1, 2, 43, 'a', True, ['b', 300, False], 4.6, 1+1, a, q, w] 
print(daftar)
daftar[-2] = 'udah malem'
print(daftar)
del daftar[3]
print(daftar)
daftar[3:]
daftar[8] = 'py'
```

    [1, 2, 43, 'a', True, ['b', 300, False], 4.6, 2, ['foo', 'bar', 10, 'quux', 20], 'Py', 'thon']
    [1, 2, 43, 'a', True, ['b', 300, False], 4.6, 2, ['foo', 'bar', 10, 'quux', 20], 'udah malem', 'thon']
    [1, 2, 43, True, ['b', 300, False], 4.6, 2, ['foo', 'bar', 10, 'quux', 20], 'udah malem', 'thon']
    


```python
#index ke 0  1  2    3    4           5            6    7   8  9  10 
daftar = [1, 2, 43, 'a', True, ['b', 300, False], 4.6, 1+1, a, q, w]
#index minus                                               -3 -2 -1
print(daftar)
print(type(daftar))
print(daftar[3])
print(daftar[5])
print(daftar[7])
print(daftar[-3])
print(daftar[1:6])
print(daftar + ['python', 'KS'])
```

    [1, 2, 43, 'a', True, ['b', 300, False], 4.6, 2, ['foo', 'bar', 10, 'quux', 20], 'Py', 'thon']
    <class 'list'>
    a
    ['b', 300, False]
    2
    ['foo', 'bar', 10, 'quux', 20]
    [2, 43, 'a', True, ['b', 300, False]]
    [1, 2, 43, 'a', True, ['b', 300, False], 4.6, 2, ['foo', 'bar', 10, 'quux', 20], 'Py', 'thon', 'python', 'KS']
    


```python
a = ['foo', 'bar', 'baz', 'qux', 'quux', 'corge']

print(a[1:4])

a[1:4] = [1.1, 2.2, 3.3, 4.4, 5.5]
print(a)
```

    ['bar', 'baz', 'qux']
    ['foo', 1.1, 2.2, 3.3, 4.4, 5.5, 'quux', 'corge']
    


```python
t = ('foo', 'bar', 'baz', 'qux', 'quux', 'corge')
print(t)
```

    ('foo', 'bar', 'baz', 'qux', 'quux', 'corge')
    


```python
print(t[0])
print(t[-1])
```

    foo
    corge
    


```python
(s1, s2, s3, s4) = ('foo', 'bar', 'baz', 'qux')
s1
```




    'foo'




```python
MLB_team = {
    'Colorado': 'Rockies', 
    'Boston': 'Red Sox',
    'Minnesota': 'Twins', 
    'Milwaukee': 'Brewers', 
    'Seattle': 'Mariners'
}

print(MLB_team['Minnesota'])
print(MLB_team['Colorado'])
```

    Twins
    Rockies
    


```python
MLB_team['Kansas City'] = 'Royals'
MLB_team
```




    {'Colorado': 'Rockies',
     'Boston': 'Red Sox',
     'Minnesota': 'Twins',
     'Milwaukee': 'Brewers',
     'Seattle': 'Mariners',
     'Kansas City': 'Royals'}




```python
MLB_team['Seattle'] = 'Seahawks'
MLB_team
```




    {'Colorado': 'Rockies',
     'Boston': 'Red Sox',
     'Minnesota': 'Twins',
     'Milwaukee': 'Brewers',
     'Seattle': 'Seahawks',
     'Kansas City': 'Royals'}




```python
del MLB_team['Seattle']
MLB_team
```




    {'Colorado': 'Rockies',
     'Boston': 'Red Sox',
     'Minnesota': 'Twins',
     'Milwaukee': 'Brewers',
     'Kansas City': 'Royals'}




```python
kamus = {
    'apa':'what', 'siapa':'who', 'bagaimana':'how'
}

print(kamus)
print(type(kamus))
print(kamus['apa'])
kamus['siapa']
```

    {'apa': 'what', 'siapa': 'who', 'bagaimana': 'how'}
    <class 'dict'>
    what
    




    'who'




```python
alamat = {}

alamat['kota'] = ['madagascar']
alamat['jalan'] = 'situ baru'
alamat['nomor rumah'] = 10
alamat['pohon'] = ['cendana', 'mahoni', 'beringin']
alamat['akses'] = {'KRL':'bisa', 'TJ':'bisa', 'ojol':'tidak'}

alamat
```




    {'kota': ['madagascar'],
     'jalan': 'situ baru',
     'nomor rumah': 10,
     'pohon': ['cendana', 'mahoni', 'beringin'],
     'akses': {'KRL': 'bisa', 'TJ': 'bisa', 'ojol': 'tidak'}}




```python
print(alamat)
print(alamat['pohon'][1])
print(alamat['akses']['TJ'])
```

    {'kota': ['madagascar'], 'jalan': 'situ baru', 'nomor rumah': 10, 'pohon': ['cendana', 'mahoni', 'beringin'], 'akses': {'KRL': 'bisa', 'TJ': 'bisa', 'ojol': 'tidak'}}
    mahoni
    bisa
    


```python
print(alamat)
```

    {'kota': ['madagascar'], 'jalan': 'situ baru', 'nomor rumah': 10, 'pohon': ['cendana', 'mahoni', 'beringin'], 'akses': {'KRL': 'bisa', 'TJ': 'bisa', 'ojol': 'tidak'}}
    


```python

```


```python
alamat = {}

alamat['kota'] = ['madagascar']
alamat['jalan'] = 'situ baru'
alamat['nomor rumah'] = 10
alamat['pohon'] = ['cendana', 'mahoni', 'beringin']
alamat['akses'] = {'KRL':'bisa', 'TJ':{'bisa':'tapi susah'}, 'ojol':'tidak'}

alamat['akses']['TJ']['bisa']
```




    'tapi susah'




```python
person = {}
type(person)
```




    dict




```python
person['fname'] = 'Hack'
person['lname'] = 'PTP' 
person['age'] = 51
person['spouse'] = 'Edna' 
person['children'] = ['Ralph', 'Betty', 'Joey'] 
person['pets'] = {'dog' : 'Fido', 'cat' : 'Sox'}

print(person)
```

    {'fname': 'Hack', 'lname': 'PTP', 'age': 51, 'spouse': 'Edna', 'children': ['Ralph', 'Betty', 'Joey'], 'pets': {'dog': 'Fido', 'cat': 'Sox'}}
    


```python
person
```




    {'fname': 'Hack',
     'lname': 'PTP',
     'age': 51,
     'spouse': 'Edna',
     'children': ['Ralph', 'Betty', 'Joey'],
     'pets': {'dog': 'Fido', 'cat': 'Sox'}}




```python
print(person['fname'])
print(person['lname'])
```

    Hack
    PTP
    


```python
print(person['children'])
print(person['children'][1])
```

    ['Ralph', 'Betty', 'Joey']
    Betty
    


```python
person1_age = 42
person2_age = 16
person3_age = 71

someone_is_of_working_age = (person1_age >=18 and person1_age <=65) or (person2_age >=18 and person2_age <=65) or (person3_age >=18 and person3_age <=65) 
someone_is_of_working_age
```




    True




```python
someone_is_of_working_age = (person2_age >= 18 and person2_age <=65)
someone_is_of_working_age
```




    False




```python
someone_is_of_working_age = (person3_age >=18 and person3_age <=65)
someone_is_of_working_age
```




    False




```python
someone_is_of_working_age
```




    False




```python

```
