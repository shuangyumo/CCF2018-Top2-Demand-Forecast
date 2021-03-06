# CCF2018-Top2-供应链预测
## 赛题背景
##### 浙江执御信息技术有限公司是一家专注出海的跨境电商企业，利用移动互联网创新和大数据应用，助力中国制造升级，将中国和全球的优质品牌、设计、产品输送到“一带一路”沿线国家和地区。在电商产业链中，为提升用户物流服务体验，供应链协同将货品提前准备在全球各个市场的本地仓，可有效降低物流时间，极大提升用户体验。不同于国内电商物流情况，出海电商的产品生产和销售地区是全球化的，商品的采购，运输，海关质检等，整个商品准备链路需要更长的时间。在大数据和人工智能技术快速发展的新时代背景下，运用大数据分析和算法技术，精准预测远期的商品销售，为供应链提供数据基础，将能够为出海企业建立全球化供应链方案提供关键的技术支持。

## 赛题任务
##### 供应链需求预测，对原问题做建模问题简化。考虑商品在制造，国际航运，海关清关，商品入仓的供应链过程，实际的产品准备时长不同。这里将问题简化，统一在45天内完成，供应链预测目标市场为沙特阿拉伯。赛题为运用平台积累最近1年多的商品数据预测45天后5周每周（week1~week5）的销量。

#### 具体Task参考 https://www.datafountain.cn/competitions/313/details/data-evaluation?lang=en-US 我们对该问题的思考，答辩PPT，及Xgboost单模型代码均开源。有幸在决赛拿到Top1的成绩，但Seq2Seq由于为队友手工实现，成为了他的专属轮子和Trick，故在此不放出，如有任何需要探讨FFT与Seq2Seq的使用可发邮件与我联系。

