# Week0-WP
自己拖延症很严重啊，拖到现在一起写，以后还是要日积月累！

.Web从0开始之0
题目描述：WEB页面的HTML，CSS，JS客户端是可以查看的哦～你能在平台源码中找到FLAG么？
1.火狐firebug查找hctf；
2.chrome F12查找hctf。

.Web从0开始之0.1
题目描述：你知道一个网页从输入URL到显示出页面，都经历了啥么？
firebug，点击 “网络”进行抓包，即可快速得出flag（有时它总不出来，可以先看看firebug“网络”是否被禁用，若已开启，则尝试刷新一下页面）

.Web从0开始之0.2
题目描述：你知道啥是cookie吗？那么你会修改它吗？
使用Edit ThisCookie工具（可下载后在chrome上装）修改值false为true,刷新一下页面，flag就打印在页面上了。

.MISC从0开始之编码0
题目描述：SENURntUSElTSVNCQVNFNjRFTkNPREV9     base系列编码
直接百度Base64编码/解码，把题目描述的一串copy进去，然后解码。

.密码学从0开始之0	
题目描述：ojam{AopzpzJhlzhyWhzzdvyk}
ojam对应hctf，剩下的字母依次推出
开学上了第一节密码学课，刚好讲了这个东西，我复习一下，把它数字化表示。
A(a)--1,B(b)--2, ... ,Y(y)--25,Z(z)--0
加密：Ek(m)=m+kmod(26)    m为明文，即当前字母；k为密钥，即当前字母后或前几位；
解密：Dk(m)=c-kmod(26)

.MISC从0开始之Steganography0
题目描述：AK菊苣的小姐姐们之0～
先把链接里面的图片保存一下，然后下载stegsolve,下载好这东西之后，一开始我一下子就懵了，不知道怎么使用，后来终于让我百度到了
大家不会用的话可以参考一下这个哈，虽然他说的是Win7的方法，但我Win8按他的 步骤也没问题。
http://jingyan.baidu.com/article/200957617c3619cb0621b44d.html
最后终于可以打开stegsolve了，然后打开图片analyse,flag就出来了（这里还有一个小地方提交时候要注意，直接复制flag粘贴到平台上提交，
它会说答案错误，后来终于发现直接复制的中间的某个地方有个空格，删掉它提交就好了，不知你们有没有遇到这个问题）

写在最后：做这些题不仅是乐趣，更多的是自己学到东西，而总结WP挺重要，以后要积极总结，及时写下来，可以进一步巩固， 不能再拖。
而且，写笔记是很好的习惯哇！
