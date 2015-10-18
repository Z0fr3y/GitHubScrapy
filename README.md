# GitHubScrapy
运行：scrapy crawl github

一.目录介绍

1.crawl目录存放的是按ctrl+c暂停后
运行scrapy crawl github -s JOBDIR=crawl/github_stop（暂停后再运行使用） 时的信息，里面是github_stop目录，
接着里面是requests.queue目录、request.seen 、spider.state。

2.GitHub/spider目录便是爬虫的全部代码/文件。

3.GitHub/media目录是存放爬取信息的。里面有people与people_image文件。

4.github.com和crawl里面的github_stop文件一致。

5.logs文件记录的是爬取的具体信息。

6.GitHub01_data_utf-8.json等文件是经多次测试后存留的文件QAQ。

运行此爬虫还需要下载NOSQL（MonGoDB），及MongoVUE（windows下的软件）。



注：连接数据库代码是网上的QAQ，不是我写的OAO.......闪。
