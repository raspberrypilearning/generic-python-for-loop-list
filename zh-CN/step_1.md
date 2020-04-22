应用 **for loop** 来显示列表`animals`中的每个项目。

```python
animals = ["fox", "wolf", "panda", "squirrel"] #表示列表‘animals’包含 [“狐狸”，“狼”，“熊猫”，“松鼠”] 

for animal in animals: #在列表‘animals’中循环寻找每一个动物
  print(animal) #显示列表中的动物
```

输出为：

    fox #狐狸
    wolf #狼
    panda #熊猫
    squirrel #松鼠
    

请注意，`print`代码行起始点较为偏右。 这称为缩进**indentation** ，这一缩进**indented**说明这行在循环内。 循环中的任何代码，都会随着循环重复。