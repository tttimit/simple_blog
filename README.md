# simple_blog
使用flask搭建的一个数据库驱动的极简blog

---
## 一些使用示例

### 主页（blog按照时间由近到远排列）

![主页](md_resources/image1_index.png)

###  登录（包含登录成功/失败的提示消息）

![登录](md_resources/image2_login.png)

### 写blog

![写blog](md_resources/image3_post.png)

![发布blog成功](md_resources/image4_blogs.png)

### 退出登录

![logout](md_resources/image5_logout.png)

---

# 如何使用

1. 下载

2. 进入根目录（simple_blog目录）

3. 在python交互环境中执行以下代码（初始化数据库）

   ```python
   from flaskr import init_db
   init_db()
   ```

4. 执行本程序

   ```powershell
   python flaskr.py
   ```

### 须知

* 默认用户名: admin
* 默认密码: default

