## 目录 ##

- **1.[你应当具备的知识](1.0.md)** 
 - 1.1 [测试环境的搭建](1.1.md)
     - 1.1.1 [php-iis-mysql](1.1.1.md)
     - 1.1.2 [php-apache-mysql](1.1.2.md)
     - 1.1.3 [php集成环境](1.1.3.md)
     - 1.1.4 [windows和linux下php](1.1.4.md)
     - 1.1.5 [php.ini与.htaccess](1.1.5.md)
 - 1.2 [基础的php语法知识](1.2.md)
     - 1.2.1 [变量](1.2.1.md)
     - 1.2.2 [逻辑语句](1.2.2.md)
     - 1.2.3 [数据传递](1.2.3.md)
     - 1.2.4 [会话控制](1.2.4.md)
     - 1.2.5 [函数](1.2.5.md)
     - 1.2.6 [面向对象](1.2.6.md)
 - 1.3 [简单的http协议](1.3.md)
     - 1.3.1 [http请求](1.3.1.md)
     - 1.3.2 [http响应](1.3.2.md)
     - 1.3.3 [http消息报头](1.3.3.md)
 - 1.4 [html与javascript基础语法](1.4.md)
     - 1.4.1 [常用的html标签介绍](1.4.1.md)
     - 1.4.2 [javascript语法简介](1.4.2.md)
 - 1.5 [常用的审计工具](1.5.md)
     - 1.5.1 [notepad++](1.5.1.md)
     - 1.5.2 [netbox(动态调试)](1.5.2.md)
     - 1.5.3 [seay代码审计工具](1.5.3.md)
     - 1.5.4 [其他的php代码审计工具简介](1.5.4.md)
- **2.[常规漏洞](2.0.md)**
 - 2.1 [sql注入漏洞](2.1.md)
     - 2.1.1 [select注入](2.1.1.md)
     - 2.1.2 [insert/update注入](2.1.2.md)
     - 2.1.3 [常见的防注入代码绕过](2.1.3.md)
 - 2.2 [上传漏洞](2.2.md)
     - 2.1.1 [直接上传](2.1.1.md)
     - 2.1.2 [黑名单与白名单](2.1.2.md)
     - 2.1.3 [$_FILE、file_put_contents、fwrite](2.1.3.md)
 - 2.3 [执行漏洞](2.3.md)
     - 2.3.1 [代码执行函数](2.3.1.md)
     - 2.3.2 [命令执行函数](2.3.2.md)
     - 2.3.3 [本地包含和远程包含](2.3.3.md)
     - 2.3.4 [正则函数](2.3.4.md)
     - 2.3.5 [反序列函数](2.3.5.md)
     - 2.3.6 [动态函数](2.3.6.md)
 - 2.4 [逻辑漏洞](2.4.md)
     - 2.4.1 [水平越权](2.4.1.md)
     - 2.4.2 [垂直越权](2.4.2.md)
     - 2.4.3 [代码逻辑错误](2.4.3.md)
     - 2.4.4 [不能缺失的exit](2.4.4.md)
 - 2.5 [前端漏洞](2.5.md)
     - 2.5.1 [xss](2.5.1.md)
     - 2.5.2 [csrf](2.5.2.md)
     - 2.5.3 [ssrf](2.5.3.md)
     - 2.5.4 [crlf](2.5.4.md)
     - 2.5.5 [XXE注入](2.5.5.md)
     - 2.5.6 [Xpath注入](2.5.6.md)
 - 2.6 [文件遍历-下载-读取-删除](2.6.md)
 	 - 2.6.1 [文件目录遍历](2.6.1.md)
 	 - 2.6.2 [任意文件下载](2.6.2.md)
 	 - 2.6.3 [任意文件读取](2.6.3.md)
 	 - 2.6.4 [任意文件删除](2.6.4.md)
- **3.[php漏洞](3.0.md)**
 - 3.1 [编码与加密解密](3.1.md)
     - 3.1.1 [url二次编码](3.1.1.md)
     - 3.1.2 [base64 编码](3.1.2.md)
     - 3.1.3 [自定义加密解密](3.1.3.md)
 - 3.2 [反序列化漏洞](3.1.4.md)
     - 3.2.1 [绕过技巧一](3.1.5.md)
     - 3.2.2 [绕过技巧二](3.1.6.md)
 - 3.3 [gpc的绕过](3.3.md)
     - 3.3.1 [宽字节](3.3.1.md)
     - 3.3.2 [字符串偏移](3.3.2.md)
     - 3.3.3 [sql二阶注入](3.3.3.md)
     - 3.3.4 [乱用字符串处理函数](3.3.4.md)
     - 3.3.5 [乱用编码](3.3.5.md)
 - 3.4 [单引号、双引号和反引号](3.4.md)
 - 3.5 [php-cgi与php-fpm](3.5.md)
 - 3.6 [php5.3版本以后的$_REQUEST](3.6.md)
 - 3.7 [变量覆盖](3.7.md)
 - 3.8 [php常见的敏感函数](3.8.md)
	 - 3.8.1[intval的错误使用](3.8.1.md)
	 - 3.8.2[其他函数](3.8.2.md)
- **4.[php与其他程序](1.1.1.md)**
 - 4.1 [解析漏洞](4.1.md)
     - 4.1.1 [iis6.0](4.1.1.md)
     - 4.1.2 [apache](4.1.2.md)
     - 4.1.3 [nginx](4.1.3.md)
 - 4.2 [mysql截断](4.2.md)
     - 4.2.1 [长度限制截断](4.2.1.md)
     - 4.2.2 [编码截断](4.2.2.md)
- **5.[多种漏洞结合](5.0.md)**
 - 5.1 [数据结合](5.1.md)
 - 5.2 [手法结合](5.2.md)
