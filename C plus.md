# C plus

## 基本语法

using namespace std作用是声明std空间，这个使用就是调用c plus语法,不然直接使用cout要报错 ,要加std::cout

## 数据类型

### wchar_t 

新增:宽字符   wchar_t 通常占用2个或4个字节

### union

union即为联合，它是一种特殊的类。通过[关键字](https://so.csdn.net/so/search?q=关键字&spm=1001.2101.3001.7020)union进行定义，一个union可以有多个数据成员。

```c++
union U
{
	char b[3];
	int num;
}
int main()
{
    U x;
    x.num = 64;
    x.b
}
```

### const

使用 **const** 前缀声明指定类型的常量

```c++
const type variable = value;
```

