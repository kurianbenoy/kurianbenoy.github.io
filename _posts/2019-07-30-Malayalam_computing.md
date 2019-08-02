---
layout: post
title: Malayalam Computing
tags: [malayalam, conference, SMC]
comments: true
---

During [MEC.Conf](https://conf.mec.dev/), we had one of of our keynotes by Santhosh Thottingal,
Developer Wikipedia and active contributor of [Swathanthra Malayalam Computing](https://smc.org.in/).

> During his talk he had asked who all knew to type `Malayalam` in computer?

Very few people raised their hands. He asked the audience to name some fonts in Malayalam equivalents to
Aerial and TimesNew Roman which is familar to all of us. Only Lakshmi Sunil and Aathira Naveenan raised their
hands. Santhosh emphasised in his talk that only 20% of world popluation know to read and write English.
This is very true, I have seen a bunch of Switzerland natives who don't even know to spell their names correctly
in Immigration counter.


Santhosh challenged us to write a Hello world program in Amma Malayalam. Check out my *hello world program*


```
>>> print("ഹെല്ലൊ വേൾഡ് ")
ഹെല്ലൊ വേൾഡ്
```

You can even program just with `Malayalam`. *Did you folks know Python3 was revamped from Python2 for unicode support?*  See the function implementation as shown here:


```
>>> def ഗണിക്ക(ക,ഖ):
...     return(ക*ഖ)
...  
>>> ഗണിക്ക(3,6)
18
```

![alt text](/img/withsanthosh.jpg "Logo Title Text 1")

He told about some important Malayalam projects like [Morphological Analyser](https://github.com/smc/mlmorph),
[sentence predictor](https://gitlab.com/smc/mlpredict).
The unique thing is most of his project doesn't use Machine
learning hype. I am planning to understand these project and 
explore this in depth in coming months.

As an AI enthusiast. I enquired with Santhosh about the possibility of Malayalam 
computing expanding with Machine Learning. According to Santhosh, inorder to use 
machine learning in Malayalam, you need lot of data and infrastructure.
So some of popular techniques in NLP like Neuro Machine Transulation cannot
be applied for Malayalam. So most of the projects by SMC are discrete and 
definite in nature. Instead of predicting nature in Machine Learning.

Do checkout Santhosh Thottingal sir being interviewed by Sreeram Venkitesh in the 
below link:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/Tr6Wxiusr54/0.jpg)](https://www.youtube.com/watch?v=Tr6Wxiusr54)

{% include disqus.html %}
{% if page.comments %}