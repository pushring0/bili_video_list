# bili_video_list
### 说明:
**bilibili指定频道视频信息爬虫,以某个频道的个人空间为入口,爬取该频道下所有视频信息**<br>
有一天在开眼短视频看到了一个非常不错的视频,但是当时没有及时收藏,某天空闲时间想起了那个视频,但是已经没什么印象了,关键字都忘了,发现B站有开眼视频个人空间,于是想要写个爬虫把所有视频标题和描述download.<br>
最开始看源代码发现是js加载,于是想到用selenium+phantomjs模拟js加载去下载视频信息,但是出现了两个小问题,一是速度慢(不是一般的慢),二是代码难看(当时想着出去玩,胡乱写的)<br>
又过了不知道多长时间,整理文件夹时发现了这个py文件,然后用Firefox抓包,重新写的这个<br>
**代码仍然很丑**<br>
**就是自己用的**
### 使用:<br>
要提供一个数据,红圈内的数字<br>
![视频aid](http://7xqu3i.com1.z0.glb.clouddn.com/snipaste_20170504_192351.png)
