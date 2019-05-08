

```python
2+3
```




    5



## Dictionaries


```python
d1={'procedural':'c','scripting':'python','function':'haskel'}
```


```python
d1['scripting']
```




    'python'




```python
d1.values()
```




    dict_values(['c', 'python', 'haskel'])




```python
d1.keys()
```




    dict_keys(['procedural', 'scripting', 'function'])




```python
d2={'Symbolic':'Mathematics','logic':'prolog'}
d1.update(d2)
```


```python
d1['Object Oriented']='Java'
d1
```




    {'procedural': 'c',
     'scripting': 'python',
     'function': 'haskel',
     'Symbolic': 'Mathematics',
     'Object Oriented': 'Java',
     'logic': 'prolog'}




```python
d1['logic']
```




    'prolog'



### Problem 1:
#### Problem Statement:
For a given number,define a function to check if it is divisible by 2,3 but not 4

#### Constraints
Given number will be in the range [1,1000000000]

#### Test cases

* Test case 1: check the divisibility(6)-> True
* Test case 2: check the divisibility(16)-> False
* Test case 3: check the divisibility(20)-> False


```python
def checkdivisibility(n):
    if(n%2==0 and n%3==0 and n%4!=0):
        return True
    else:
        return False
checkdivisibility(16)
```




    False




```python

```
