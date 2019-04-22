# zhaopin_spider
***
### 说明
1. 用scrapy编写的一个可以爬取智联招聘全部职位信息的爬虫；
2. 爬虫文件keywords_spider用于爬取智联招聘首页的工作关键字，并存储到json文件中，但是在运行的时候需要关闭pipline；
3. test.py文件用于编写过程中部分代码测试；
4. run_spider文件可直接运行爬虫
5. 如果有人需要使用本项目，只需要修改settings文件下的数据库相关设置；
6. 数据存储在MongoDB数据库中,运行前请确保MongoDB服务已启动，数据库以及集合已创建；
7. Python版本3.6.3
8. Scrapy版本1.5.1
***
### 运行
1.需要安装MongoDB数据库，并开启服务;
2.命令行运行
```
 python main.py
```
3.也可以再IDE中直接运行main.py文件;

4.settings.py文件根据自己的系统自行更改。
