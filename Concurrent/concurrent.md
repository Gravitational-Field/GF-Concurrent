

## 1. 并发与高并发

![image-20210315100036946](img/concurrent/image-20210315100036946.png)



![image-20210315100058125](img/concurrent/image-20210315100058125.png)



![image-20210315100204671](img/concurrent/image-20210315100204671.png)



![image-20210315104545581](img/concurrent/image-20210315104545581.png)



![image-20210315100401836](img/concurrent/image-20210315100401836.png)



![image-20210315104201279](img/concurrent/image-20210315104201279.png)

![image-20210315104236377](img/concurrent/image-20210315104236377.png)



OOM异常：out of memory



## 2. 并发基础

![image-20210315120828207](img/concurrent/image-20210315120828207.png)



![image-20210315104851865](img/concurrent/image-20210315104851865.png)

![image-20210315105029044](img/concurrent/image-20210315105029044.png)

![image-20210315105145042](img/concurrent/image-20210315105145042.png)



![image-20210315111908349](img/concurrent/image-20210315111908349.png)



![image-20210315112218859](img/concurrent/image-20210315112218859.png)

JMM



JVM和JMM的关系

- JMM内存图

![image-20210315112918576](img/concurrent/image-20210315112918576.png)



- 硬件内存抽象图

![image-20210315113025649](img/concurrent/image-20210315113025649.png)

- 关系图

![image-20210315113622476](img/concurrent/image-20210315113622476.png)

- 为什么会发生不同步的问题：

![image-20210315114028450](img/concurrent/image-20210315114028450.png)



- Java内存模型-同步的八种操作

![image-20210315114233432](img/concurrent/image-20210315114233432.png)



![image-20210315114146323](img/concurrent/image-20210315114146323.png)



![image-20210315114352518](img/concurrent/image-20210315114352518.png)



![image-20210315114424029](img/concurrent/image-20210315114424029.png)



![image-20210315114448831](img/concurrent/image-20210315114448831.png)

![image-20210315114529221](img/concurrent/image-20210315114529221.png)



![image-20210315115556494](img/concurrent/image-20210315115556494.png)





![image-20210315120703353](img/concurrent/image-20210315120703353.png)





数据访问保护





## 3. 并发编程与线程安全项目准备

- 进程安全

并发环境下得到我们期望的结果；

- 进程不安全

进程由于没有对数据进行数据保护，导致数据为脏数据及错误。























