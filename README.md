# Check_VirtualAPK
A library for check whether your app run in a virtual project. 

检测应用是否被多开，接入很简单，直接拷贝Java类CheckVirtual，调用isRunInVirtual方法即可

以下为在Android 6.0 三星Note 5，Android 7.0 一加5，Android 4.4 Sony Lt55上面测试的结果

| 多开APP应用 | 测试结果 | 
| --- | :---:|
|Go双开 |测试通过|
|双开精灵|测试通过|
|VirtualApp |测试通过| 
|平行空间|测试通过|
|双开助手|测试通过|
|双开精灵|测试通过|

原理可见：[Android虚拟机多开检测](http://www.jianshu.com/p/216d65d9971e)