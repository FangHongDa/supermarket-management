# 毕业设计-超市订单管理系统

#### 介绍
系统主要业务是对超市供应商以及订单进行管理与维护


#### 软件架构
后端技术：spring + springmvc + mybatis  
前端技术：jsp  
环境要求：jdk1.8 | maven | mysql  


#### 功能介绍
##### 【代码结构与数据库截图】
![输入图片说明](images/image2.png)
![输入图片说明](images/image3.png)

##### 【功能详述】 
△登录
在登录页面，填写账号、密码、验证码，验证成功可成功登录页面。
![输入图片说明](images/image4.png)


△订单管理
超市购买订单信息管理，包含商品信息，价格、供应商信息。
![输入图片说明](images/image5.png)


△供应商管理
对超市供应商的基础信息进行管理，比如供应商名称、联系人、联系电话等等
![输入图片说明](images/image6.png)


△用户管理
对用户账号信息进行管理，包括用户的基本信息，用户对超市系统的登录等等，提供基础的增删改查
![输入图片说明](images/image7.png)

△修改密码
主要是针对当前用户的登录密码进行修改
![输入图片说明](images/image8.png)


#### 项目预览
地址：[商品详情 ](https://www.xunmaw.com/shop/detail/1624392459166236674)   
点击商品详情中的演示地址，看查看系统录制的视频    

#### 使用说明
1. 创建数据库，执行数据库脚本
2. 修改jdbc数据库连接参数
3. 下载安装maven依赖jar
4. 在tomcat服务器部署项目  
    请求地址： http://localhost:8080/supermarket    
    用户名：admin  
    密码：admin  

#### 联系作者
这是作者的微信二维码，如需本项目源代码，可扫码联系联系作者  
![作者微信](https://gitee.com/xiaoxinlai/book-system/raw/master/xunmaw001.jpg)

这是作者的公众号二维码，时不时会推一些新开发的项目源码与高效软件工具，感兴趣的朋友给个关注  
![作者公众号](https://gitee.com/xiaoxinlai/book-system/raw/master/xunmaw%E5%85%AC%E4%BC%97%E5%8F%B7.jpg)