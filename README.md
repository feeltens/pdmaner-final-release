# 一、项目说明

本仓库为 **PDManer 元数建模 v4.9.3** 的 **最后发行版本源码存档**。  
由于官方已升级至新版本且旧版本安装包无法下载，因此将源码备份于此，方便有需要的用户自行编译使用。  

PDManer-v4.9.3 安装包  
for mac arm:  
https://github.com/feeltens/pdmaner-final-release/blob/main/dist/PDManer-mac_arm64_v4.9.3.dmg

for mac x64:  
https://github.com/feeltens/pdmaner-final-release/blob/main/dist/PDManer-mac_x64_v4.9.3.dmg

for windows:  
https://github.com/feeltens/pdmaner-final-release/blob/main/dist/PDManer-win_v4.9.3.exe

PDManer 是一款多操作系统、开源免费的桌面版关系数据库建模工具，界面简洁美观，操作简单，上手容易，支持 Windows、Mac、Linux 及国产操作系统。  

支持的数据库包括：
- MySQL、PostgreSQL、Oracle、SQLServer 等常见数据库  
- 达梦、GuassDB 等国产数据库  
- Hive、MaxCompute 等大数据方向数据库  
- 用户可自行扩展更多数据库类型  

本产品基于 **ES6 + React + Electron + Java** 构建。  

---

# 二、主要功能

- **数据表管理**：表、字段、注释、索引等  
- **视图管理**：多表多字段组合视图，支持生成 DDL 及 Java DTO  
- **ER 关系图**：绘制 ER 图及高阶抽象模型  
- **数据字典**：代码映射表管理，并与数据表字段关联  
- **数据类型**：支持基础数据类型与数据域，用户可自定义  
- **多数据库支持**：内置主流数据库，支持自定义扩展  
- **代码生成**：内置 Java / MyBatis / MyBatisPlus / C# 等代码生成，可扩展 Python 等  
- **版本管理**：数据表版本管理与增量 DDL 生成  
- **生态对接**：支持导入 PowerDesigner PDM、旧版 PDMan 文件，支持导出 Word 文档等  

---

# 三、如何编译

如需本地编译本版本，请参考这篇详细教程：  
🔗 [PDManer 旧版本手动编译安装包全记录](https://www.bytezonex.com/archives/pdmaner-old-version-build-guide.html)

---

# 四、特别说明

1. 本仓库源码仅用于学习与历史存档，不再进行功能更新  
2. 编译需具备一定前端开发基础（React / Electron / Node.js）  
3. 安装包请自行编译生成，本仓库不直接提供成品安装包  
4. 欢迎提交 PR 修复问题或改进文档  
5. Java 部分代码参考：[chiner-java](https://gitee.com/robergroup/chiner-java)  

---

# 五、相关资源

- [官方 PDManer 新版本](https://gitee.com/robergroup/pdmaner)
- [操作手册 - 语雀版](https://www.yuque.com/pdmaner/docs)
- [OSChina PDMan 专栏](https://my.oschina.net/skymozn?tab=newest&catalogId=5775221&sortType=time)

---
