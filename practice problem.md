```python
x1 = int(input("x1 죄표를 입력하시오 :"))
y1 = int(input("y1 죄표를 입력하시오 :"))
x2 = int(input("x2 죄표를 입력하시오 :"))
y2 = int(input("y2 죄표를 입력하시오 :"))
def area(x1,y1,x2,y2):
    print('직각삼각형의 면적은',(x2-x1)*(y2-y1)*0.5)
area(x1,y1,x2,y2)
    
```

    x1 죄표를 입력하시오 :0
    y1 죄표를 입력하시오 :0
    x2 죄표를 입력하시오 :3
    y2 죄표를 입력하시오 :4
    직각삼각형의 면적은 6.0
    


```python
def max2(m,n):
    if (m > n):
        print('{}과 {}중 큰 수는 : {}'.format(m,n,m))
    else:
        print('{}과 {}중 큰 수는 : {}'.format(m,n,n))
def min2(m,n):
    if (m < n):
        print('{}과 {}중 작은 수는 : {}'.format(m,n,m))
    else:
        print('{}과 {}중 큰 수는 : {}'.format(m,n,n))
max2(100,200)
min2(100,200)
```

    100과 200중 큰 수는 : 200
    100과 200중 작은 수는 : 100
    


```python
import math
x1 = int(input("x1 죄표를 입력하시오 :"))
y1 = int(input("y1 죄표를 입력하시오 :"))
x2 = int(input("x2 죄표를 입력하시오 :"))
y2 = int(input("y2 죄표를 입력하시오 :"))
def distance(x1,y1,x2,y2):
    a = x2-x1
    b = y2-y1
    print('두 점의 거리',math.sqrt(a*a+b*b))
distance(x1,y1,x2,y2)
    
```

    x1 죄표를 입력하시오 :0
    y1 죄표를 입력하시오 :0
    x2 죄표를 입력하시오 :3
    y2 죄표를 입력하시오 :4
    두 점의 거리 5.0
    


```python
a, b, c = map(int, input('세 수를 입력하세요: ').split())
alist = []
alist.append(a)
alist.append(b)
alist.append(c)
alist.sort()
print('정렬된 리스트는 다음과 같습니다: ',alist[0],alist[1],alist[2])
```

    세 수를 입력하세요: 3 2 5
    정렬된 리스트는 다음과 같습니다:  2 3 5
    


```python
width = int(input("밑변을 입력하시오: "))
height = int(input("높이를 입력하시오: "))
def cal_area(width,height):
    print('삼각형의 면적: ',width*height*0.5)
cal_area(width,height) 
```

    밑변을 입력하시오: 20
    높이를 입력하시오: 15
    삼각형의 면적:  150.0
    


```python

```
