# thinkphp-blog

## 链接
- 博客：http://whphp.top 
- github：https://github.com/HannibalKB/Blog 

## 简介
闲暇之时使用thinkphp开发了一个个人博客用来整理技能知识 

亦可以作为初学thinkphp的同学们的参考源代码；  

此博客程序前后台页面以及逻辑代码的都由我手工打造；没有版权限制；可以随意折腾；

想研究支付宝、微信支付、邮件发送、短信通知验证码发送、oss云存储、融云即时通讯、友盟推送、Memcached缓存 

![image](http://github.com/blog/demo.jpg)  

## 使用说明
1. 请将项目内的所有文件直接放在根目录下；不要多层目录；  
例如正确：www/;错误：www/thinkbjy/；
2. 后台登陆密码默认为admin；
3. 如果确认开启了mod_rewrite  
请将/Application/Common/Conf/config.php中的URL_MODEL改为2以优化url  
未开启路由：http://whphp.top/index.php/Home/Index/article/aid/60  
开启路由后：http://whphp.top/article/60
4. 把根目录下的robots.txt中的whphp.top改为自己的域名；
5. 可以在用户管理中；将第三方账号标记为站长；然后后台就必须使用第三方账号登录以增强安全性；

## 针对thinkphp的改进优化；
1. 修复tinkphp的session设置周期无效的bug；
2. 自定义标签 /Application/Common/Tag/My.class.php；
3. 将html视图页面分离；

## 项目介绍
1. 前台基于boostrap的响应式页面布局适配手机和平板；
2. 带表情的ajax无限级评论系统；
3. PHPMail邮件系统；
4. QQ、微博、豆瓣、人人、开心网等第三方登陆；
5. ueditor 百度富文本编辑器；
7. font-awesome；
8. iCheck;


