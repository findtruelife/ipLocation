# ipLocation
This is a library of IP, contains the provinces, cities, latitude and longitude

由于之前的vps到期，所有决定使用github来存放代码。
本期ip库更新时间是2016-02-19.
本ip库，支持查询国家，省份，城市，经纬度，运营商等。

关于本程序并发测试（在个人电脑上测试，在linux server上测试上万很轻松）：

Concurrency Level:      500
Time taken for tests:   10.789 seconds
Complete requests:      50000
Failed requests:        0
Write errors:           0
Total transferred:      14350000 bytes
HTML transferred:       8200000 bytes
Requests per second:    4634.50 [#/sec] (mean)
Time per request:       107.886 [ms] (mean)
Time per request:       0.216 [ms] (mean, across all concurrent requests)
Transfer rate:          1298.93 [Kbytes/sec] received
在个人电脑上每秒支持5k左右的查询，在服务器(8核双线)上测试qps轻松达到1.2w左右。

