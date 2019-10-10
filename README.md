### 什么是“gitsolo”？
---------------------------------------
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“gitsolo”是知启蒙团队开源的极简Git服务器，纯Java开发，本地文件数据库，只依赖JDK，一键启动（zhiqim.exe/zhiqim.lix），支持HTT(S)协议、多项目多成员权限管理和二次开发。。

<br>

### gitsolo有什么优点？
---------------------------------------
1、想搭一个Git服务器，又觉得GitLab很非常的公司或个人，选择gitsolo绝对错不了。<br>
2、gitsolo只依赖JDK和ZhiqimDK，安装简单到爆，特别是有经验的Java程序员，配置好boot.home，一键启动（zhiqim.exe/zhiqim.lix）。<br>
3、独立工程，不需要WEB容器，什么Tomcat/Jetty不需要的。<br>
4、有HTTP(S)协议就够了，什么ssh协议配置太麻烦。gitsolo的多项目/多成员管理很棒的。<br>
5、还有一个特点就是会检查提交者和提交者邮箱，这个要注意啦，提交者必须是gitsolo的用户名，否则提交不了，为什么这么设计呢？因为这么控制了之后，可以避免别人用自己的账号提交啦，哈哈哈。<br>
<br>

### gitsolo安装指南

> 1、 **JDK下载安装** ：其详细安装教程请前往[【JDK安装教程】](https://www.zhiqim.com/document/bestcase/jdk.htm)。
> 
> 2、**执行程序下载** ：源码下载克隆请点击[【Gitsolo】](https://www.zhiqim.com/gitcan/zhiqim/gitsolo.htm)。
> 
> 3、**安装配置** ：

gitsolo配置时，有几个需要主要的点，详见下图图解说明：

配置zhiqim.xml:

![输入图片说明](https://images.gitee.com/uploads/images/2018/0705/163637_1edfc186_1793820.jpeg "zhiqim配置.jpg")

<br>

配置httpd.xml：

![输入图片说明](https://images.gitee.com/uploads/images/2018/0705/164043_61f9b77f_1793820.jpeg "httpd配置.jpg")

4. **启动**：

![输入图片说明](https://images.gitee.com/uploads/images/2018/0705/165548_8e285386_1793820.jpeg "启动.jpg")


5.  **gitsolo功能展示** 

-  **自带的管理和权限功能** 

系统基础设置,如系统菜单，系统头像，系统配置，系统参数首页主题等。
部门角色管理，如部门管理，部门成员，部门权限，角色管理，角色成员，角色权限
还有操作员管理，操作日志查询

![输入图片说明](https://images.gitee.com/uploads/images/2018/0705/170555_bb7bc3db_1793820.jpeg "管理和权限.jpg")

-  **项目信息管理功能** 

项目的增删改查和转让等功能。

![输入图片说明](https://images.gitee.com/uploads/images/2018/0705/170636_11bcc6b0_1793820.jpeg "项目信息管理功能.jpg")

-  **项目成员管理功能** 
项目成员的添加和删除功能。

![输入图片说明](https://images.gitee.com/uploads/images/2018/0705/170708_13dfa779_1793820.jpeg "项目成员管理功能.jpg")

-  **项目代码仓库功能** 

增加，修改，删除，重命名和迁移仓库功能。

![输入图片说明](https://images.gitee.com/uploads/images/2018/0705/170739_5253fac8_1793820.jpeg "项目代码仓库功能.jpg")

-  **设置独立密钥功能** 

开启仓库独立密钥，加强保密性。

![输入图片说明](https://images.gitee.com/uploads/images/2018/0705/170802_69c6ae1b_1793820.jpeg "设置独立密钥功能.jpg")

-  **我的汇报设置功能** 

可以增加我汇报工作的对象，以及向我汇报工作的对象。

![输入图片说明](https://images.gitee.com/uploads/images/2018/0705/170905_67098e9c_1793820.jpeg "我的汇报设置功能.jpg")

-  **我的项目动态功能** 

可以查看我创建的项目动态以及向我汇报的项目的动态。

![输入图片说明](https://images.gitee.com/uploads/images/2018/0705/170942_2a770e8f_1793820.jpeg "我的项目动态功能.jpg")



### 知启蒙技术框架与交流
---------------------------------------
![知启蒙技术框架架构图](https://images.gitee.com/uploads/images/2018/0907/101431_93f5c39d_2103954.jpeg "知启蒙技术框架架构图.jpg")<br><br>
QQ群：加入QQ交流群，请点击[【458171582】](https://jq.qq.com/?_wv=1027&k=5DWlB3b) <br><br>
教程：欲知更多知启蒙WEB容器，[【请戳这里】](https://www.zhiqim.com/gitcan/zhiqim/gitsolo/tutorial/index.htm)
