WoutLa乌拉公链--节点智能合约部署器



1 、访问Remix
http://节点的IP:8080
界面如下：
 ![](https://img-blog.csdnimg.cn/20181107101555431.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1dvdXRsYQ==,size_16,color_FFFFFF,t_70)

至此，Remix算是配置完成了。

2、调试部署合约


1）.当前的solidity版本，如上图截图所示为0.4.9，这个默认用的是当前最新的release版本：

 ![](https://img-blog.csdnimg.cn/20181107101621131.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1dvdXRsYQ==,size_16,color_FFFFFF,t_70)
 


2）. 点击下拉框，可以选择不同的版本，包括还未成熟的最新构建版本，或者是之前的版本等。 选择release版本，如下图所示的这些 ：

 ![](https://img-blog.csdnimg.cn/20181107101637933.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1dvdXRsYQ==,size_16,color_FFFFFF,t_70)

3） 合约自动编译后生成:

 ![](https://img-blog.csdnimg.cn/20181107101653929.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1dvdXRsYQ==,size_16,color_FFFFFF,t_70)

4） 点击create,会在内存中将该智能合约创建一个实例，即将下面的web3 deploy代码部署在虚拟的内存中: 

 ![](https://img-blog.csdnimg.cn/20181107101707968.png)

