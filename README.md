# 用Springboot开发客户管理系统

### 项目说明

**客户管理系统** 主要是对客户的管理。此项目是以熟悉Springboot的开发流程而产生，是以学习Springboot为目的。很多人认为（也包括我）在技术学习中需要有实际的项目为向导学习起来才有方向也会相对较容易，所以现拟定一个**客户管理系统**的小项目作为`Springboot`的学习项目。

通过这个小项目基本可以对`Springboot`、`Spring MVC`等很多知识点有比较深刻的认识，以至在实际项目开发中手到擒来、得心应手。

### 需求分析

+ 用户管理
  
    - 属于系统管理范畴，本系统需要有用户登陆才能进行操作，这里的用户也就是系统用户，每个用户可根据权限管理自己的客户信息。

+ 菜单管理

    - 属于系统管理范畴，将系统中所有可能访问到的URL都提取为菜单（可分为导航菜单和权限菜单），用户只能访问权限范围内的菜单。

+ 角色管理

    - 属于系统管理范畴，为方便为用户分配菜单（可能很多用户的权限是一样的），所以增加了角色这个中间元素，先为用户分配可访问的菜单 ，再为用户分配对应角色。

+ 客户管理

    - 属于系统业务范畴，登陆用户对自己的客户进行增、删、查、改等操作。

### 开始

+ 先在Github上创建一个项目，命名为`customer`。我这里的仓库是[https://github.com/zsl131/customer.git](https://github.com/zsl131/customer.git)。*在Github上创建项目的具体方案可参考我的文档[《Github上创建项目》](http://www.zslin.com/web/article/detail/10 "Github上创建项目")*

+ 使用IDEA开发工具创建名为`customer`的项目。具体方法可参考我的文档[《Springboot 之 Helloworld》](http://www.zslin.com/web/article/detail/7 "Springboot 之 Helloworld")
