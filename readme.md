笔记本
====
1.基础功能
---
	1.1显示时间戳（这里可以显示具体的记录时间）
	
![aa](https://github.com/xieyueyin/newPicture/blob/master/tupian/Screenshot_2018-06-10-22-30-38.png)
<br>

时间戳的显示可以通过修改数据库的数据信息，然后添加一个修改时间的long字段，这样可以看到在运行截图的页面内的一些时间戳有显示出来。
添加了一个TextView显示时间戳。
	
	1.2搜索功能
![aa](https://github.com/xieyueyin/newPicture/blob/master/tupian/Screenshot_2018-06-10-22-30-32.png)
<br>
	
可以为自己的note增加搜索功能，也就是可以根据title进行note的搜
使用使用了toolbar + searchview + recyclerview 实现搜索功能
	
	
2.附加功能3
----
	2.1美化UI
	
	2.2修改背景图片的颜色
![](https://github.com/xieyueyin/newPicture/blob/master/tupian/Screenshot_2018-06-10-22-31-55.png)
![](https://github.com/xieyueyin/newPicture/blob/master/tupian/Screenshot_2018-06-10-22-32-14.png)
![](https://github.com/xieyueyin/newPicture/blob/master/tupian/Screenshot_2018-06-10-22-32-20.png)


使用了DialogFragment + 横向的ReclcyerView布局，对ui界面进行美化，可以对note的背景选择更换颜色，用户可自由选择自己所喜欢的颜色来更换默认的颜色。
	
	2.3排序
![](https://github.com/xieyueyin/newPicture/blob/master/tupian/Screenshot_2018-06-10-22-30-44.png)
![](https://github.com/xieyueyin/newPicture/blob/master/tupian/Screenshot_2018-06-10-22-30-51.png)
![](https://github.com/xieyueyin/newPicture/blob/master/tupian/Screenshot_2018-06-10-22-30-57.png)


这里使用了ReclcyerView+spinner，增加了排序的功能，可以使用时间排序，对记录的笔记进行时间轴的排序，可以看到页面内的note的记录根据了时间轴的顺序来排列，还可对颜色、标题进行排序，颜色可根据笔记的颜色顺序进行排列。还可对标题首字母或者是数字进行排序。
