# weixin-admin
管理微信公众号，实现了自动回复，自定义菜单，渠道二维码创建等功能


体验地址：http://wechat.anchel.cn/

部署步骤
+ 准备自己的web服务器，安装好nginx（可选），node，mysql，pm2（可选）
+ 将项目代码下载到自己的web服务器上，比如这个目录 /data/web/weixin-admin
+ 将项目下 docs/db/wechat.sql 建库表语句执行
+ 在项目主目录下执行：npm install
+ 然后执行 node app.js 就启动系统了
+ 访问 http://IP ，这里的ip是你web服务器的ip。如果要更换端口，修改 config/development.js 里面的80端口号。另外1024以下端口号需要root权限才能正常启动监听。
