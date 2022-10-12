```python
def print_star():
    print('**********************')
```


```python
def print_star():
    print('**********************')
print_star()
print_star()
print_star()
print_star()
print_star()
print_star()
```

    **********************
    **********************
    **********************
    **********************
    **********************
    **********************
    


```python
def print_star5():
    for i in range(5):
        print('**********************')
    
print_star5()
print_star5()
```

    **********************
    **********************
    **********************
    **********************
    **********************
    **********************
    **********************
    **********************
    **********************
    **********************
    


```python
def print_star():
    print('**********************')
def print_plus():
    print('++++++++++++++++++++++')
def print_hash():
    print('######################')
print_hash()  
print_star() 
print_plus()
print_plus()
print_star() 
print_hash()
```

    ######################
    **********************
    ++++++++++++++++++++++
    ++++++++++++++++++++++
    **********************
    ######################
    


```python
def print_star(n):
    for _ in range(n):
        print('************************')
print_star(10) 
```

    ************************
    ************************
    ************************
    ************************
    ************************
    ************************
    ************************
    ************************
    ************************
    ************************
    


```python
def print_hash(n):
    for _ in range(n):
        print('#######################')
print_hash(10) 
print('\n')
print_hash(6) 

def print_hash(n):
    for _ in range(n):
        print(_,'#######################')
print_hash(6) 
```

    #######################
    #######################
    #######################
    #######################
    #######################
    #######################
    #######################
    #######################
    #######################
    #######################
    
    
    #######################
    #######################
    #######################
    #######################
    #######################
    #######################
    0 #######################
    1 #######################
    2 #######################
    3 #######################
    4 #######################
    5 #######################
    


```python
def print_sub(a,b):
    return print(a,'과 ',b,'의 ','차는 ',a -b,'입니다.',sep='')
print_sub(10,20)
def print_sum(a,b):
    return print(a,'과 ',b,'의 ','차는 ',a +b,'입니다.',sep='')
print_sum(10,20)
def print_mult(a,b):
    return print(a,'과 ',b,'의 ','차는 ',a *b,'입니다.',sep='')
print_mult(10,20)
```

    10과 20의 차는 -10입니다.
    10과 20의 차는 30입니다.
    10과 20의 차는 200입니다.
    


```python
def print_root(a,b,c):
    r1 = (-b+(b**2-4*a*c)**0.5)/(2*a)
    r2 = (-b-(b**2-4*a*c)**0.5)/(2*a)
    print('해는', r1, '또는', r2)
print_root(1,4,-21)
print_root(1,-6,8)
def print_area(w,h):
    return print('밑변',w,' , ','높이 ',h,'인 삼각형의 면적은 : ',int(w * h /2),sep='')
print_area(10,20)
```

    해는 3.0 또는 -7.0
    해는 4.0 또는 2.0
    밑변10 , 높이 20인 삼각형의 면적은 : 100
    


```python
def circle_area_circum(radius):
    area = radius * radius * 3.14
    circum = 2 * 3.14 * radius
    return area,circum
radius = 10
area, circum = circle_area_circum(radius)
print('반지름 ',radius,'인 원의 면적은 ',area,'원의 둘레는 ','%.1f'%circum,sep='')
```

    반지름 10인 원의 면적은 314.0원의 둘레는 62.8
    


```python

def muliples(n,m):
    l2 =[]
    for i in range(m):
        l2.append((i+1)*n)
    return l2
                               

r1,r2,r3,r4= muliples(3,4)
print(r1,r2,r3,r4)
                               

r1,r2,r3,r4,r5= muliples(2,5)
print(r1,r2,r3,r4,r5)
```

    3 6 9 12
    2 4 6 8 10
    


```python
def print_name(honorifics,first_name,last_name):
    print(honorifics,first_name,last_name)
print_name(first_name='Gildong',last_name='Hong',honorifics='Dr')
print_name('Gildong','Hong','Dr.') 
```

    Dr Gildong Hong
    Gildong Hong Dr.
    


```python
def sum_nums(*numbers):
    result = 0
    for n in numbers:
        result += n
    
    av = result / len(numbers)
    
    print(len(numbers),'개의 인자',numbers,'\n합계 :',result,', 평균 :',av)
print(sum_nums(10, 20, 30)) 

print(sum_nums(10, 20, 30, 40, 50))
def min_nums(*numbers):
    min = 1000000
    for i in nubers:
        if(i < min):
            min = i
    print("최솟값은 ",min)
print(min_nums(20,40,50,10))
```

    3 개의 인자 (10, 20, 30) 
    합계 : 60 , 평균 : 20.0
    None
    5 개의 인자 (10, 20, 30, 40, 50) 
    합계 : 150 , 평균 : 30.0
    None
    최솟값은  10
    None
    


```python
name = input('당신의 이름을 입력해주세요 :')
age = input('나이를 입력해주세요 :')
job = input('직업을 입력해 주세요 :')
place = input('사는 곳을 입력해 주세요 :')

print('당신의 이름은 {},나이는 {}살,직업은 {},사는 곳은 {}입니다.'.format(name,age,job,place))
```

    당신의 이름을 입력해주세요 :김철수
    나이를 입력해주세요 :21
    직업을 입력해 주세요 :학생
    사는 곳을 입력해 주세요 :창원시
    당신의 이름은 김철수,나이는 21살,직업은 학생,사는곳은 창원시입니다.
    


```python
'_'.join("ABCD")
```




    'A_B_C_D'




```python
s = 'My favorite thing is monsters.'
t = s.replace('monsters','cartoons')
t
```




    'My favorite thing is cartoons.'




```python

```
