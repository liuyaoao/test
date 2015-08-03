# test
this is a test project ,my first github project.

moment.js 使用注释：
moment().format('YYYY-MM-DD HH:mm:ss'); //2014-09-24 23:36:09,获取当前时间，并以特定格式输出。
moment(1437925575663).format('YYYY-MM-DD HH:mm:ss'); //2015-07-26 23:46:15， 把指定的时间戳转换成特定格式的字符串。
moment("2015-08-18 11:33:28").format("x"); //1439868808000 , 这个把指定格式的字符串转换成时间戳long型。注意这里的x只能是小写。
moment(1439868808000).format("YY");//15. 取得时间戳的年份，如果是四个Y,则表示2015.注意Y要大写。
moment(1439868808000).format("MM");
//08. 取得时间戳的月份，如果是两个M,则表示08,一个M表示8，没有前导0.注意M要大写。M可取：M,MM，MMM,MMMM(英文的完整月份).

moment(1439868808000).format("m");
"33"   //表示分钟。两个mm，表示有前导0.
moment(1439868808000).format("h");
"11"  //表示小时。两个h表示有前导0，，如果H大写的话，表示24小时制。
moment(1439868808000).format("s");
"28"   //表示秒数。 两个s表示有前导0的秒。
moment(1439868808000).format("Q");
"3" //Q表示第几季度。（1-4）
moment(1439868808000).format("d");
"2"  //星期中的第几天。d可取d,ddd,dddd.分别表示的格式是：(0到6，0表示周日，6表示周六),(Sun到Sat),(从Sunday到Saturday)
moment(1439868808000).format("D");
"18"  //表示月份中的第几天，D可取D,DD， 分别表示没有前导0,有前导0。。。
