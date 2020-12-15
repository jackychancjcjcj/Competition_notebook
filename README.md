# 目录
* [比赛](#比赛)
    * [结构化比赛](#结构化比赛)
        * [2019年厦门国际银行数创金融杯](#2019年厦门国际银行数创金融杯)
        * [安泰杯-跨境电商智能算法大赛](#安泰杯-跨境电商智能算法大赛)
        * [CCF-BDCI-乘用车销量预测](#CCF-BDCI-乘用车销量预测)
        * [CCF-离散制造过程中典型工件的质量符合率预测](#CCF-离散制造过程中典型工件的质量符合率预测)
    * [CV](#cv)
    * [NLP](#nlp)
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
[冠军方案](https://github.com/CcIsHandsome/-TOP1-)
## CV
## NLP
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
