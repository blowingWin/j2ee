2012年11月20日 16:33:56

我最喜欢spring rmi的特性：
服务无需实现Remote接口,也不用调用rmic编译stub和skeleton

<del>这意味着旧代码可以透明成为remote服务！</del>

远程服务的参数和返回的自定义结构对象必须实现序列化Serializable，不然会抛异常!

资料：http://blog.csdn.net/ajun_studio/article/details/7681640
常见问题解决：http://yangwencan2002.iteye.com/blog/284249