# JavaT4

## 计G201 吴晓波

## 实验目的

* 掌握字符串String及其方法的使用
* 掌握文件的读取/写入方法
* 掌握异常处理结构


## 实验要求

* 设计学生类，包括学生基本信息
* 设计文件处理类，实现格式化输出诗句到文件
* 采用交互式方式实例化学生类

## 核心代码
```
char o = sc.next().charAt(0); //查找字符出现次数
char[] ch =str.toCharArray();
for(int i=0;i<ch.length;i++){
  if(o==ch[i]){
      count++;
         }
   }
```
```
for (int i=7,x=0; i<=14*17;i+=7,x+=7) { //输出诗句到文件

                if (i % 2 == 0) {
                    for (int j = x; j < i; j++) {
                        out.write(c[j]);
                    }
                    out.write("。\n");

                } else {
                    for (int j = x; j < i; j++) {
                        out.write(c[j]);
                    }
                    out.write(",");

                }
            }
```
## 实验结果

![](https://github.com/INHOPEKEEP/JavaT4/blob/main/picture/001.PNG)
![](https://github.com/INHOPEKEEP/JavaT4/blob/main/picture/002.PNG)

## 实验总结
通过这次实验，掌握了接口的定义和使用，如果要实现接口，得实现它的所有方法，抽象类也是这样。学会使用简单的Java的异常处理，Scanner类的使用。还有理解了static final的意义，
