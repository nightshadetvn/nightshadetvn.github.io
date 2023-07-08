---
layout: post
title: shodan and it's power
---

today i would like to present shodan - the search engine for the internet of everything. it allows users to query for devices of specifics they request - almost like google but actually good :>

lately i have been doing a audit for a private company and i encountered a brand of cameras that manufacter don't provide secure, nor chosen in setup. it's name is "Kenik" - they are a polish based security camera company.

my research has shown that in the [user's manual](http://e-commercepartners.home.pl/public_html/kenik/wp-content/uploads/2017/11/instrukcja_obslugi_kamery.pdf) the default username is "admin" and password is blank. that, combined with shodan allowed me to make a [search query](https://www.shodan.io/search?query=Kenik) that shows their cameras via web. this allows to search for some cameras that left the default passes. 

![shodan]({{ site.baseurl }}/images/shodan-ss.png)

interesting results :P enjoy
