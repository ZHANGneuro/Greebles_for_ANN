# Greebles_for_ANN

```diff
! the stimuli were updated in 31th Jan 2021
```


### -Dataset and features:
There are 3253 Greeble-like images, each of them has two features: `Toogit (T)` and `Vacso (V)`, which varies from 0 to 2.7 unit of length relative to baseline greeble. The ratio of T & V (i.e. T/V) was represented by a point on sunbrust map with a center point defined at [3,3]. <br />
 <br />
 
The Greebles were categorized into two 'families': `Family_1` & `Family_2` depending on the line orientation on the map that the point locates. <br /> <br />
Family_1: `0°`，`60°`，`120°`，`180°`，`240°`，`300°` <br />
Family_2：`30°`，`90°`，`150°`，`210°`，`270°`，`330°` <br />
 <br />
 
 ```diff
For the number of greebles, there are on average 271 greebles for each of 12 orientations with identified step size on sunbrust map.<br />

The greeble file was named as family-(alignment)-ori-(angle)-xaxis-(ratio of change in unit of length)-yaxis-(ratio of change in unit of length)-md (movement distance), the movement distance (md=[1,2,3]) is the distance between the point on sunbrust map and the baseline greeble (coordinate 3,3), md=3 is farest, md=1 is nearest, only md=2 & 3 were used<br />
```



### -Goal
Training ANN to recognize the family (Family_1 or Family_2) given a specific greeble.

### -Download dataset
For full version of dataset (~5GB), download from BAIDU cloud, link:<br />
链接: https://pan.baidu.com/s/190CJP9TpJkJUErA3vYK0zg  <br />
密码: 97dk<br />
--来自百度网盘超级会员V4的分享
<br />


![alt tag](https://github.com/ZHANGneuro/Greebles_for_ANN/blob/master/Greebles_for_ANN/illustrator_figure-01.png)
<br />

#### The stimuli were modified based on the original paper and shared materials below 
##### *Gauthier, I., & Tarr, M. J. (1997). Becoming a “Greeble” expert: Exploring mechanisms for face recognition. Vision research, 37(12), 1673-1682.*
##### *https://wiki.cnbc.cmu.edu/Novel_Objects.*
<br />

#### This is a ongoing project in Prof. Liujia lab
##### *https://www.tsinghua.edu.cn/xlxxzh/*
<br />

bo <br />
2021-01-22
