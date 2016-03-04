#week1-Wp
平时不写，就得挑灯夜战！以后不能这样子！

#密码学从0开始之1
题目描述： http://ctf.lazysheep.cc:8081/cry1.html

flag不是标准格式，提交你解出的明文就行，flag全是大写

首先打开链接是空白页，不要慌，查看网页源代码，出来一群很凌乱的东西，当时直接copy它一百度明白它叫摩斯密码。

刚开始照着百度密文对应的字母一个一个进行人工翻译，后来发现有一个叫摩斯密码翻译器的东西，直接copy那段密文翻译一下就出来flag了。

#WEB从0开始之PHP代码审计0	
题目描述：http://ctf.lazysheep.cc:8081/web1.php    (PHP)

name和password不能相等，后面的sha1(name)等于sha1(password)，因为sha1只能对字符串散列，对数组类型会返回NULL

name[]=1,password[]=2（也可别的常数）,值不等，跳过第一个判断， 而sha1返回NULL，可得出flag。
