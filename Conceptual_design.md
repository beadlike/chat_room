1.注册 
	用户输入用户名,密码,确认密码
	校验两次密码是否相等
	校验用户名是否合法
	校验用户名是否存在
	添加新用户
	
2.登录
	用户输入用户名,密码
	检验用户名是否存在
	检验用户密码是否匹配
	将用户信息写入全局变量
	
3.好友管理
	查看  得到好友ID SELECT fuid FROM friend WHERE state = '同意' AND uid = gl_uid;