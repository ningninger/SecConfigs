## 描述
本目录下记录的Source主要来自Java Web应用程序开发框架Apache Wicket，，会产生污点的Source方法包括
- 会从传入的request中获取属性的方法(getHeader, getParameterValue)
- 会获取上传文件的输入流等信息的方法(getInputStream)

这些信息由外部输入且可以伪造