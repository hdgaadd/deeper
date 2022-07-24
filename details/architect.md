# article of meituan

- **深度学习在搜索业务中的探索与实践**

  > https://tech.meituan.com/2019/01/10/deep-learning-in-meituan-hotel-search-engine.html

  1. 具体分层实现

     根据输入关键词，找出相关性产品 -> 根据用户的行为雷达与特征，进行相关性产品的排序，推荐相对于该用户的最优产品 -> 降权，某些商家若在平台有作弊记录，把排序级别降低

  2. 关键词分析

     - 查询时需添加**用户所在地**的权重
  
     - 去除无关字符串
  
     - 匹配同义词
  
     - 判断关键词是走**文本匹配**、还是'**地标匹配**'
  
       如用户搜索某个地标点，其实是想找附近的酒店，则需走'地标匹配'
  
- **研发团队资源成本优化实践**

  > https://tech.meituan.com/2019/02/21/rd-team-resource-cost-optimization-practice.html

  1. 成本控制，**预**则立

  2. 每个项目申请的资源机器须有量化的**评价指标**，阐明该机器所需资源范围

  3. **分摊成本**控制

     预防本项目所提供的第三方服务占用了过量的资源



# article of COOLSHELL

- **与程序员相关的CPU缓存知识**

  > https://coolshell.cn/articles/20793.html

  1. 