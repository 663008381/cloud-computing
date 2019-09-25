# 实验一  GitHub使用入门

### 1.初始化本地文件夹作为一个Git仓库：

`git init`

![img](file:///C:\Users\Lenovo\AppData\Local\Temp\ksohtml8920\wps1.jpg) 

 

### **2.拷贝GitHub网站中的项目网址：**

![img](file:///C:\Users\Lenovo\AppData\Local\Temp\ksohtml8920\wps2.jpg) 

 

### 3.**添加远程代码仓库的URL：**

`(git remote add origin https://github.com/663008381/test.git)`

`git remote add origin https://github.com/663008381/cloud-computing.git`

说明，origin指代远程代码仓库（GitHub中），master表示本地的主分支。验证一下添加是否成功：

`git remote -v`

![1569397961633](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\1569397961633.png)

### 4.**首先从远程代码仓库拉取数据**

`git pull origin master`

![1569398028287](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\1569398028287.png)

### 5.**新建README文档，README文档是每个GitHub项目必备，说明项目内容。上文没有创建，在此处完成。**

`touch README.md`

### 6.**添加文件夹中的所有文件：**

`git add .`

![1569398048648](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\1569398048648.png)

### 7.**提交文件：**

`git commit -m “wuue”   //上传者名字`

可以使用`git config user.name "someone"`，`git config user.email "someone@someplace.com"`修改上传者信息

![1569398084046](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\1569398084046.png)



### 8.**推送本地更新至远程服务器：**

 

`git push -u origin master`

![1569398094561](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\1569398094561.png)

<img src="file:///C:\Users\Lenovo\AppData\Local\Temp\ksohtml8920\wps5.jpg" alt="img" style="zoom:150%;" /> 
