# 如何获取Gmail邮箱授权码

## 步骤一：开启IMAP服务

1. 打开谷歌邮箱，进入[设置页面](https://mail.google.com/mail/u/0/#settings/fwdandpop)。
![image](https://github.com/kenneethmcdn/Gmail/assets/169994523/27658cc9-a965-4d15-9047-f68a11b9585a)


2. 在“转发和 POP/IMAP”选项卡中，启用IMAP服务。
![image](https://github.com/kenneethmcdn/Gmail/assets/169994523/303cbb60-1bf5-44c8-bc5c-e6aa61d81052)


## 步骤二：管理Google账号

1. 点击右上角的个人头像，然后选择“管理您的Google账号”。
![image](https://github.com/kenneethmcdn/Gmail/assets/169994523/34c76ab1-4892-4113-93e7-80c860021646)


2. 在“管理您的Google账号”页面，设置应用专用密码。
![image](https://github.com/kenneethmcdn/Gmail/assets/169994523/d7d5404f-4746-44c1-8d56-bcc4e88be700)


3. 生成应用专用密码，并复制该密码。
![image](https://github.com/kenneethmcdn/Gmail/assets/169994523/2637647c-d19a-431c-ab37-4c23501843ee)

![image](https://github.com/kenneethmcdn/Gmail/assets/169994523/3ef7d458-4452-4f35-99eb-0f14421d04b0)


## 步骤三：在Opencart中应用授权码

将生成的专用密码应用到Opencart的邮件设置中：

```bash
# Mail Engine
SMTP

# Mail Parameters
demo@gmail.com

# SMTP Hostname
ssl://smtp.ym.163.com

# SMTP Username
demo@gmail.com

# SMTP Password
生成的授权码

# SMTP Port
465

# SMTP Timeout
5

在“store”选项卡内的“E-Mail”设置中，同步修改为“demo@gmail.com”。
