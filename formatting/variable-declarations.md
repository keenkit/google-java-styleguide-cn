#### 4.8.2 变量声明

##### 4.8.2.1 每次只声明一个变量

不要使用组合声明，比如`int a, b;`。

##### 4.8.2.2 需要时才声明，并尽快进行初始化

不要在一个代码块的开头把局部变量一次性都声明了(这是c语言的做法)，而是在第一次需要使用它时才声明。 局部变量在声明时最好就进行初始化，或者声明后尽快进行初始化。


