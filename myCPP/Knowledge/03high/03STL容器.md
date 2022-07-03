# 3. STL-常用容器

## 3.1 string容器

### 3.1.1 string基本概念

#### 本质

- string是C++风格的字符串，而string本质上是一个类

#### string和char*区别

- char* 是一个指针
- string 是一个类，类内部封装了char*，管理这个字符串，是一个char*型的容器

#### 特点

- string类内部封装了很多成员方法
- string管理char*所分配的内存，不用担心赋值越界和取值越界等，由类内部进行负责

### 3.1.2 string构造函数

1. string(); 创建一个空的字符串
2. string(const char* s); 使用字符串s初始化
3. string(const string& str); 使用一个string对象初始化另一个string对象
4. string(int n, char c); 使用n个字符c初始化

### 3.1.3 string赋值操作

1. string = ;
2. string.assign();

### 3.1.4 string字符串拼接

1. string += ;
2. string.append();

### 3.1.5 string查找和替换

- 查找：查找指定字符串是否存在  str.find();
- 替换：在指定的位置替换字符串  str.replace();

#### 总结

- find查找是从左往右，rfind是从右往左
- find找到字符串后返回超找的第一个字符位置，找不到返回-1
- replace在替换时，要指定从哪个位置起，多少个字符，替换成什么样的字符串

### 3.1.6 string字符串比较

- 字符串比较是按照字符的ascii码进行对比
- 相等返回0，大于返回1，小于返回-1
- str.compare();
- 主要作用用来比较是否相等

### 3.1.7 string字符存取

1. str.at(i);
2. str[i];

### 3.1.8 string插入和删除

1. str.insert();
2. str.erase();
3. 插入和删除的其实下标都是从0开始

### 3.1.9 string 子串

1. str.substr()

## 3.2 vector容器

### 3.2.1 vector基本概念

#### 功能

- vector数据结构和数组非常相似，也称为单端数组

#### vector与普通数组区别

- 不同之处在于数组是静态空间，而vector可以动态扩展

#### 动态扩展

- 并不是在原空间之后续接新空间，而是找到更大的内存空间，然后将元数据拷贝新空间，释放原空间
- vector容器的迭代器是支持随机访问的迭代器

### 3.2.2 vector构造函数

1. `vector<T> v1;`
2. `vector<T> v2(v1.begin(), v1.end());` 前闭后开

### 3.2.3 vector赋值操作

### 3.2.4 vector容量和大小

1. empty();             判断容器是否为空，空为1
2. capacity();          容器的容量
3. size();              返回容器中元素的个数
4. resize(int num);     重新指定大小

### 3.2.5 vector插入和删除

1. push_back();         尾部插入
2. pop_back();          删除最后一个元素
3. insert(pos, ele);    指定位置插入元素ele
4. erase(pos);          删除指定位置元素
5. clear();             删除所有

### 3.2.6 vector数据存取

- a[i]      第i个元素

### 3.2.7 vector互换容器

- 函数原型：swap(vec);

### 3.2.8 vector预留空间

- reserve(int len);

## 3.3 deque容器

### 3.3.1 deque容器基本概念

#### 作用

- 双端数组，可以对头端进行插入删除操作

#### deque与vector区别

1. vector对于头部的插入删除效率低，数据量越大，效率越低
2. deque对头部的插入删除速度会比vector快
3. vector访问元素时的速度会比deque快

### 3.3.2 deque构造函数

### 3.3.3 deque赋值操作

### 3.3.4 deque大小操作

- deque没有容量的概念

### 3.3.5 deque插入和删除

- 插入和删除提供的位置是迭代器，索引没有用

### 3.3.6 deque数据存取

### 3.3.7 deque排序

- sort(iterator beg, iterator end);

## 3.4 案例-评委打分
