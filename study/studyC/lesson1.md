本节主要总结指针与其他类型的关系。结合内存图形</br>
指针是一种数据类型。指针的实质就是地址。
每一个变量、数组、函数在内存中都对应一段内存空间，而这段内存空间。而这段内存空间的首地址位置，就是变量、数组、函数的指针位置。
**怎么获取地址？**
C语言中提供了一个特殊的运算符：&寻址运算符。
C语言中提供了一个特殊的运算符：*寻值运算符。

···
int main(void){
    //声明一个变量
    int a = 100;
    //使用&寻址运算符
    printf("a 的内存地址：%p\n",&a);
}

···


**XX指针为指针，指针是别名**。

## 指针与变量
变量声明与初始化：</br>
int a = 0;
#### 指针变量
指针变量是变量，它的类型是指针类型。可以理解为(int *)p
int * p = &a;
#### 变量指针
变量指针是指针，是变量的别名。
int (*p) = 

## 指针与常量
#### 指针常量
#### 常量指针

## 指针与数组
#### 指针数组
#### 数组指针
