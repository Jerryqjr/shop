# CSS

## CSS基础

![image-20230803164433541](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20230803164433541.png)

![image-20230803164521214](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20230803164521214.png)

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Jerry</title>
    </head>
    <style>
        #p1{
            color:red;
            font-size: 33px;
        }
    </style>
    <body>
        <p id="p1">
            加油拿下实习
        </p>
    </body>
</html>
```



![image-20230803195525034](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20230803195525034.png)

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Jerry</title>
    </head>
    <style>
       a[href] {
        color: red;
       }
    </style>
    <body>
        <a href="www.baidu.com">百度1</a>
        <a href="www.baidu.com">百度2</a>
        <a>百度3</a>
    </body>
</html>
```

结果：

![image-20230803200158323](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20230803200158323.png)

## CSS常用属性

![image-20230803200815743](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20230803200815743.png)

## html中引入css的方式

![image-20230803203228385](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20230803203228385.png)

内联方式

![image-20230803203347477](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20230803203347477.png)

![image-20230803203445117](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20230803203445117.png)

## CSS&DIV布局

![image-20230803204849823](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20230803204849823.png)

![image-20230803205542544](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20230803205542544.png)

![image-20230803205937527](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20230803205937527.png)

![image-20230804094739560](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20230804094739560.png)

![image-20230804101517158](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20230804101517158.png)

![image-20230804103418388](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20230804103418388.png)

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Jerry</title>
        <style>
            body{
                margin: 15px;
                font-family: Arial;
                font-size:12px;
            }

            .father{
                background-color: red;
                border: 1px solid black;
                padding: 5px;
            }

            .father div{
                background-color: aqua;
                margin: 15px;
                border: 1px dashed black;
                padding: 5px;
            }

            .father p{
                background-color: chartreuse;
                border: 1px dashed yellow;
            }

            .son1{
                float:left;
            }
            .son2{
                float: left;
            }
            .son3{
                float: left;
            }
        </style>
    </head>

    <body>
        <div class="father">
            <div class="son1">Box-1</div>
            <div class="son2">Box-2</div>
            <div class="son3">Box-3</div>
            <p>这里是浮动框外围的文字</p>
        </div>
        </body>
</html>

```

结果：

![image-20230804104353417](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20230804104353417.png)

![image-20230804104233288](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20230804104233288.png)

![image-20230804114756842](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20230804114756842.png)

![image-20230804114846622](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20230804114846622.png)

