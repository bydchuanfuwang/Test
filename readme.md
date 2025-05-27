#print("hello world")

# 类型

```python
num = -10
print(type(num))

num2 = 10.5
print(type(num2))

Temp = True
print(type(Temp))

ma = 1+2j#j是固定的，不能替换成i
print(type(ma))

temp = "sixStar"
print(temp)#字符串类型
```

# 格式化输出v
```
temp = "test"
age = 20
print("name: %s, age: %d" % (temp,age))
print(f"name: {temp}, age: {age}")
a = 1.23456789
print("%f"% a)# %f默认7位四舍五入
```