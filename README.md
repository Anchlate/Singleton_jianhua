# Singleton_jianhua
1、这是一个简化的单例模式，可以自动在ARC和MRC创建相应的单例。其中最主要的文件是ANSingleton.h头文件，在该头文件中define了一个创建单例类的宏定义。

2、使用方法：(1)、将ANSingleton.h头文件copy到你的项目中，并在使用的地方import该头文件；(2)、在你的单例类的.h文件中使用ANSingleton.h中的宏定义ANSingletonH(你的单例类的名称)；(3)、在你的单例类的.m文件中使用宏定义ANSingletonM(你的单例类的名称)

3、只要进行第2点的三步操作就可以创建一个单例类。使用非常方便。
