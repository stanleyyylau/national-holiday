## Tour of the core

Learn how to read ref on the codex


## the loop

* wordpress根据URL里决定加载哪个模版文件以及到数据库读取哪些信息
* the loop的核心在于wp_query, wp_query是WP_QEUERY的一个instance
* WP_QUERY Class  这个class会生产sql查询语句
* WP_QUERY Class  里面可以查询meta, taxonomy等，看下面Advanced Search的例子



## 参考资料

[Life of a Front-end WordPress Request](https://roots.io/routing-wp-requests/) 
[Building An Advanced WordPress Search With WP_Query](https://www.smashingmagazine.com/2016/03/advanced-wordpress-search-with-wp_query/)
[WP_Query Generator](https://generatewp.com/wp_query/)