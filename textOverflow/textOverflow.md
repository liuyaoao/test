## 文本溢出超出多少个字数后更多和收起操作的插件


text_overflow.js 使用注释：
-----------------
###使用方法：

1.设置所需的长度

    $(this).attr("displayLength","字节长度")

2.调用该插件

    1.溢出与还原切换

    $(this).un_displayPart();

     2.溢出不还原

     $(this).text_overflow();

###插件原理：

    	获取对象的html文本，根据所需的字节长度，取其该需要的长度，然后在该长度后面加"..."; //frht
