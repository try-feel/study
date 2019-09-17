#第二章 JavaScript数据类型
### 2.1 数据类型的分类
2.1.1 基础数据类型
基础数据类型，也可以叫做简单数据类型或原始数据类型，通常表示某种值，对值进行比较。

2.1.2引用数据类型
引用数据类型，也可以叫做复杂数据类型，是键值对形式出现的，一属性和属性值构成，无序列表集合，在内存中占据独立的空间，任何连个独立的对象都不相等。

###2.2 基本数据类型
2.2.1 数字类型
Number类型，这种类型使用IEEE745格式来表示整数和浮点数，数字类型包括：整数，浮点数、NaN.Infinity.
数字范围：最小值5e-324，最大值2的53次方。
isNaN()方法用来验证该值是否为非数字，非数字返回值为ture，数字返回值为flase

    <script>
        var a = 10;
        var b = "10";
        console.log('a+b:'+ isNaN(a + b)); //false
        alert(isNaN(a - b));//false
        alert(isNaN(a * b));//false
        alert(isNaN(a / b));//false
        alert(isNaN(NaN));//true
    </script>

2.2.2 字符串类型
String类型是由引号括起来的一组16位Unicode字符组成的字符序列，字符串类型通常被用于表示文本数据。

        var a = '你好';
        var b =  "你们好";
        var c = '你好我叫"tom"';
字符串中反斜线有着特殊用途，用反斜线后面加一个特殊字符，就变为了转义字符，具备一些特殊用途。

2.2.3 布尔类型
Boolean类型，只有两个字面量值，分别是true和false，并且他们区分大小写，小写的是布尔类型的值。
数据类型中有以下数据类型转换后为false；
（1）false
（2）''空字符串
（3）+0和-0
（4）NaN
 (5)null
 (6)undefined

2.2.4null
Null类型，是一个对象，函数的参数，表示该函数不是对象，也可以当做空对象用。
     
    console.log(null+1);
    //null数字类型转换为0

2.2.5 undefined
 Undefined类型代表未定义，是变量的初始值，也是函数的默认返回值

        console.log(undefined+1);
        //undefined数字类型转换为NaN
 
###2.3 验证基础数据类型

### 2.4 数据类型转换