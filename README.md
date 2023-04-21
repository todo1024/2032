# 2032
Elasticsearch【马士兵教育】| 完结
### 微:NoBug1024 


课程介绍：

Elasticsearch 是一个分布式、高扩展、高实时的搜索与数据分析引擎。它能很方便的使大量数据具有搜索、分析和探索的能力。充分利用Elasticsearch的水平伸缩性，能使数据在生产环境变得更有价值。Elasticsearch 的实现原理主要分为以下几个步骤，首先用户将数据提交到Elasticsearch 数据库中，再通过分词控制器去将对应的语句分词，将其权重和分词结果一并存入数据，当用户搜索数据时候，再根据权重将结果排名，打分，再将返回结果呈现给用户。



〖课程目录〗:

- ├──01_简介  
- |   └──01_课程介绍.mp4  85.75M
- ├──02_环境安装  
- |   ├──01_安装Elasticsearch.mp4  57.14M
- |   ├──02_安装Kibana.mp4  24.89M
- |   ├──03_安装Elasticsearch-Head插件.mp4  21.71M
- |   ├──04_集群的健康值检查.mp4  15.72M
- |   └──05_本章小结.mp4  190.57kb
- ├──03_核心概念(一)  
- |   ├──01_倒排索引的核心原理.mp4  36.90M
- |   ├──02_FOR压缩算法.mp4  49.19M
- |   ├──03_RoaringBitmap压缩.mp4  240.73M
- |   ├──04_Trie前缀树原理.mp4  21.27M
- |   ├──05_FST的构建过程.mp4  51.88M
- |   ├──06_FST在Lucene中的实现过程-1.mp4  51.45M
- |   ├──07_FST在Lucene中的实现原理-2.mp4  60.30M
- |   ├──08_tip和tim文件的内部结构.mp4  41.63M
- |   ├──09_FST在Lucene中的构建和读取过程.mp4  177.92M
- |   └──10_集群、节点和分片.mp4  72.67M
- ├──04_核心概念(二)  
- |   └──01_索引和文档的概念.mp4  4.24M
- ├──05_索引的CRUD  
- |   └──01_索引的CRUD.mp4  20.95M
- ├──06_Mapping  
- |   └──01_Mapping.mp4  97.87M
- ├──07_搜索和查询  
- |   ├──01_本章内容介绍.mp4  3.06M
- |   ├──02_ES的查询上下文、评分、元数据.mp4  33.89M
- |   ├──03_Query String.mp4  13.92M
- |   ├──04_全文检索：match.mp4  285.57M
- |   ├──05_精准查询：term.mp4  44.86M
- |   ├──06_过滤器：filter.mp4  77.67M
- |   └──07_组合查询：bool query.mp4  328.08M
- ├──08_分词器  
- |   ├──01_文档正常化：normalization.mp4  103.20M
- |   ├──02_字符过滤器：character filter.mp4  113.30M
- |   ├──03_令牌过滤器：token filter.mp4  187.35M
- |   ├──04_分词器：tokenizer.mp4  7.06M
- |   ├──05_自定义分词器.mp4  214.97M
- |   ├──06_中文分词器.mp4  231.38M
- |   ├──07_基于远程词库的热更新.mp4  391.48M
- |   └──08_基于MySQL的热更新.mp4  226.97M
- ├──09_聚合查询  
- |   ├──01_本章内容介绍.mp4  91.67M
- |   ├──02_三种聚合分类：Bucket、Metrics、Pipeline.mp4  73.37M
- |   ├──03_代码+案例演示三种不同的聚合.mp4  443.48M
- |   ├──04_嵌套聚合：基于聚合结果的聚合.mp4  295.16M
- |   ├──05_基于查询结果的聚合和基于聚合结果的查询.mp4  175.07M
- |   ├──06_聚合排序.mp4  146.27M
- |   └──07_常用的聚合函数.mp4  467.84M
- ├──10_脚本查询  
- |   ├──01_本章内容介绍.mp4  17.77M
- |   ├──02_Scripting基本概念.mp4  96.94M
- |   ├──03_Scripting的CRUD.mp4  181.79M
- |   ├──04_参数化脚本.mp4  136.93M
- |   ├──05_Scripts模板.mp4  48.45M
- |   ├──06_函数式编程.mp4  208.95M
- |   └──07_本章课程小结及知识点补充.mp4  274.72M
- ├──11_索引的批量操作  
- |   ├──01_基于_mget的批量查询.mp4  100.81M
- |   ├──02_文档的四种操作类型.mp4  116.07M
- |   └──03_基于_bulk的增删改.mp4  271.33M
- ├──12_模糊查询和智能搜索推荐  
- |   ├──01_关于课程使用ES的版本升级.mp4  175.24M
- |   ├──02_本章内容介绍.mp4  31.22M
- |   ├──03_prefix：前缀搜索.mp4  177.52M
- |   ├──04_wildcard：通配符.mp4  98.71M
- |   ├──05_regexp：正则表达式.mp4  3.23M
- |   ├──06_fuzzy：模糊查询.mp4  179.60M
- |   ├──07_match_phrase_prefix：短语前缀.mp4  85.45M
- |   └──08_前缀、中缀和后缀搜索的优化方案.mp4  110.25M
- ├──13_搜索推荐  
- |   ├──01_Term Suggester.mp4  434.56M
- |   ├──02_phrase suggester.mp4  214.71M
- |   ├──03_completion suggester.mp4  3.22M
- |   └──04_context suggester.mp4  245.52M
- ├──14_数据建模  
- |   ├──01_嵌套类型查询：Nested.mp4  347.64M
- |   ├──02_父子级关系查询：Join.mp4  155.08M
- |   └──03_Elasticsearch数据建模.mp4  40.16M
- ├──15_ES客户端  
- |   ├──01_本章内容介绍.mp4  25.88M
- |   ├──02_Java API和Transport Client.mp4  240.19M
- |   ├──03_基于Java API的CRUD.mp4  175.99M
- |   ├──04_基于Java API的多条件查找.mp4  92.33M
- |   ├──05_基于Java API的聚合查询.mp4  490.21M
- |   ├──06_Java REST Client.mp4  561.28M
- |   ├──07_Java REST Client的基础使用.mp4  188.26M
- |   ├──08_封装RestClient.mp4  993.98kb
- |   ├──09_嗅探器：Sniffer.mp4  94.73M
- |   └──10_总结性学习：使用ESClient处理常用操作.mp4  158.35M
- ├──16_Spring Data Elasticsearch  
- |   └──01_Spring Data Elasticsearch.mp4  267.06M
- ├──17_高手进阶篇  
- |   └──01_课程介绍.mp4  206.92M
- ├──18_分布式原理（一）  
- |   ├──01_单机服务和分布式.mp4  144.25M
- |   ├──02_分布式集群环境.mp4  277.24M
- |   ├──03_主从模式.mp4  49.18M
- |   ├──04_ES的常见模块-1.mp4  210.60M
- |   ├──05_ES的常见模块-2.mp4  71.01M
- |   ├──06_分片的创建策略.mp4  225.36M
- |   ├──07_集群级和索引级配置.mp4  243.48M
- |   ├──08_分片分配感知策略.mp4  17.44M
- |   └──09_强制感知策略.mp4  114.69M
- ├──19_分布式原理（二）  
- |   ├──01_容灾机制.mp4  3.95M
- |   ├──02_选举过程中两个重要的角色.mp4  180.49M
- |   └──03_高可用集群架构设计.mp4  502.57M
- ├──20_分布式原理（二）  
- |   ├──01_Master选举的必要前置认知.mp4  244.88M
- |   ├──02_选取临时activeMaster节点.mp4  518.88M
- |   ├──03_选举完成.mp4  3.79M
- |   ├──04_节点的失效监测.mp4  39.48M
- |   └──05_脑裂问题.mp4  96.97M
- ├──21_深度分页问题  
- |   ├──01_什么是深度分页.mp4  161.74M
- |   ├──02_深度分页问题的危害.mp4  40.29M
- |   ├──03_避免使用深度分页.mp4  8.23M
- |   ├──04_Scroll Search.mp4  110.87M
- |   ├──05_Search After.mp4  9.85M
- |   └──06_实战环境解决深度分页问题的思路.mp4  66.17M
- └──22_高级搜索  
- |   ├──01_most_fields和best_fields.mp4  226.71M
- |   ├──02_cross_fields策略及评分计算的基本规则.mp4  354.04M
- |   ├──03_搜索模板.mp4  239.57M
- |   ├──04_term vector.mp4  177.81M
- |   ├──05_高亮查询.mp4  24.60M
- |   ├──06_地理位置检索-两种数据类型.mp4  123.45M
- |   ├──07_Geo_point Based Query.mp4  362.22M
- |   ├──08_Geo_shape Based 几何图形存储.mp4  522.16M
- |   └──09_Geo_shape Based Query.mp4  656.11M

