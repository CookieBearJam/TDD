# TDD
软件过程改进TDD
### 项目简介
这是在20年春季学期的软件过程改进课程中所做的TDD项目
最终产出一个To-Do list，可以访问服务器ip创建自己的待办事项清单，效果如下：
![](out.png)
目前还有很多需要改进的地方，功能仅供测试
### 实现依赖：
* Python3.6
* Django 3.0.6
* Virtualenv + pip
* Nginx
* Gunicorn 20.0.4
* Fabric3
* Git
## 其他
1. deploy_tools文件夹下为部署时使用配置文件
2. 自动部署主要使用fabric3，自动化脚本见fabfile.py
