# D3
三个用D3画成的图表  
three D3 plots using the version 4  

## Requirements(环境)
python 3  
d3.v4  

## Datasets(数据来源)  
github API:https://developer.github.com/v3/repos/  

## Online Demo(在线展示)  
http://chenhuaizhen.github.io/D3/  

## Input(输入)
首先输入一个合法的github链接，如 "https://github.com/torvalds/linux", 然后点击搜索  
Firstly input a legal github web link, such as "https://github.com/torvalds/linux", then click search button  
![image](https://github.com/chenhuaizhen/d3/raw/master/image/img0.jpg)

## Plot #1(图表1)
第一个图是一个双直方图，左右分别代表不同含义  
The first plot is a bi-bar chart which respectively represent for different means  
![image](https://github.com/chenhuaizhen/d3/raw/master/image/img1.jpg)

## Plot #2(图表2)
第二个图是仿造github的热力图，代表着每小时的提交次数  
The second plot is a heat map which represents the count of commit number of each hour  
![image](https://github.com/chenhuaizhen/d3/raw/master/image/img2.jpg)

## Plot #3(图表3)
第三个图主要是动态烈日图表，代表着指定作者的各个仓库里的编程语言的分布情况  
The third plot is a zoomable sunburst chart which count the number of bytes of different programming languages in different repositories of the specific author  
![image](https://github.com/chenhuaizhen/d3/raw/master/image/img3.jpg)