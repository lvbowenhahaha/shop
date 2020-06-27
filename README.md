# 商城
- 开发环境：IDEA、Tomcat8.5
- 数据库：MySql
- 前端主要使用Bootstrap以及JQuery，后端基于SpringMVC、Spring、MyBatis进行开发，使用Maven构建

> ## 相关问题
> 1. 若项目部署到tomcat中，则需要在tomcat的webapp目录中(即shop项目所在目录)建立shopimage目录用以保存图片。 在idea的edit configurations中的tomcat中的deployment中添加external source指定shopimage这个目录,不然无法显示图片

> 2. 聊天使用了activemq，需要先下载安装，然后开启服务，即可使用。

> 3. 如果修改个人信息地址不成功的，报404错误，在IDEA的工具栏的运行配置Edit Configuration里面的Deployment选项中war explode中的Application Context中的"/"改成"/shop"即可


***如果还有其他Bug，请提Issues。***
