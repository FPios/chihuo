#吃货
-------------------------------  
                                    Author:朱海飞<br/>
                                    PhoneNum:13641906375<br/>
                                    E-mail:zhuhaifei_ios@163.com<br/>
                                    
                          *文采不是太好，写的不是太详细，具体内容可面试详谈，谢谢*

***************************************************************
##介绍
* 这里有你最想要的美食`教程`. <br/>
* 这里的教程通俗易学`简单易上手`.  <br/>

***************************************************************


##作品展示　　
![](https://github.com/SummerHF/chihuo/raw/master/gif/chihuo.gif)
***************************************************************
##主要模块

### 专题模块
* **这个模块主要使用collectionView来展示分类数据** <br/>
  * **你可以在这里找到任何想要的分类教程** <br/>
    * **界面展示**  

![](https://github.com/SummerHF/chihuo/raw/master/gif-show/specialList.gif) 

     实现思路
     1>使用collectionView展示数据
       1.1 使用两组来展示数据
       1.2 第一组自定义cell 点击cell 跳转到另一个控制器，使用webView加载网页数据   
       1.3 第二组 设置headerView 用来展示广告 点击广告 跳转到相应的链接
       1.4 第二组自定义cell 使用流水布局即可 用来展示分类数据
     2>使用AFNetWorking 加载数据 并且缓存到本地 使用FMDB缓存数据到本地 利用返回数据的每个字典中的id作为字段 缓存一条记录 
     3>使用SDWebImage加载分类图片 为了提升用户体验 可使用占位符提示用户正在加载数据 
     4>下拉加载更多,使用MJRefresh实现即可，同时要保证数据插入到数据库中.
     
     5>分类控制器的内容大致如此，关于选中相应的控制器的push操作面试详谈。
     
### 分类模块
* **这个模块主要使用tableview来展示** <br/>
  * **你可以在这里找到想要的其他分类** <br/>
    * **界面展示**  

![](https://github.com/SummerHF/chihuo/raw/master/gif-show/category.gif) 

    
### 图集模块
* **这个模块主要使用tableview来展示** <br/>
  * **你可以在这里找到想要的图集** <br/>
    * **界面展示**  

![](https://github.com/SummerHF/chihuo/raw/master/gif-show/photoList.gif) 

***************************************************************
