          **乌拉公链介绍**
          国内领先的区块链技术开发商。区块链技术研发，分布式数据库开发，大数据研发，链式数据研发，高容错的分布式系统设计，去中心化的数据库建设。
                Woutla乌拉公链--为行业应用而生，乌拉公链技术开发团队，致力于区块链技术落地，解决行业痛点，为行业提供区块链底层基础设施服务和架构DAPP开发，信息数据上链数字资产管理等多维度场景应用。           Woutla乌拉公链，邀您共创链上世界：公链开发/数字钱包/区块链跨境支付结算技术/区块链溯源商城/区块链供应链金融开发/智能合约/区块链竞猜应用等

智能合约部署器
1 、访问Remix
http://节点的IP:8080
界面如下：
 ![](https://img-blog.csdnimg.cn/20181127142401857.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1dvdXRsYQ==,size_16,color_FFFFFF,t_70)
至此，Remix算是配置完成了。
2、调试部署合约

1）.当前的solidity版本，如上图截图所示为0.4.9，这个默认用的是当前最新的release版本：
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/20181127142429112.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1dvdXRsYQ==,size_16,color_FFFFFF,t_70)
 

2）. 点击下拉框，可以选择不同的版本，包括还未成熟的最新构建版本，或者是之前的版本等。选择release版本，如下图所示的这些。但是所选择的版本一定要和智能合约中引用的版本一样或者更高，这样才会编译通过。
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/20181127142448213.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1dvdXRsYQ==,size_16,color_FFFFFF,t_70)
3）. 合约自动编译后生成:
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/20181127142503859.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1dvdXRsYQ==,size_16,color_FFFFFF,t_70)
4）.点击create,会在内存中将该智能合约创建一个实例，并将该合约发布到指定的区块链上:
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/20181127142518596.png)

