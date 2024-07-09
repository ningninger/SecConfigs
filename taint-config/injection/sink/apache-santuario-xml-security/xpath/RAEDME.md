- **概述**：
    Apache XML Security API 提供了用于处理 XML 文档中的 XPath 表达式的功能，该功能主要涉及两个类：XPathAPI 和 JDKXPathAPI，用于在 XML 文档中评估 XPath 表达式和选择节点列表。
- **常见使用场景**
    这些API通常用于解析与执行XPath表达式，并根据XML文档内容返回对应的结果
- **安全风险**
    XPath注入：与SQL注入攻击类似，攻击者可以通过构造恶意的XPath表达式来获取 XML 数据的组织结构，或者访问在正常情况下不允许访问的数据，若 XML 数据被用于用户认证，攻击者甚至可以进行提权。
