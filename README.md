# myblog.github.io
个人博客  利用vue实现前端界面搭建，使用github搭建个人博客网站
## 记录一下主要的步骤：  
### 1、创建以 `'username'.github.io`为标准的仓库，这个仓库名也是以后访问的网络地址  
如图  
![img](https://github.com/szjzszjz/szjzszjz.github.io/blob/master/pic/01.png)  
### 2.1、[下载github桌面客户端](https://desktop.github.com/)  
如图  
![img](https://github.com/szjzszjz/szjzszjz.github.io/blob/master/pic/02.png)  
### 2.2、或者直接通过git命令将远程仓库clone至本地  

### 3、打包前端项目  
命令行执行`npm run build` 在项目的目录中多了一个dist文件夹，里面有static文件夹和一个index.html  
![img](https://github.com/szjzszjz/szjzszjz.github.io/blob/master/pic/03.png)  
打开html文件，将所有'/static...' 前面的'/'去掉，保存！  
![img](https://github.com/szjzszjz/szjzszjz.github.io/blob/master/pic/04.png)  
将static, index.html文件复制粘贴至'username'.github.io文件夹下  
### 4、提交至远程仓库  
(1) 桌面工具提交  
(2) 'username'.github.io`文件夹下命令行提交  
```
git add .
git commit -m '提交日志'
git push
```
### 5、访问刚刚搭建的网站  
输入：`https://szjzszjz.github.io/`  
