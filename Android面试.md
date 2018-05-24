# Android面试
## Android相关
- Android系统总览
	- [Android系统开篇](gityuan.com/android/)

- Handler
	- [Android异步消息处理机制完全解析，带你从源码的角度彻底理解](https://blog.csdn.net/sinyu890807/article/details/9991569)

	- [Android消息机制，你真的了解Handler吗？](www.10tiao.com/html/227/201711/2650241824/1.html)
	- [你真的懂吗？（Android内存泄露之Handler）](https://blog.csdn.net/vv_bug/article/details/52765990)
- Animation
	- ["Android中的动画"-Android面试必问"精华技能点"汇总](https://blog.csdn.net/nzfxx/article/details/51919128)

	
	- [Android属性动画完全解析(上)，初识属性动画的基本用法](https://blog.csdn.net/sinyu890807/article/details/43536355)
- View绘制流程
	
	从ViewRoot的performTraversals（）方法开始依次调用perfromMeasure、performLayout和performDraw这三个方法。这三个方法分别完成顶级View的measure、layout和draw三大流程，其中perfromMeasure会调用measure，measure又会调用onMeasure，在onMeasure方法中则会对所有子元素进行measure，这个时候measure流程就从父容器传递到子元素中了，这样就完成了一次measure过程，接着子元素会重复父容器的measure，如此反复就完成了整个View树的遍历.

	同理，performLayout和performDraw也分别完成perfromMeasure类似的流程。通过这三大流程，分别遍历整棵View树，就实现了Measure，Layout，Draw这一过程，View就绘制出来了。

- 线程池
	- [Android开发——Android中常见的4种线程池](https://blog.csdn.net/seu_calvin/article/details/52415337)
- OOM
	- [Android 内存泄漏总结](https://blog.csdn.net/u010687392/article/details/49909477)

	- [Android性能优化：关于 内存泄露 的知识都在这里了！](https://www.jianshu.com/p/97fb764f2669)
- Service 	
- 大图加载
	- [Android高效加载大图、多图解决方案，有效避免程序OOM](https://blog.csdn.net/sinyu890807/article/details/9316683)

	- [Android 高清加载巨图方案 拒绝压缩图片](https://blog.csdn.net/lmj623565791/article/details/49300989)
- Activity
- ListView/RecyclerView
	- [Android RecyclerView局部刷新](https://blog.csdn.net/qq15357971925/article/details/78043332) 

	- [Android ListView工作原理完全解析，带你从源码的角度彻底理解](https://blog.csdn.net/guolin_blog/article/details/44996879)
- 事件分发机制
	- [Android事件分发机制详解：史上最全面、最易懂](https://www.jianshu.com/p/38015afcdb58)

## 网络通信
- TCP、UDP

- [经典面试题：URL输入到页面展示经过的所有过程？](https://www.jianshu.com/p/184ebd448c7f?mType=Group)

## 数据结构与算法
- [Java集合---HashMap源码剖析](https://www.cnblogs.com/ITtangtang/p/3948406.html)

- [HashMap为什么线程不安全？浅析高并发情况下的HashMap](https://blog.csdn.net/V_Axis/article/details/78604505)
- [Java集合---LinkedList源码解析](https://www.cnblogs.com/ITtangtang/p/3948610.html)
- [Java集合---ArrayList的实现原理](https://www.cnblogs.com/ITtangtang/p/3948610.html)
- [Java并发编程：并发容器之ConcurrentHashMap（转载）](http://www.cnblogs.com/dolphin0520/p/3932905.html)
- [二分查找算法（递归与非递归两种方式）](https://blog.csdn.net/lovesummerforever/article/details/24588989)
- [图解快速排序](http://www.cnblogs.com/MOBIN/p/4681369.html)

## 设计模式
