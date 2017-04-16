# AdminLTE for laravel

##  介绍
基于[AdminLTE](https://github.com/almasaeed2010/AdminLTE)的后台模板样式 集成基本的文章 用户模块 其余的功能模板可根据实际项目需求添加


## 效果图
### 后台首页
![image](public/screenshot/1.png)
### 文章列表
![image](public/screenshot/2.png)

## 安装
### 1.clone到本地
```
git clone https://github.com/GeekGhc/adminLTE-for-laravel.git
```
### 2.根目录下创建.env文件
```
 php artisan key:generate  //生成key值
```

后台开发过程时可借助`MustBeAnAdmin` middleware 完成逻辑判断