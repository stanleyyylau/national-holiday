## Data Management

* 了解Wordpress 十一张表之间的关系
* 用wpdb这个class 直接操作数据库 学习增删查减

## Custom Post type and taxonomy

这里注意了解如果创建custom post type, taxonomy, custom fileds已及创建的时候有哪些选项可以用

深入了解taxonomy相关的三张表，以及一张wp_term_meta表

wp_terms存放所有分类，小分类，子分类数据，以及对应的slug，比较简单。

![wp_terms](https://ws2.sinaimg.cn/large/006tKfTcgy1fk59htlvtjj30ru0bsdh8.jpg)

wp_terms_taxonomy存放分类terms和他们对应的分类法，父分类

![wp_terms_taxonomy](https://ws1.sinaimg.cn/large/006tKfTcgy1fk59l5dm82j316i0as3zz.jpg)

wp_term_relationships存放某篇文章对应的terms_taxonomy_id 一篇文章可以对多个

![wp_term_relationships](https://ws3.sinaimg.cn/large/006tKfTcgy1fk59my4dm0j30k40800t3.jpg)

