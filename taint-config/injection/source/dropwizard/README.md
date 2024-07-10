## 描述
本目录下记录的Source主要来自dropwizard框架，会产生污点的Source方法包括
- 会将传入的request作为参数的方法(doFilter, doGet)
- 会从传入的request中获取属性的方法(getParameter, getBody)
- ...
  
这些信息由外部输入且可以伪造