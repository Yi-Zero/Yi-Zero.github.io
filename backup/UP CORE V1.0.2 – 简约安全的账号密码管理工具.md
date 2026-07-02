
### 前言：

如有BUG或新的想法请去博客评论反馈，谢谢。
软件官网：https://upcore.top/

### 简介：

UP CORE 中文名”用户名密码核心(Username Password Core)”，是基于AntdUI+SQLite开发的本地化账号密码存储软件，支持深浅双模式显示，自动识别当前系统主题色自动切换。安全方面使用PBKDF2密钥派生算法，60万次迭代增强抗暴力破解，拥有高安全性，还采用Windows DPAPI字段级加密用于加密用户存储的数据，加密范围限定为当前用户，是你在Windows环境下存储密码的不二之选。

### 核心功能：

硬件级绑定：您的数据只能在注册账号的电脑上才能被解密，在其他电脑就算登录成功也无法解密数据

敏感数据加密：使用Windows数据保护API加密敏感字段以及使用系统级密钥管理，避免硬编码密钥风险

数据库安全：使用字段级加密，敏感数据在存储前加密，限制为当前用户访问，全面使用参数化查询

### 安全机制：

零知识原则：您的密码只有您知道，我们无法访问您的数据

本地加密存储：所有数据均在本地加密存储，用户输入内容全加密，拒绝用户数据明文存储

密码安全：PBKDF2密钥派生算法，60万次迭代增强抗暴力破解

### UI展示(局部，详细请前往最新博客)：

![Image](https://github.com/user-attachments/assets/5ca7f2b2-26c2-4191-a776-52bd4cc353fc)

![Image](https://github.com/user-attachments/assets/adf67e7b-0e40-4d1a-97f5-0fdd015a6688)

![Image](https://github.com/user-attachments/assets/4c3b318c-f525-467c-b46f-dff979e5db8d)

### 下载区：
| 下载方式 | 下载地址 |类型 |
| -------- | -------- | -------- |
| 官网下载     | https://upcore.top/    | 跳转官网     |
| 123盘     | https://www.123912.com/s/HTa7Vv-P6F93    | .exe安装包     |
| 百度网盘     | https://pan.baidu.com/s/1gKr9h3yUlWT4YRUSjf7dyA?pwd=ux9y    | .exe安装包     |

### 补充：
V1.0.2:
- 1.新增 设置 功能，方便用户个性化设置
- 2.新增 设置→双击默认执行 功能，可以设置表项双击是查看信息还是复制密码
