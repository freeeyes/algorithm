#算法汇总
##目的
>总结各个产品线上用到的算法，抽象各个算法的应用场景。
>
>将算法按照语言和场景划分，提供通用的输入输出，为程序员项目程序开发提供便利。
>
>此算法浏览由算法小组提供，相关问题请反馈给次小组。
>
>算法版本考虑提供以下语言的支持C,C++,Java,Shell,Python
>
>因为有些算法目前涉及的开发语言比较集中，优先提供正在使用中的算法支持，未来扩展上述相关语言。
##算法总分类
###文件同步和分布式算法
* [Reed Solomon编码算法](./File/ReedSolomon.md)
* [Cauchy RS编码算法](./File/CauchyRS.md)
* [RAID5编码算法](./File/RAID5.md)
* [RDP(RAID6)编码算法](./File/RDP.md)
* [E-MBR编码算法](./File/E-MBR.md)
* [E-MSR编码算法](./File/E-MSR.md)
* [SRC编码算法](./File/SRC.md)
* [LRC编码算法](./File/LRC.md)
* [RAID1编码算法](./File/RAID1.md)
* [多副本高可靠性算法](./File/TranScript.md)
* [数据分布HASH算法](./File/HashFile.md)
* [目录虚拟分级算法](./File/DirLever.md)
* [大文件数据块分块算法](./File/BigFIleBlock.md)
* [高效遍历文件系统算法](./File/SearchFile.md)
* [路由选取均衡算法](./File/RouteChoose.md)
* [数据压缩算法](./File/CompressData.md)
* [数据分发算法](./File/DataSend.md)
* [任务调度主机名获取算法](./File/TaskDispatch.md)
* [分布式服务策略引擎服务节点选举算法](./File/NodeSelect.md)
* [文件队列算法](./File/FileQueue.md)
* [数据压缩gzip算法](./File/gzip.md)
* [纤芯自动调度算法](./File/FindOpticalFiberPath.md)
* [自动生成局向光纤算法](./File/AutoOpticalFiber.md)
* [负载均衡算法](./File/LoadBalancing.md)
* [容量算法](./File/Capacity.md)
* [fork/join详单查询算法](./File/FJ.md)

###加密解密算法
* [字符串加密解密算法](/Encry/StringEncry.md)
* [三户加密解密算法](/Encry/3UserEncry.md)
* [弱密码校验算法](/Encry/WeakPassword.md)
* [敏感信息加密解密算法](/Encry/SensitiveInformation.md)
* [3DES加解密算法](/Encry/3DES.md)
* [多表替代加密算法](/Encry/MutiTable.md)
* [RSA加密算法](/Encry/RSA.md)
* [BASE64算法](/Encry/Base64.md)

###排序和索引算法
* [Terasort排序算法](/Sort/Terasort.md)
* [LRU算法](/Sort/LUR.md)
* [T-Tree算法](/Sort/T-Tree.md)
* [递归算法](/Sort/Recursion.md)
* [二分查找算法](/Sort/BinarySearch.md)
* [快速排序算法](/Sort/QuickSort.md)
* [冒泡排序算法](/Sort/BubbleSort.md)
* [回溯算法](/Sort/Recall.md)
* [链表相关算法](/Sort/Link.md)
* [前序遍历森林数据结构](/Sort/ForestSort.md)
* [堆排序算法](/Sort/Heap.md)
* [sql迭代器算法](/Sort/SqlSort.md)
* [合并排序算法](/Sort/MergeSort.md)
* [令牌桶(Token bucket)算法](/Sort/TokenBucket.md)
* [语法树的节点遍历算法](/Sort/SyntaxTree.md)
* [文件排序算法](/Sort/FileSort.md)

###集合算法
* [集合运算算法](/Assembly/Assembly.md)
* [计算掩码位数](/Assembly/Mask.md)
* [斐波那契数列](/Assembly/Fibonacci.md)
* [排班的优先级算法](/Assembly/Paiban.md)
* [双休算法](/Assembly/Rest.md)
* [天地班算法](/Assembly/SkyField.md)

###AI算法
* [分治算法](/AI/DivideAndConquer.md)
* [动态规划算法](/AI/DynamicPlanning.md)
* [聚类算法](/AI/Clustering.md)
* [关联规则算法](/AI/Relevance.md)
* [决策树算法](/AI/DecisionMakingTree.md)
* [因子算法](/AI/Factor.md)
* [K-means聚类算法](/AI/K-means.md)
* [线性回归最小二乘法](/AI/LineArregression.md)
* [AHP算法](/AI/AHP.md)
* [灰色评估算法](/AI/GreyEvaluation.md)
* [BP神经网络算法](/AI/BP.md)
* [稳定交往圈模型算法](/AI/Association.md)
* [物品协同过滤算法](/AI/ItemFiltration.md)
* [ALS矩阵分解算法](/AI/ALS.md)
* [apriori频繁项集算法](/AI/Apriori.md)
* [KNN算法](/AI/KNN.md)
* [熵权值法](/AI/Entropy.md)
* [标准差权值法](/AI/StandardDeviation.md)
* [PCA权值法](/AI/PCA.md)
* [修正宾艾宾浩斯衰减方程](/AI/Binhaosi.md)
* [二次指数平滑分析算法](/AI/IndexAnalysis.md)
* [多线程任务分解算法](/AI/MutiThread.md)
* [HMM马科莫夫模型](/AI/HMM.md)
* [最短路径算法](/AI/ShortPath.md)

###Hash算法
* [3级HASH算法](/Hash/3levelHash.md)
* [可控Hash算法](/Hash/LimitHash.md)
* [MD5加密算法](/Hash/MD5.md)

###内存管理
* [共享内存管理](/Memory/MemoryManager.md)

###协议读写和转换相关算法
* [JSON解析算法](/Protocol/Json.md)
* [JSON和XML互转算法](/Protocol/Json2XML.md)
* [字符串转换成数组算法](/Protocol/String2Array.md)
* [从字符串获得键值对算法](/Protocol/String2Keys.md)
* [字符串替换算法](/Protocol/StringReplace.md)