### 请勿用于非法用途！

### 具体介绍：https://yzddmr6.tk/2019/09/01/BestShell/

### 代码开源不含后门

### 如何利用webshell-venom对大马免杀：
https://yzddmr6.tk/2019/09/03/webshell-venom-3-3/

### TODO

1. 内嵌 `https://github.com/yangyangwithgnu/bypass_disablefunc_via_LD_PRELOAD`

2. 把path参数base64一遍


## 4.0 更新日志

1. 修复php7.0之后将不再支持与类名相同的构造方法的问题，支持php所有版本。


## 3.0 更新日志

1. 修复压缩功能  (mmp改了好久)

2. 支持单文件下载

3. 改正错别字 :  登陆->登录

4. 更新cmd命令集合，更方便

5. 增加 PHP 执行命令的函数(proc_open,COM('Wscript.shell'), shellshock)，可以在某些情况下bypass disable_function


## 2.0 更新日志

1. 去除后门

2. 修复乱码问题

3. 所有数据提交均采用base64方式，实测绕过waf

4. udf提权自动加载路径，不用再select @@basedir了，并且修复了一个加载路径时的小bug

5. 去除大马标题，防止谷歌黑客找马

6. 从其他大马里移植了顶部函数

