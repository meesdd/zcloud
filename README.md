### zcloud榛云盘
#### 项目完成进度（未完成）
##### 进度日志
* 20170617完成了用户注册登录以及登录状态的保持（未测试登录状态保持情况）
* 20170618已经测试登录状态保持
* 20170618完成云盘文件的删除功能
* 20170620完成了文件的下载功能并且所有功能全部经过测试，注释也适当添加
#### 背景
前段时间开始学习struts2，了解了相关的架构，同时学习了基于struts2的拦截器的概念与用法以及网页文件上传下载的相关知识，看到了几个小的demo之后，想就着学到的一些新知识做一个小的网盘的demo。为了使用到拦截器以及相关的知识，所以决定实现用户登录的功能，同时为了熟悉servlet以及web相关的知识，决定使用session来保持用户的登录状态。这一次的代码相对以上一个餐厅预订系统相比，更加贯彻了mvc的思想，在数据库链接方面，尽管依然没有用到连接池，但是对于数据库的连接以及相关的数据的查询过程有了更加好的解决（参考了其他大神的代码）。
#### 实现
Intellij IDEA + struts2 + MySQL
#### 用到的知识
* 基本的mvc思想
* struts2拦截器
* javaweb知识
* 数据库mysql知识
#### 功能介绍
##### 基本
每一位用户可以注册登录本云盘，进行文件的存取
##### 详细
* 新用户通过注册得到属于自己的云盘账户
* 用户登录云盘账户，进入到云盘界面，可以查看到云盘的使用情况（~~使用空间、~~文件列表）
* 云盘内容页面上方有相关按钮可以上传文件
* ~~点击每个文件弹出窗口显示文件的详细信息，同时在该窗口可以将文件下载或者永久删除~~
* 点击文件列表中的文件名，可以在页面下方进行下载、删除操作
