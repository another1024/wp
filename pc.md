# rsa

信息泄露：

高明文已知攻击泄露main_arena，首先堆排布把main_arena放在chunk里面，然后写入n个a逐爆破判断是否与密文相等，。

有大佬短密文也做出来了。

利用：

洞1:exim4邮件解析漏洞（cve-2018-6789）

洞2:create off-by-one



# cal

洞1:堆溢出在设置字符串长度的时候





洞2:压栈堆溢出在逆波兰计算器里（这个不知道能不能做）



洞3：构造函数没限制索引，可以改got表

##### 洞4：CVE-2018-8174（在构造和析构函数处通过释放前执行脚本来触发漏洞）

a="asdf"

创建完成前设置b=a创造uaf

###### 或者

释放的时候

b=a构造uaf



# cppnote

upx壳改了符号，改回来工具直接脱壳

彩蛋： 输入10 getshell



洞1:堆溢出在edit的时候size没限制大小



洞2:存在double free漏洞

