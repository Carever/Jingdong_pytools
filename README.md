# 京东 抢购 抢券 脚本 秒杀
京东 抢购 抢券 脚本 秒杀
使用方法请参考https://blog.csdn.net/weixin_45020214/article/details/123938592

python 3.10

依赖

抢购：

pip install selenium

pip install datetime

抢券：

pip install requests

pip install datetime

抢券目前单线程，后续开发多线程

59-20的券api：https://api.m.jd.com/client.action?functionId=newBabelAwardCollection&body={%22activityId%22:%22csTQSAnfQypSN7KeyCwJWthE6aV%22,%22from%22:%22H5node%22,%22scene%22:%221%22,%22args%22:%22key=m1a5teeereibadl8c9m9s812171a4448,roleId=76866119%22}&client=wh5
