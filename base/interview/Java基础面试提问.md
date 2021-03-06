# Java基础面试提问

## 1. String篇

1. 说说String、StringBuffer和StringBuilder的区别
2. 为什么String 不可变？
   1. final修饰的变量特点
3. StringBuffer为什么是线程安全的？（引出多线程话题）

## 2. 线程安全篇

1. 什么是线程安全？
2. 为什么会有线程安全问题？(说说java内存模型？)
3. 说说java 是如何保证线程安全的？
4. 谈谈Synchronized和ReentrantLock的区别？
5. Synchronized和ReentrantLock都是悲观锁，那什么是乐观锁，如何实现的呢
6. 你有使用过volatile 关键字吗？他能保证线程安全吗？

## 3. 多线程篇

1. 为什么要使用多线程？
2. 你在使用多线程中有没有遇到什么问题？
3. 多线程导致的内存泄漏你是怎么解决的？
4. 什么是上下文切换？为什么需要上下文切换？
5. 什么是死锁？如何解除死锁？
6. 线程之间是如何进行线程通信的？
7. 我们为什么不能直接调用run()方法？

## 4. 线程池篇

1. 你是如何管理这些线程的？为什么要使用线程池呢？
2. 线程池的execute() 和submit() 的区别是什么？
3. 你是怎么创建这些线程池的？
4. 为什么不建议使用Executors？
5. 线程池从启动到工作的流程？
6. 如何合理的配置一个线程池的大小？

## 5. 异常处理篇

1. 说说java异常处理类的整体架构
2. try语句和finally语句都有return的情况如何返回？
3. finally一定都会执行吗？有没有特例？

## 6. 容器篇

1. 说说ArrayList 的底层数据结构？
2. ArrayList的扩容机制
3. HashMap的底层实现
4. HashMap的哈希表长度为什么是2的幂次方
6. HashSet是如何检查重复的？