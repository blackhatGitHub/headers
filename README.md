#!/usr/bin/python
# -*- coding: UTF-8 -*-

>>> import urllib2
>>> url='http://www.baidu.com'
>>> user_agent='Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/50.0.2661.87 Safari/537.36'
>>> request = urllib2.Request(url, headers={'User-Agent' : user_agent})
>>> response = urllib2.urlopen(request)
>>> page = response.read()
