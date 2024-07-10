## 描述
本目录下记录的Source主要来自Java标准库，，会产生污点的Source方法包括
- 会从传入的request中获取属性的方法(getContent, getRemoteSocketAddress)
- 会从外部进行输入的方法(getSelectedText, readLine)
- ...
  
这些信息由外部输入且可以伪造