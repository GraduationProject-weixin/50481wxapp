# [首页查询更多项目](https://github.com/GraduationProject-weixin) 包安装运行


# 50481wxapp智慧物业平台修改5.5小程序

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


推荐使用：谷歌浏览器


后台登录页面
http://localhost:8080/zhihuiwuyepingtai/admin/dist/index.html

管理员				账户:admin 		密码：admin
用户				账户:a1 		密码：123456
用户				账户:a2 		密码：123456
用户				账户:a3 		密码：123456
员工				账户:a1 		密码：123456
员工				账户:a2 		密码：123456
员工				账户:a3 		密码：123456

在src\main\resources\application.yml中编辑

	url: jdbc:mysql://127.0.0.1:3306/zhihuiwuyepingtai?useUnicode=true&characterEncoding=utf-8&useJDBCCompliantTimezoneShift=true&useLegacyDatetimeCode=false&serverTimezone=GMT%2B8
	username: root	    数据库用户名 root
	password: 123456	用户密码    123456


图片存放路径： src\main\webapp\upload 里面上传图片名里面不能有中文











