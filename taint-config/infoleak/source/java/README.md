## 描述
本目录下记录的Source主要来自Java标准库，会产生污点的Source方法包括
- 会从数据库中获取存储数据的方法(java.sql中的getString, getNString方法)
- 会从需要进行验证的用户中获取数据(如用户账户、密码)的方法(java.net中Authenticator中相应的get方法及requestPasswordAuthentication方法)
- 会从连接的client中获取信息的方法(java.net中的ContentHandler、CookieHandler、CookieManager的get方法)
- 会从DatagramSoceket/HttpCookie中获取信息的方法(java.net中DatagramSoceket/HttpCookie的get方法)
- 会从System中获取系统信息的方法(java.lang.System中的get方法)
- 会从输入流中获取信息的方法(java.io中从输入流读取信息的read方法，主要是各种InputStream和Reader中的read方法)
- 会从持久字段中获取指定值的方法(java.io.ObjectInputStream$GetField中的get方法)
- 会从文件中读取信息的方法(java.io.RandomAccessFile中的read方法)
- ...


注：get方法、read方法都是指以get/read开头的方法
