# reading-practice
## 学习资料：
### 1. bilibili “【给傻子的Git教程】 https://www.bilibili.com/video/BV1Hkr7YYEh8/?share_source=copy_web&vd_source=2ecb47ed73a6b23fb9470d8ade7cfb42”
### 2. 稀土掘金 “【Git 入门实战：从 0 到 1 搞定本地与远程仓库】 https://juejin.cn/post/7566851737811468294”

## 实践流程
### 1.在git官网下载并安装适配自己电脑的git版本
### 2.在终端进行本地配置
```
git config --global user.name "你的姓名"
git config --global user.email "你的邮箱"
```
### 3.在目标目录下创建本地仓库
```
git init
```
### 4.在github创建远程仓库并与本地仓库关联
```
git remote add origin "远程仓库地址"
git remote -v  #查看是否成功
```
### 5.将本地代码推送到远程仓库
```
git add .
git commit -m "备注"
git push -u origin main
```
## 提交内容
### 1.第一次提交：README.md,demo.py,index.html
### 2.第二次提交：在demo.py中新增一行，在README.md中增加内容
### 3.第三次提交：在demo.py中新增一行，在README.md中增加内容

## 遇到的问题
### 1.对git命令不熟悉：查询ai
### 2.对git操作流程不熟悉：查询相关视频及ai