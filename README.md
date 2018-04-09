流程化 机器学习框架 基于 scala java语言 ,一站式自动机器学习平台 ,主要包括数据分析 特征工程 ，机器模型，自动部署，超参数优化，模型自动优化，自动扩容分配创建功能，类似第四范式、阿里PAI平台、google autoMl、亚马逊SageMaker 

工作比较忙，空余周末时间或者 下班回家后才有时间写一些代码
todo:1.封装一个DataFrame抽象层
todo:2.封装DataFrame -> spark DataSet/DataFrame转换
todo:3.封装Graph 可视化设计 flow 
todo:4.FlowGroup flow的处理 connction node


最近架构这一块，要考虑很多，要仔细想一想，
以前自己实现了很多，但是最后发现无法实现复杂业务场景，复杂的图模式
以及复杂的各种交互以及各种节点依赖关系并行控制问题，所以这开源项目打算重新实现一套体系
不在使用以前自己实现的一站式机器学习平台的架构体系，全面支持复杂系列 以及 复杂图 上下界点依赖。
尽量更新在今年年中出可运行版本



github博客:http://beautifulnow.club/


##特点

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

* 1.采用scala java 对spark 进行扩展封装， 
* scala spark ml
* 2.常用的机器学习算法 +深度学习算法 +强化学习算法
* 3.图像 文本NLP 声音 各种推荐算法特征工程支持
* 4.图计算支持 时间系列支持
* 5.同时计划支持mxnet tensorflow dl4j bigdl 模型无缝支持兼容
* 计划支持可视化探索分析
* flow流程化调度

### 功能图：
 
 计划后面实现kubernetes 实现自动扩容部署。

![功能图](https://github.com/beautifulNow1992/flowml/raw/master/images/1.png)

### 设计草稿图 
 ![flowml设计初稿](http://7xllic.com1.z0.glb.clouddn.com/2018-04-09-flowml设计初稿.png)
### 

1. ####数据管理


2. ####模型训练


3. ####模型评估


4. ####模型部署


5. ####执行预测


6. ####监控预测


7. ####模型自优化


8. ####可视化





