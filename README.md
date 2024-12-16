## 推荐、搜索、广告的区别
1、根本问题上的区别

广告直接目的是增加公司的收入，推荐的直接目的是增加用户的参与度，从而间接增加公司收入，搜索所要解决的关键问题是围绕用户输入的搜索词展开，而推荐算法强调的个性化永远只是搜索算法的补充

2、优化目标的区别

广告：因为CPC (Cost-per-click)=消费量/点击量，对于广告主来说，就是每次点击（广告）的（付给网站主的）成本；对于媒体（或网站主）来说，就是用户每次点击（广告）（向广告主收取）的费用和CPA (Cost Per Action)=消费量/转化量，即按转化计费，广告费用支付给广告主的是每完成一个预设目标的费用，仍然为效果类广告系统的主流计价方式，所以只有预估出CTR（点击率）=点击量/展现量和CVR（转化率）=转化量/点击量才能反向推导出流量的价值，然后给出合理的出价。针对此，广告算法将预估偏差作为首要评价指标

推荐：推荐算法的预估目标不尽相同，视频类更多倾向于预测观看时长，新闻类预测CTR，电商类预估客单价等等这些和用户参与度最相关的业务指标，而且推荐算法的应用场景是生成一个列表，所以更加关注项目间的相对位置，因此评估阶段更倾向于用AUC (Area Under the Curve)、gAUC(group AUC)实际上是计算每个用户的AUC，最后计算加权平均，MAP(average precision)这些指标作为评价指标

搜索：由于搜索在某种意义上存在正确答案，所以搜索非常看重能否把这些正确答案召回，所以搜索系统往往会针对找回了、MAP、NDCG这些指标进行优化

总计：广告算法注重‘估得更准’，推荐算法注重‘排的更好’，搜索算法注重‘搜的更全’

3、算法模型设计中的区别
广告：

推荐系统的应用
- 电商首页推荐（淘宝、京东、拼多多）  
- 视频推荐（抖音、快手、B站、爱奇艺）    
- 饮食推荐（美团、饿了么、叮咚买菜）  
- 音乐电台（网易云音乐、QQ音乐、喜马拉雅）  
- 资讯、阅读（头条、知乎、豆瓣）


