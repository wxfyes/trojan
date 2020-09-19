A大更新的trojan+wp一键安装脚本，适合建站的小伙伴使用，特此fork一份！以下是A大原文

有朋友在博客留言想要trojan go + wordpress的教程和一键脚本，奈何个人喜欢trojan，所以写了个trojan+wordpress一键脚本，适用于centos7系统，经测试在PR-V（pacific rack新面板）机器测试，正常使用。

适用于centos7系统，暂无适配debian/ubuntu的计划
trojan自动配置win客户端，也会展示config配置文件
wordpress启用了强制https，经测试上传及安装主题/插件正常，wordpress功能正常使用。
注意此种模式下不能开启CDN
除在本文留言转载网站并获取授权外，此文及脚本禁止转载，已获授权转载请著明文章链接。
trojan+wordpress一键脚本
1、使用以下命令，trojan+wordpress一键脚本，注意不能开启CDN

bash <(curl -Ls https://raw.githubusercontent.com/wxfyes/trojan/master/trojan_wp.sh)
2、选择1、安装trojan + wp

3、安装过程需要输入已经解析到VPS的域名，例如www.yourdomain.com，不要带https://，再次提醒不要开启CDN

4、安装过程中设置trojan密码

5、等待安装完成即可。
