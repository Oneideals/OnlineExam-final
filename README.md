# 在线考试系统

* ## 系统介绍

     该项目是一个前后端分离，后端使用 SpringBoot，前端使用 VUE 和 Element-UI 组件库配合完成开发。

* ## 在线浏览地址
    温馨提示：请登录后台的朋友,不要删除计算机网络这套试卷，因为目前只添加了这套试卷的题目作为测试，删了，其他人就不能答题了。
    
    [在线考试系统](http://124.223.53.193/ "在线考试系统")


* ## 部署过程
  
  ### 后端环境：
  
  #### 1、安装Java
  
  Java版本最好使用Java 8，版本太新容易出问题
  
  下载地址：（https://www.oracle.com/cn/java/technologies/javase/javase8-archive-downloads.html）
  
  #### 2、安装MySQL
  
  下载地址：（https://dev.mysql.com/downloads/mysql/）
  
  运行数据库文件，连接数据库
  
  ### 前端环境：
  
  #### 1、安装node
  
  版本为12（高版本可能会不兼容，出现预期外的bug）
  
  下载地址：（https://registry.npmmirror.com/binary.html?path=node/latest-v12.x/）
  
  安装完成以后可以通过cmd命令：**node -v** 查看是否安装成功
  
  #### 2、安装yarn
  
  安装node后，自动会安装npm包管理器，npm安装依赖速度较慢，所以这里推荐使用yarn。
  
  使用 npm install yarn -g 命令安装，完成后请设置yarn源为淘宝镜像
  
  yarn config set registry https://registry.npm.taobao.org
  
  #### 3、安装依赖
  
  温馨提示，前端项目在 SpringBoot-Vue-OnlineExam/exam目录下，运行命令请在此目录打开bash窗口
  
  l yarn install（安装依赖）
  
  l yarn start（运行项目）
  
  #### 4、done
  
  到此步骤，前端运行步骤完成。
