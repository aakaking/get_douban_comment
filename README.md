# get_douban_comment
## 爬虫获得豆瓣的电影评论

从一个初始网页开始， 获得足够多的豆瓣电影评论（使用DFS 广度优先 遍历电影id）

必须要获得的数据:

<豆瓣电影的id， 电影名称， 时间， 评论， 星级>

例如:

+ <21345, 阿甘正传， 1994， “简直太棒了”, 5>
+ <21345, 阿甘正传， 1994， “五星好评！！！”, 5>
+ <21345, 阿甘正传， 1994， “五星好评！！！”, 5>
+ <21345, 阿甘正传， 1994， “五星好评！！！”, 5>
+ <12314, 西游外传， 2001， “真懒！！！”, 1>

## Requirement

+ bs4   # beautiful soup
+ requests
+ jieba
+ pandas
