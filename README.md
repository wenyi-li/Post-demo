# 博客系统

> 国科大2023高级软件工程课程作业

> 姓名：李文毅  学号：202318015059008

此项目是一个基于Ruby on Rails的博客系统。它允许用户创建、删除、评论博客。同时，博客内容可以显示创建时间、支持富文本编辑。

## 功能

- 创建新的博客，博客内容支持富文本编辑、上传图片，支持显示创建时间
- 浏览已有的博客内容
- 更新/删除/删除已发布的博客
- 当某条博客有新评论的时候，支持邮件通知博客创建者

## 使用指南

### 依赖库

- ruby 3.2.2  
- sqlite3 3.24.0
- Rails 7.1.2

### 安装

1. 克隆仓库：

   ```
   git clone https://github.com/wenyi-li/Post-demo.git
   cd Post-demo
   ```

2. 参考[Ruby on Rails官网](https://rubyonrails.org/)配置相应的环境

3. 启动Server

   ```
   rails server
   ```

6. 打开你的 Web 浏览器，访问 [http://127.0.0.1:3000/posts/](http://127.0.0.1:3000/posts/)。

## 使用

1. 在你的 Web 浏览器中访问 [http://127.0.0.1:3000/posts/](http://127.0.0.1:3000/posts/)。

2. 创建新的博客，支持富文本编辑+上传图片

3. 对已有博客进行修改或删除

4. 对已有博客进行评价

   

## 致谢

- 感谢 Ruby on Rails 社区提供的文档帮助。
