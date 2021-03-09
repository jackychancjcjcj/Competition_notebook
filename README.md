# 目录
![Author](https://img.shields.io/badge/Author-CJ-red.svg "Author")
![LICENSE](https://img.shields.io/github/license/JoeyBling/hexo-theme-yilia-plus "LICENSE")
![Language](https://img.shields.io/badge/Language-python3.6-green.svg "Laguage")
![Last update](https://img.shields.io/badge/last%20update-22Feb%202021-brightgreen.svg?style=flat-square "Last update")
* [比赛](#比赛)
    * [结构化比赛](#结构化比赛)
        * [2019年厦门国际银行数创金融杯](#2019年厦门国际银行数创金融杯)
        * [安泰杯-跨境电商智能算法大赛](#安泰杯-跨境电商智能算法大赛)
        * [CCF-BDCI-乘用车销量预测](#CCF-BDCI-乘用车销量预测)
        * [CCF-离散制造过程中典型工件的质量符合率预测](#CCF-离散制造过程中典型工件的质量符合率预测)
        * [2019年DCIC-消费者人群画像-信用智能评分](#2019年DCIC-消费者人群画像-信用智能评分)
        * [2017腾讯广告算法大赛](#2017腾讯广告算法大赛)
        * [2018腾讯广告算法大赛](#2018腾讯广告算法大赛)
        * [2019腾讯广告算法大赛](#2019腾讯广告算法大赛)
        * [2019DCIC-混凝土泵车砼活塞故障预警](#2019DCIC-混凝土泵车砼活塞故障预警)
        * [2018中国高校计算机大赛-快手活跃用户预测](#2018中国高校计算机大赛-快手活跃用户预测)
        * [2018消费金融场景下的用户购买预测](#2018消费金融场景下的用户购买预测)
        * [2018kaggle-Home Credit Default Risk](#2018kaggle-Home-Credit-Default-Risk)
        * [2017全国社会保险大数据应用创新大赛](#2017全国社会保险大数据应用创新大赛)
        * [2019津南数字制造算法挑战赛-赛场一:原料企业工艺优化](#2019津南数字制造算法挑战赛-赛场一原料企业工艺优化)
        * [2018年甜橙金融杯大数据建模大赛-识别交易风险](#2018年甜橙金融杯大数据建模大赛-识别交易风险)
        * [2018OGeek算法挑战赛-实时搜索场景下搜索结果ctr预估](#2018OGeek算法挑战赛-实时搜索场景下搜索结果ctr预估)
        * [2018CCF-面向电信行业存量用户的智能套餐个性化匹配模型](#2018CCF-面向电信行业存量用户的智能套餐个性化匹配模型)
        * [2016CCF-大数据精准营销中搜狗用户画像挖掘](#2016CCF-大数据精准营销中搜狗用户画像挖掘)
        * [2019JDATA-用户对品类下店铺的购买预测](#JD1)
    * [CV](#cv)
    * [NLP](#nlp)
        * [2020腾讯广告算法大赛](#2020腾讯广告算法大赛)
* [Tips](#tips)
# 比赛
## 结构化比赛
### 2019年厦门国际银行数创金融杯
**赛题链接**  
https://m.dcjingsai.com/cmptDetail.html?id=319  
**赛题任务**  
信用风险是金融监管机构重点关注的风险，关乎金融系统运行的稳定。在实际业务开展和模型构建过程中，面临着高维稀疏特征以及样本不平衡等各种问题，如何应用机器学习等数据挖掘方法提高信用风险的评估和预测能力，是各家金融机构积极探索的方向。本次竞赛提供实际业务场景中的信贷数据作为建模的对象，希望能借此展现各参赛选手数据挖掘的实战能力。本次赛题给出20个非匿名的业务字段以及84个匿名字段，在极不平衡的样本数据中，预测客户是否会出现信用违约行为。  
**赛题难点**  
①数据的高维稀疏性导致数据的可利用性降低，给模型学习能力的提升带来了困难；②数据的极度不平衡，导致模型极其容易出现过拟合问题；③匿名字段的处理：如何理解并使用匿名字段中潜在的业务意义；④新旧数据探索：如何衡量新旧数据的差异，如何把握特征的新旧差异，以及如何构建合适的验证策略;  
**方案参考**  
[冠军方案](https://zhuanlan.zhihu.com/p/149985365)  
[第二名方案](https://github.com/Tersaiz/2019-XiaMenBank-Data-Modeling-Competition)  
[第六名方案](https://github.com/yanqiangmiffy/Data-Finance-Cup)  
[其他](https://github.com/shenxiangzhuang/Bank-Competition)  
### 安泰杯-跨境电商智能算法大赛
**赛题链接**  
https://tianchi.aliyun.com/competition/entrance/231718/information  
**赛题任务**  
今天许多中国互联网公司都在响应习近平主席一带一路的号召积极开拓海外市场。在我们开拓海外市场时往往会遭遇到用户习惯与国内不同造成国内的优秀策略难以在海外奏效等问题。即使成功开拓了某一国的市场，当需要进一步向更多国家扩张时，也会遇到不同国家的用户心智不统一的问题。  
AliExpress是中国最大出口B2C电商平台，2010 年平台成立至今已过 8 年，高速发展，日趋成熟。我们覆盖全球 230 个国家和地区，支持世界 18 种语言站点，22 个行业囊括日常消费类目，商品备受海外消费者欢迎；海外装机量超过 6亿，入围全球应用榜单 TOP 10；目前的主要交易市场为俄、美、西、巴、法等国。  
对于AliExpress来说，目前某些国家的用户群体比较成熟。这些成熟国家的用户在AliExpress尽享买买买之乐的同时，为我们沉淀了大量的该国用户的行为数据。这些沉淀下来的用户数据被我们挖掘利用后形成我们的推荐算法，用来更好的服务于该国用户。  
但是还有一些待成熟国家的用户在AliExpress上的行为比较稀疏，对于这些国家用户的推荐算法如果单纯不加区分的使用全网用户的行为数据，可能会忽略这些国家用户的一些独特的心智；而如果只使用这些国家的用户的行为数据，由于数据过于稀疏，不具备统计意义，会难以训练出正确的模型。于是怎样利用已成熟国家的稠密用户数据和待成熟国家的稀疏用户数据训练出对于待成熟国家用户的正确模型对于我们更好的服务待成熟国家用户具有非常重要的意义。  
本次比赛给出若干日内来自成熟国家的部分用户的行为数据，以及来自待成熟国家的A部分用户的行为数据，以及待成熟国家的B部分用户的行为数据去除每个用户的最后一条购买数据，让参赛人预测B部分用户的最后一条行为数据。  
**赛题难点**  
怎样利用已成熟国家A的稠密用户数据和待成熟国家B的稀疏用户数据，训练出的正确模型对于国家B的用户有很大价值。  
**方案参考**  
[冠军方案](https://github.com/RainFung/Tianchi-AntaiCup-International-E-commerce-Artificial-Intelligence-Challenge)  
[itemCF+SVD](https://tianchi.aliyun.com/notebook-ai/detail?spm=5176.12586969.1002.12.7404238aWqSGWk&postId=65062)  
### CCF-BDCI-乘用车销量预测
**赛题链接**  
https://www.datafountain.cn/competitions/352  
**赛题任务**  
近几年来，国内汽车市场由增量市场逐步进入存量市场阶段，2018年整体市场销量首次同比下降。 在市场整体趋势逐步改变的环境下，消费者购车决策的过程也正在从线下向线上转移，我们希望能在销量数据自身趋势规律的基础上，找到消费者在互联网上的行为数据与销量之间的相关性，为汽车行业带来更准确有效的销量趋势预测。  
本赛题需要参赛队伍根据给出的60款车型在22个细分市场（省份）的销量连续24个月（从2016年1月至2018年12月）的销量数据，建立销量预测模型；基于该模型预测同一款车型和相同细分市场在接下来一个季度连续4个月份的销量；除销量数据外，还提供同时期的用户互联网行为统计数据，包括：各细分市场每个车型名称的互联网搜索量数据；主流汽车垂直媒体用户活跃数据等。参赛队伍可同时使用这些非销量数据用于建模。  
**赛题难点**  
 时序特征处理，构造方法多种多样  
**方案参考**  
[鱼佬baseline](https://zhuanlan.zhihu.com/p/93602770)  
[冠军方案](https://zhuanlan.zhihu.com/p/98926322)  
[第三名方案](https://zhuanlan.zhihu.com/p/98611487)  
### CCF-离散制造过程中典型工件的质量符合率预测
**赛题链接**  
https://www.datafountain.cn/competitions/351/  
**赛题任务**  
在高端制造领域，随着数字化转型的深入推进，越来越多的数据可以被用来分析和学习，进而实现制造过程中重要决策和控制环节的智能化，例如生产质量管理。由于在实际生产中，同一组工艺参数设定下生产的工件会出现多种质检结果，所以我们针对各组工艺参数定义其质检标准符合率，即为该组工艺参数生产的工件的质检结果分别符合优、良、合格与不合格四类指标的比率。相比预测各个工件的质检结果，预测该质检标准符合率会更具有实际意义。  
**赛题难点**  
匿名数据怎么做特征，预测重要特征的缺失值  
**方案参考**  
[冠军方案](https://github.com/CcIsHandsome/-TOP1-) 可以学习的点：用预测的方法补充重要特征缺失值？同时加上重要特征的stacking（巨tm过拟合）。以及标准的特征增加方法（nunique、std之类的）  
### 2019年DCIC-消费者人群画像-信用智能评分
**赛题链接**  
https://www.datafountain.cn/competitions/337  
**赛题任务**  
随着社会信用体系建设的深入推进, 社会信用标准建设飞速发展，相关的标准相继发布，包括信用服务标准、信用数据釆集和服务标准、信用修复标准、城市信用标准、行业信用标准等在内的多层次标准体系亟待出台，社会信用标准体系有望快速推进。社会各行业信用服务机构深度参与广告、政务、涉金融、共享单车、旅游、重大投资项目、教育、环保以及社会信用体系建设，社会信用体系建设是个系统工程，通讯运营商作为社会企业中不可缺少的部分同样需要打造企业信用评分体系，助推整个社会的信用体系升级。同时国家也鼓励推进第三方信用服务机构与政府数据交换，以增强政府公共信用信息中心的核心竞争力。  
传统的信用评分主要以客户消费能力等少数的维度来衡量，难以全面、客观、及时的反映客户的信用。中国移动作为通信运营商拥有海量、广泛、高质量、高时效的数据，如何基于丰富的大数据对客户进行智能评分是中国移动和新大陆科技集团目前攻关的难题。运营商信用智能评分体系的建立不仅能完善社会信用体系，同时中国移动内部也提供了丰富的应用价值，包括全球通客户服务品质的提升、客户欠费额度的信用控制、根据信用等级享受各类业务优惠等，希望通过本次建模比赛，征集优秀的模型体系，准确评估用户信用分值。  
**赛题难点**  
关于此次赛题，数据上来说可挖掘潜力并不是那么大，因此各个队伍能挖掘到的特征基本都很相似。于是只能拼数据，拼模型，拼骚操作了。  
**方案参考**  
[冠军方案1](https://mp.weixin.qq.com/s?__biz=MzIyNjM2MzQyNg==&mid=2247484826&idx=1&sn=5e008478c274143d0716ce7184804356&chksm=e870d4d7df075dc16442660d866bcfb903b01010282dfb9fd41b4159609cc2b78a58f82db9ac&mpshare=1&scene=24&srcid=#rd)  
[冠军方案2](https://blog.csdn.net/weixin_35770067/article/details/94336044) 学习的点：分段式的stacking（纵向，训练的时候分层的用不同的损失函数）  
[冠军答辩](https://mp.weixin.qq.com/s/5bTYwflXeC0K39z0XQwhgA)  
[冠军开源](https://github.com/AnTi-anti/Credit-Intelligence-Assessment)  
[top2开源](https://github.com/C-rawler/DCIC-2019-Credit-intelligence-score-2th-Place) 学习的点：看下多个模型stacking的代码  
[top5方案](https://zhuanlan.zhihu.com/p/62291067)  
[top10开源](https://github.com/xy0210/DCIC-2019-China-Mobile)  
### 2017腾讯广告算法大赛
**赛题链接**  
已失效  
**赛题任务**  
第一届腾讯社交广告高校算法大赛以“移动App广告转化率预估“为主题，首次开放腾讯在社交和数字广告领域的“实战类”数据，以高度模拟真实业务的赛题方式呈现，并直指数字广告中的核心关键问题：转化预估，面向高校学生征集最智慧的算法解决方案，引领广告生态业界的核心技术方向。  
**赛题难点**  
数据线上线下分布不一致：1、某些app和用户的记录比较少；2、数据的时效性要求较高。这对于特征工程会是一个比较大的要求，在比赛中有许多的特征会使得线上的成绩下降，比如各种差分的特征。   
**方案参考**  
[top10方案](https://zhuanlan.zhihu.com/p/95418813)  
[top14开源](https://github.com/freelzy/Tencent_Social_Ads)  
[top20开源](https://github.com/shenweichen/Tencent_Social_Ads2017_Mobile_App_pCVR)  
[top23开源](https://github.com/BladeCoda/Tencent2017_Final_Coda_Allegro)  
### 2018腾讯广告算法大赛
**赛题链接**  
已失效  
**赛题任务**  
本次算法大赛的题目源于腾讯社交广告业务中的一个真实的广告产品——相似人群拓展（Lookalike）。该产品的目的是基于广告主提供的目标人群，从海量的人群中找出和目标人群相似的其他人群。在实际广告业务应用场景中，Lookalike 能基于广告主已有的消费者，找出和已有消费者相似的潜在消费者，以此有效帮助广告主挖掘新客、拓展业务。目前，腾讯社交广告 Lookalike 相似人群拓展产品以广告主提供的第一方数据及广告投放效果数据（即后文提到的种子包人群）为基础，结合腾讯丰富的数据标签能力，透过深度神经网络挖掘，实现了可在线实时为多个广告主同时拓展具有相似特征的高质潜客的能力。    
**赛题难点**   
**方案参考**  
[top3开源](https://github.com/DiligentPanda/Tencent_Ads_Algo_2018)  
[top6方案](https://zhuanlan.zhihu.com/p/38443751)  
[top7开源](https://github.com/guoday/Tencent2018_Lookalike_Rank7th)  
[top9方案+开源](https://zhuanlan.zhihu.com/p/38499275)  
[top10开源](https://github.com/keyunluo/Tencent2018_Lookalike_Rank10th)  
[top11方案+开源](https://zhuanlan.zhihu.com/p/38034501)  

### 2019腾讯广告算法大赛
**赛题链接**  
已失效  
**赛题任务**  
第一个子任务就是用广告的定向时段等设置来用预估未来的触发请求数和 曝光分数分布情况，它也可拆分两个更小的目标，一是用定向时段素材尺寸这 些来召回历史匹配的请求数据，这部分主要是业务规则的匹配，瓶颈主要在于 运行的效率和复杂业务规则的适配及可扩展问题（实际业务中的定向维度远比 初赛中使用的定向维度复杂的多，不同广告位的业务匹配逻辑也更加复杂）， 二是用历史请求数据预估未来的请求数据，这更像是一个时间序列建模问题， 即用历史的变化趋势预估未来。  
第二个子任务是预估广告的相对竞争水平以及基于此的胜出比例，它的前 提是触发的请求和竞价队列已知（这是第一个子任务的预估结果）。此时，我们如果使用当天已知的触发请求和竞价队列去抽取特征建模预估当天的曝光 （即使用所谓”穿越“特征），这里得到的评估结果必然是高估的（和实际业务 效果对比），因为这实际上是基于第一个子任务预估百分百准确的前提。 但这 不妨碍基于此去做特征构建和模型算法的调研选择（基于同样假设的评估结果 横向比较）。 而经调研优选得到的最优的特征和模型，同样可以结合第一个子 任务的结果重新进行评估（相同的特征计算方式和模型从未来数据迁移到历史 数据），最终得到真实的模型整体预估效果。 综上，大家已经可以看出，初赛是完整的业务问题抽象， 而复赛数据其实 就是第二个子任务的抽象。  
**赛题难点**  
特征缺失：广告中的图像、宣传文字等许多用户直观感受到的特征未提供；新广告冷启动问题，历史统计特征不存在。  
**方案参考**  
[冠军方案](https://zhuanlan.zhihu.com/p/73062485)学习的点：处理数据泄露问题  
[top5方案](https://mp.weixin.qq.com/s/j5YICHrkHLDm7OldPFPOjw)  
### 2019DCIC-混凝土泵车砼活塞故障预警
**赛题链接**  
https://www.datafountain.cn/competitions/336  
**赛题任务**  
本赛题由中科云谷科技有限公司提供某类混凝土泵车砼活塞故障有关的数据，包括工作时间、发动机转速、油温、压力等多类工况数据，以及对应情况下，在未来完成给定工作量（混凝土泵送方量）的过程中，活塞是否故障的标识信息。希望参赛者利用大数据分析、机器学习、深度学习等方法，提取合适的特征、建立合适的故障预测模型，再根据测试数据预测该活塞在未来给定工作量内（泵送方量），是否会发生故障。  
**赛题难点**  
工业互联网领域与互联网和金融领域的有所不同，一般而言，工业互联网领域，当设备发生故障的时候才会产生一个黑样本，而在互联网领域，也许是一个用户的点击行为就是一样样本。普遍而言，工业上数据量不足，以及正负样本失衡市一个天然存在的问题。  
**方案参考**  
[冠军方案](https://zhuanlan.zhihu.com/p/66324559)  
[冠军开源](https://github.com/pinlank/DCIC_Failure-Prediction-of-Concrete-Piston-for-Concrete-Pump-Vehicles_1st/tree/master/code)  
### 2018中国高校计算机大赛-快手活跃用户预测
**赛题链接**  
https://www.kesci.com/home/competition/5ab8c36a8643e33f5138cba4/content/0  
**赛题任务**  
本次大赛基于脱敏和采样后的数据信息，预测未来一段时间活跃的用户。参赛队伍需要设计相应的算法进行数据分析和处理，比赛结果按照指定的评价指标使用在线评测数据进行评测和排名，得分最优者获胜。  
**赛题难点**  
**方案参考**  
[冠军方案](https://zhuanlan.zhihu.com/p/42622063)  
[冠军开源](https://github.com/drop-out/RNN-Active-User-Forecast)  
[top4开源](https://github.com/chantcalf/2018-Rank4-)  
[top6开源](https://github.com/yuxiaowww/2018-China-University-Computer-Contest)  
[top13开源](https://github.com/luoda888/2018-KUAISHOU-TSINGHUA-Top13-Solutions)  
[top15开源](https://github.com/sunwantong/Kuaishou-Active-User)  
[top20开源](https://github.com/bigzhao/Kuaishou_2018_rank20th)  
### 2018消费金融场景下的用户购买预测
**赛题链接**  
https://www.datafountain.cn/competitions/287  
**赛题任务**  
利用招商银行客户的个人属性、信用卡消费数据，以及部分客户在掌上生活APP上的一个月的操作行为日志，设计合理的特征工程与模型算法方案，预测客户在未来一周内（4月1日-7日），是否会购买掌上生活APP上的优惠券（包括饭票、影票等）。考虑到客户隐私，客户的个人属性数据与信用卡消费数据，采用脱敏并标准化处理为V1,V2,…,V30数值型属性。客户在APP上的行为日志，一些字段也进行了相应加密。  
**赛题难点**  
**方案参考**  
[冠军开源](https://github.com/sunwantong/China-Merchants-Bank-credit-card-Cente-User-purchase-forecast)
### 2018kaggle-Home Credit Default Risk
**赛题链接**  
https://www.kaggle.com/c/home-credit-default-risk/overview  
**赛题任务**  
Many people struggle to get loans due to insufficient or non-existent credit histories. And, unfortunately, this population is often taken advantage of by untrustworthy lenders.  
Home Credit strives to broaden financial inclusion for the unbanked population by providing a positive and safe borrowing experience. In order to make sure this underserved population has a positive loan experience, Home Credit makes use of a variety of alternative data--including telco and transactional information--to predict their clients' repayment abilities.  
While Home Credit is currently using various statistical and machine learning methods to make these predictions, they're challenging Kagglers to help them unlock the full potential of their data. Doing so will ensure that clients capable of repayment are not rejected and that loans are given with a principal, maturity, and repayment calendar that will empower their clients to be successful.  
**赛题难点**  
**方案参考**  
[top2开源](https://github.com/KazukiOnodera/Home-Credit-Default-Risk)  
[top4开源](https://github.com/Cirice/4th-place-Home-Credit-Default-Risk)  
[top8开源](https://github.com/CortexFoundation/Home-Credit-Default-Risk-rank8)  
[top10开源](https://github.com/dylanxia2017/Kaggle-Home-Credit-Default-Risk)  
[top17开源](https://github.com/NoxMoon/home-credit-default-risk)  
[baseline开源](https://github.com/minerva-ml/open-solution-home-credit)  
### 2017全国社会保险大数据应用创新大赛
**赛题链接**  
https://tianchi.aliyun.com/competition/entrance/231607/information  
**赛题任务**  
“精准社保”的赛题为“基本医疗保险医疗服务智能监控”，由参赛队完成数据算法模型的开发设计，实现对各类医疗保险基金欺诈违规行为的准确识别，以进一步丰富现行医保智能监控的医保规则和医学规则，提高医保智能监控的针对性和有效性。违规行为举例如下：  
（1）为了获得不当利益，部分人员从各种途径收集医疗保险参保人员的社保卡，通过社保卡到医院进行虚假诊疗，套取医保基金。  
（2）在门诊特殊疾病的诊疗中，部分人员通过编造病历、诊疗过程，套取医保基金。  
在本次比赛中，将上述两种违规人员统称为涉嫌造假人员。选手需要基于给定的训练集数据得到模型，然后使用模型判定测试集中的人员是否为涉嫌造假人员。  
**赛题难点**  
**方案参考**  
https://tianchi.aliyun.com/competition/entrance/231607/forum
### 2019津南数字制造算法挑战赛-赛场一:原料企业工艺优化
**赛题链接**  
https://tianchi.aliyun.com/competition/entrance/231695/introduction  
**赛题任务**  
异烟酸用作医药中间体，主要用于制抗结核病药物异烟肼，也用于合成酰胺、酰肼、酯类等衍生物。烟酰胺生产过程包含水解脱色、结晶甩滤等过程。每个步骤会受到温度、时间、压强等各方面因素的影响，造成异烟酸收率的不稳定。为保证产品质量和提高生产效率，需要调整和优化生产过程中的参数。然而，根据传统经验的人工调整工艺参数费时费力。近年来，人工智能在工艺参数优化以及视频检测等领域取得了突飞猛进的成果。AI技术的发展有望助力原料药制造企业实现工艺生产革新，规范生产操作过程，从而达到提高产品的收率的目标。  
本次大赛要求选手以异烟酸生产过程中的各参数，包括各主要步骤的时间、温度、压强等参数为基础，设计精确智能的优秀算法，提升异烟酸的收率。  
**方案参考**  
[baseline开源](https://tianchi.aliyun.com/notebook-ai/detail?spm=5176.12586969.1002.3.54587ffcBbKm9R&postId=41822) 交叉特征怎么做模板  
[top1开源](https://tianchi.aliyun.com/notebook-ai/detail?spm=5176.12586969.1002.6.54587b9dKsySi9&postId=54381) 交叉特征怎么做模板  
[top2方案](https://tianchi.aliyun.com/notebook-ai/detail?spm=5176.12586969.1002.27.54587b9dKsySi9&postId=54530)  
[top2开源](https://tianchi.aliyun.com/notebook-ai/detail?spm=5176.12586969.1002.9.54587b9dKsySi9&postId=54342) 根据训练模型metric不同来区分模型？  
[top3开源](https://tianchi.aliyun.com/notebook-ai/detail?spm=5176.12586969.1002.3.54587b9dKsySi9&postId=54439)  
[top6开源](https://github.com/JonneryR/2019.1-TianChi-Jinnan)  
[top17开源](https://github.com/taoyafan/jinnan)  
**赛题难点**  
* 变量脱敏，特征不好构建；  
* 数据量整体较小，特征扩维太大容易炸，模型的可操作性不大，还是重在特征的扩维以及特征选择的方法；  
* 人工标注的错误数据相对较多；  
* 实验中的偶然因素比较多，如数据中存在较多批次的样本，所有工序步骤包括时间都相同，得到的异烟酸的收率是不同的，如何学习到这一部分或者说如何增强模型的稳定性；  
### 2018年甜橙金融杯大数据建模大赛-识别交易风险
**赛题链接**  
https://js.dclab.run/v2/cmptDetail.html?id=265  
**赛题任务**  
随着互联网+这一概念的不断发展，电商、出行、外卖等行业近些年也持续发展壮大，越来越多的商家进入这一市场。为了在激烈的竞争中拉取新用户，培养用户的消费习惯，各种类型的营销活动和补贴活动也是层出不穷。在为正常用户带来福利的同时，也催生了一批专注于营销活动的“羊毛党”。目前，羊毛党的行为越发专业化，团伙化和地域化，同套利黑产团伙的斗争，是一场永无止境的攻防战。机器学习模型是风控系统中实时识别和对抗黑产攻击的有效手段。面对黑产攻击手段快速多变，黑样本数据标签缺失等问题，目前除了LR,RF等耳熟能详的机器学习模型，基于RNN的深度学习模型，无监督学习模型等技术也被应用到同黑产的对抗中。通过训练学习用户在消费过程中的关联操作、交易详单信息，来识别交易风险。  
**赛题难点**  
**方案参考**  
[top6开源](https://github.com/BirderEric/Tiancheng)  
[top9开源](https://github.com/PandasCute/2018-ORANGE-FINANCIAL-BIG-DATA-top9)  
[top10方案](https://zhuanlan.zhihu.com/p/66412427)  
[baseline开源](https://github.com/lcxanhui/2018-orange-finance-baseline)  
### 2018OGeek算法挑战赛-实时搜索场景下搜索结果ctr预估
**赛题链接**  
https://tianchi.aliyun.com/competition/entrance/231688/introduction  
**赛题任务**  
在搜索业务下有一个场景叫实时搜索（Instance Search）,就是在用户不断输入过程中，实时返回查询结果。此次赛题来自OPPO手机搜索排序优化的一个子场景，并做了相应的简化，意在解决query-title语义匹配的问题。简化后，本次题目内容主要为一个实时搜索场景下query-title的ctr预估问题。基于百万最新真实用户搜索数据的实时搜索场景下搜索结果ctr预估。给定用户输入prefix（用户输入，查询词前缀）以及文章标题、文章类型等数据，预测用户是否点击。文章资源类别非全网资源，属部分垂直领域内容。  
**赛题难点**  
**方案参考**  
[冠军方案](https://tianchi.aliyun.com/notebook-ai/detail?spm=5176.12586969.1002.3.651d262af1mkfD&postId=50763)  
[top2方案](https://zhuanlan.zhihu.com/p/51422621)  
[top2开源](https://github.com/bettenW/TIANCHI_OGeek_Rank2)  
[top3方案1](https://tianchi.aliyun.com/notebook-ai/detail?spm=5176.12586969.1002.15.651d4cd6uJjKS3&postId=50016)  
[top3方案2](https://tianchi.aliyun.com/forum/postDetail?spm=5176.12586969.1002.12.651d4cd6uJjKS3&postId=50184)  
[top3方案3](https://tianchi.aliyun.com/notebook-ai/detail?spm=5176.12586969.1002.9.651d4cd6uJjKS3&postId=50285)  
[优胜奖方案](https://tianchi.aliyun.com/forum/postDetail?spm=5176.12586969.1002.3.651d4cd6uJjKS3&postId=50456)  
[baseline开源](https://zhuanlan.zhihu.com/p/46482521) 做ctr时候把特征做成click/count的形式  
### 2018CCF-面向电信行业存量用户的智能套餐个性化匹配模型
**赛题链接**  
https://www.datafountain.cn/competitions/311  
**赛题任务**  
电信产业作为国家基础产业之一，覆盖广、用户多，在支撑国家建设和发展方面尤为重要。随着互联网技术的快速发展和普及，用户消耗的流量也成井喷态势，近年来，电信运营商推出大量的电信套餐用以满足用户的差异化需求，面对种类繁多的套餐，如何选择最合适的一款对于运营商和用户来说都至关重要，尤其是在电信市场增速放缓，存量用户争夺愈发激烈的大背景下。针对电信套餐的个性化推荐问题，通过数据挖掘技术构建了基于用户消费行为的电信套餐个性化推荐模型，根据用户业务行为画像结果，分析出用户消费习惯及偏好，匹配用户最合适的套餐，提升用户感知，带动用户需求，从而达到用户价值提升的目标。  
套餐的个性化推荐，能够在信息过载的环境中帮助用户发现合适套餐，也能将合适套餐信息推送给用户。解决的问题有两个：信息过载问题和用户无目的搜索问题。各种套餐满足了用户有明确目的时的主动查找需求，而个性化推荐能够在用户没有明确目的的时候帮助他们发现感兴趣的新内容。  
此题利用已有的用户属性(如个人基本信息、用户画像信息等)、终端属性(如终端品牌等)、业务属性、消费习惯及偏好匹配用户最合适的套餐，对用户进行推送，完成后续个性化服务。  
**赛题难点**  
**方案参考**  
[冠军开源](https://github.com/PPshrimpGo/BDCI2018-ChinauUicom-1st-solution)  
[top2开源](https://github.com/PandasCute/2018-CCF-BDCI-China-Unicom-Research-Institute-top2)  
[top4开源](https://github.com/jinchenyu/2018_CCF_BDCI_ChinaUicom_rank4_solution)  
[top6开源](https://github.com/ZengHaihong/2018_CCF_BDCI_ChinaUnicom_Package_Match_Rank6)  
### 2016CCF-大数据精准营销中搜狗用户画像挖掘
**赛题链接**  
https://www.datafountain.cn/competitions/239  
**赛题任务**  
"物以类聚，人以群分"这句古语不仅揭示了物与人的自组织趋向，更隐含了“聚类”和“人群”之间的内在联系。在现代数字广告投放系统中，以物拟人，以物窥人，才是比任何大数据都要更大的前提。如何把广告投放给需要的人，是大数据在精准营销中最核心的问题，如何越来越精确的挖掘人群属性，也一直是技术上的天花板。对于企业主来说，了解自身产品的受众有助于进行产品定位，并设计营销解决方案。本题目以精准广告中一个具体问题为例，希望发掘到数据挖掘的优秀人才。  
本题目提供用户历史一个月的查询词与用户的人口属性标签（包括性别、年龄、学历）做为训练数据，要求参赛人员通过机器学习、数据挖掘技术构建分类算法来对新增用户的人口属性进行判定。  
**赛题难点**  
**方案参考**  
[冠军开源](https://github.com/hengchao0248/ccf2016_sougou)  
[top3开源](https://github.com/AbnerYang/2016CCF-SouGou)  
[top5开源](https://github.com/dhdsjy/2016_CCFsougou)   
### <span id='JD1'>2019JDATA-用户对品类下店铺的购买预测</span>
**赛题链接**  
https://jdata.jd.com/html/detail.html?id=8  
**赛题任务**  
京东零售集团坚持“以信赖为基础、以客户为中心的价值创造”这一经营理念，在不同的消费场景和连接终端上，在正确的时间、正确的地点为3亿多活跃用户提供最适合的产品和服务。目前，京东零售集团第三方平台签约商家超过21万个，实现了全品类覆盖，为维持商家生态繁荣、多样和有序，全面满足消费者一站式购物需求，需要对用户购买行为进行更精准地分析和预测。基于此，本赛题提供来自用户、商家、商品等多方面数据信息，包括商家和商品自身的内容信息、评论信息以及用户与之丰富的互动行为。参赛队伍需要通过数据挖掘技术和机器学习算法，构建用户购买商家中相关品类的预测模型，输出用户和店铺、品类的匹配结果，为精准营销提供高质量的目标群体。同时，希望参赛队伍通过本次比赛，挖掘数据背后潜在的意义，为电商生态平台的商家、用户提供多方共赢的智能解决方案。  
**赛题难点**  
本次比赛分为A，B榜，但是两个榜都是采用同一套数据集。通过EDA分析可知，数据集存在很多噪声，例如加购数据存在大量缺失，浏览数据也存在两天的缺失，2月份数据受春节影响流量异常。如何建模尽可能达到最大的预测准确性。我们将本次比赛的难点归纳为如下几点。   
（1）本次比赛的label需要自己构建, 如何建模使我们能在给定的数据集上达到尽可能大的预测准确性，是本次比赛考虑的关键点之一。   
（2）对于训练集不同时间段的选取对最终结果都很造成一定的影响，如何选用时间段，让训练集分布和测试集分布类似，也是本次比赛的关键之一。   
（3）如何刻画每个时间段的时序特点，使其能够捕捉数据集的趋势性，周期性，循环性。   
（4）给来的数据集存在太多影响因素，比如加购数据缺失，浏览数据部分缺失，春节流量异常，节后效应等，所以该如何选取训练集&保证模型稳定的情况。   
（5）模型预测出来是概率文件，如何确定划分正负样本的概率阈值，如何确定最优的提交结果数，也是本次比赛不可忽略的关键点之一。   
**方案参考**  
[冠军开源](https://github.com/jackychancjcjcj/Competition_notebook/edit/master/README.md)  
[top2开源](https://github.com/anzhizh/2019-taida-jdata-top3)  
[top3开源](https://github.com/WeavingWong/JDATA_2019-Cate_Shop_predict)  

## CV
## NLP
### 2020腾讯广告算法大赛
**赛题链接**  
https://algo.qq.com/  
**赛题任务**  
本届算法大赛的题目来源于一个重要且有趣的问题。众所周知，像用户年龄和性别这样的人口统计学特征是各类推荐系统的重要输入特征，其中自然也包括了广告平台。这背后的假设是，用户对广告的偏好会随着其年龄和性别的不同而有所区别。许多行业的实践者已经多次验证了这一假设。然而，大多数验证所采用的方式都是以人口统计学属性作为输入来产生推荐结果，然后离线或者在线地对比用与不用这些输入的情况下的推荐性能。本届大赛的题目尝试从另一个方向来验证这个假设，即以用户在广告系统中的交互行为作为输入来预测用户的人口统计学属性。我们认为这一赛题的“逆向思考”本身具有其研究价值和趣味性，此外也有实用价值和挑战性。例如，对于缺乏用户信息的实践者来说，基于其自有系统的数据来推断用户属性，可以帮助其在更广的人群上实现智能定向或者受众保护。与此同时，参赛者需要综合运用机器学习领域的各种技术来实现更准确的预估。  
**赛题难点**  

**方案参考**  
[冠军方案](https://zhuanlan.zhihu.com/p/166710532)  
[亚军方案](https://zhuanlan.zhihu.com/p/185045764)  
[top5方案](https://zhuanlan.zhihu.com/p/170603281)  
[top11方案](https://github.com/llllllyu/Tencent2020_Rank11)   
[top12方案](https://github.com/LogicJake/Tencent_Ads_Algo_2020_TOP12)









# Tips
## 特征过多怎么办？  
### 1. 重要性排序，保留前面的
### 2. 看训练集和测试集分布，删除分布不一样的  
```python
# 重要！！！观察筛选的特征，在train和test上的分布差异，并删除分布差异大的特征
for column in base_corr_col:

    plt.hist(df_x_train[column], color='g')
    plt.hist(df_x_test[column], color='r')
    plt.xlabel(column)
    plt.legend(['train', 'test'])
    plt.show()
    
    sns.kdeplot(df_x_train[column], shade=True, color='g')
    sns.kdeplot(df_x_test[column], shade=True, color='r')
    plt.xlabel(column)
    plt.legend(['train', 'test'])
    plt.show()
    print(column)
```
### 3. 也可以通过相关性筛选（相关性超过阈值就不要）  
```python
# 设置相关性系数的阈值，并据此进行特征初步删减
size_base_col = []
corr_thresh1 = 0.1
corr_thresh2 = -0.16
# 分别对3个尺寸，分别进行筛选
for i,size in enumerate(['size1', 'size2', 'size3']):
    temp = []
    for c in corr_col:
        if (df_corrmat.loc[size, c]>=corr_thresh1) or (df_corrmat.loc[size, c]<=corr_thresh2):
            temp.append(c)    
    size_base_col.append(temp)
```
## 特征可以怎么做？
### 交叉特征
```python
//定义离散型特征和连续型特征
col_cat = ['subGrade', 'grade', 'employmentLength', 'term', 'homeOwnership', 'postCode', 'regionCode','employmentTitle','title']
col_num = ['dti', 'revolBal','revolUtil', 'ficoRangeHigh', 'interestRate', 'loanAmnt', 'installment', 'annualIncome', 'n14',
             'n2', 'n6', 'n9', 'n5', 'n8']
             
# 定义离散型特征和连续型特征交叉特征统计函数
def cross_cat_num(df, num_col, cat_col):
    for f1 in tqdm(cat_col):
        g = df.groupby(f1, as_index=False)
        for f2 in tqdm(num_col):
            feat = g[f2].agg({
                '{}_{}_max'.format(f1, f2): 'max', '{}_{}_min'.format(f1, f2): 'min',
                '{}_{}_median'.format(f1, f2): 'median',
            })
            df = df.merge(feat, on=f1, how='left')
    return (df)
    
data = cross_cat_num(data, col_num, col_cat)  # 一阶交叉
print('一阶交叉特征处理后：', data.shape)

# 类别特征之间的二阶交叉
def cross_qua_cat_num(df):
    for f_pair in tqdm([
        ['subGrade', 'regionCode'], ['grade', 'regionCode'], ['subGrade', 'postCode'], ['grade', 'postCode'], ['employmentTitle','title'],
        ['regionCode','title'], ['postCode','title'], ['homeOwnership','title'], ['homeOwnership','employmentTitle'],['homeOwnership','employmentLength'],
        ['regionCode', 'postCode']
    ]):
        ### 共现次数
        df['_'.join(f_pair) + '_count'] = df.groupby(f_pair)['id'].transform('count')
        ### n unique、熵
        df = df.merge(df.groupby(f_pair[0], as_index=False)[f_pair[1]].agg({
            '{}_{}_nunique'.format(f_pair[0], f_pair[1]): 'nunique',
            '{}_{}_ent'.format(f_pair[0], f_pair[1]): lambda x: entropy(x.value_counts() / x.shape[0])
        }), on=f_pair[0], how='left')
        df = df.merge(df.groupby(f_pair[1], as_index=False)[f_pair[0]].agg({
            '{}_{}_nunique'.format(f_pair[1], f_pair[0]): 'nunique',
            '{}_{}_ent'.format(f_pair[1], f_pair[0]): lambda x: entropy(x.value_counts() / x.shape[0])
        }), on=f_pair[1], how='left')
        ### 比例偏好
        df['{}_in_{}_prop'.format(f_pair[0], f_pair[1])] = df['_'.join(f_pair) + '_count'] / df[f_pair[1] + '_count']
        df['{}_in_{}_prop'.format(f_pair[1], f_pair[0])] = df['_'.join(f_pair) + '_count'] / df[f_pair[0] + '_count']
    return (df)
```
### embedding 特征
## 标准处理df的内存减少流程
```python 
def reduce_memory(data):
    start_memory = data.memory_usage().sum() / 1024**2 
    print("Memory usage of properties dataframe is :",start_memory," MB")
    NAlist = [] # Keeps track of columns that have missing values filled in. 
    
    for col in data.columns:
        if ('int' in data[col].dtype.name) or ('float' in data[col].dtype.name):  # Exclude strings
            try:
                # Print current column type
                print("******************************")
                print("Column: ",col)
                print("dtype before: ",data[col].dtype)

                # make variables for Int, max and min
                IsInt = False
                value_max = data[col].max()
                value_min = data[col].min()

                # Integer does not support NA, therefore, NA needs to be filled
                if not np.isfinite(data[col]).all(): 
                    NAlist.append(col)
                    data[col].fillna(value_min-1,inplace=True)  

                # test if column can be converted to an integer
                asint = data[col].fillna(0).astype(np.int64)
                result = (data[col] - asint)
                result = result.sum()
                if result > -0.01 and result < 0.01:
                    IsInt = True


                # Make Integer/unsigned Integer datatypes
                if IsInt:
                    if value_min >= 0:
                        if value_max < 255:
                            data[col] = data[col].astype(np.uint8)
                        elif value_max < 65535:
                            data[col] = data[col].astype(np.uint16)
                        elif value_max < 4294967295:
                            data[col] = data[col].astype(np.uint32)
                        else:
                            data[col] = data[col].astype(np.uint64)
                    else:
                        if value_min > np.iinfo(np.int8).min and value_max < np.iinfo(np.int8).max:
                            data[col] = data[col].astype(np.int8)
                        elif value_min > np.iinfo(np.int16).min and value_max < np.iinfo(np.int16).max:
                            data[col] = data[col].astype(np.int16)
                        elif value_min > np.iinfo(np.int32).min and value_max < np.iinfo(np.int32).max:
                            data[col] = data[col].astype(np.int32)
                        elif value_min > np.iinfo(np.int64).min and value_max < np.iinfo(np.int64).max:
                            data[col] = data[col].astype(np.int64)    

                # Make float datatypes 32 bit
                else:
                    data[col] = data[col].astype(np.float32)

                # Print new column type
                print("dtype after: ",data[col].dtype)
                print("******************************")
            except:
                print("dtype after: Failed")
        else:
            print("dtype remain: ",data[col].dtype)
    
    # Print final result
    print("___MEMORY USAGE AFTER COMPLETION:___")
    end_memory = data.memory_usage().sum() / 1024**2 
    print("Memory usage is: ",end_memory," MB")
    print("This is ",100*start_memory/end_memory,"% of the initial size")
    print("Missing Value list", NAlist)
    return data
 ```
