xblog 在nodejs实战源码N-blog修改版kirinblog的基础上进行修改的修改版（感谢^_^）
正在重构、扩展及修bug
<br/>
2016/11/05 ---修复文章重名时的bug<br/>
2016/11/06 ---添加swiper滚动条,预添加媒体库<br/>
2016/11/07 ---修复bug<br/>


欢迎加QQ群：337323051 一起讨论

启动准备： npm install
数据库配置与启动 ：settings.js设置帐号密码  启动mongodb： mongod --dbpath  dbPath\dbname

本地调试注意修改start.js中的port端口，

app.set( 'port', process.env.PORT || 3000 ); //服务启动端口

默认为80可以修改为3000 

启动： supervisor start  然后访问浏览器 http://localhost:3000/#/

示例：oospace.com
