# 爬取cnvd最近3年的漏洞详情

## 环境

软件 |版本 
 -|-
 python|3.6
 requests|
 sqlalchemy|
 mysql|5.7

`sudo python3 -m pip install --upgrade pip`

`sudo python3 -m pip install --upgrade setuptools`

<!-- `sudo python3 -m pip install -i https://pypi.tuna.tsinghua.edu.cn/simple/ scrapy` -->

`sudo python3 -m pip install -i https://pypi.tuna.tsinghua.edu.cn/simple/ sqlalchemy`

## 功能

* 按顺序依次爬取cnvd的漏洞详情,起始url在代码中修改

* 使用sqlchemy保存数据,也可以改为csv文件存储

* 使用前请先修改数据库的连接信息与User-Agent

## 运行

`python3 cnvd2.py`