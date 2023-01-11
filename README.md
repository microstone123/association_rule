![image](https://user-images.githubusercontent.com/4679522/211786814-976941c4-c3f2-41a9-bae4-f9b7012cf7fd.png)

### ARL：关联规则学习

一种基于规则的机器学习技术，用于查找数据中的模式。 在进行关联规则学习时使用先验算法。 Apriori算法根据过程开始时确定的支持度阈值计算可能的产品对，并根据每次迭代确定的支持度值进行淘汰，从而创建最终表。

在这个项目中，经过数据预处理后，获得了 Apriori 算法所需的 Invoice-Item 矩阵。 然后，使用先验算法找到经常一起出现的项目，并使用关联规则方法得到规则表。 创建规则表后，根据需要进行排序，然后进行推荐过程。

您可以从以下链接获得项目的详细说明：
[https://medium.com/@zbeyza/recommendation-systems-arl-association-rule-learning-bed1a07b5d9a](https://medium.com/@zbeyza/recommendation-systems-arl-association-rule-learning-bed1a07b5d9a)

关于数据集：
Online Retail II 数据集包含 2009 年 1 月 12 日至 2011 年 9 月 12 日期间英国注册的非商店在线零售发生的所有交易。该公司主要销售独特的全场合礼品。 公司的许多客户都是批发商。

- **Invoice**：发票编号。名义上的。为每笔交易唯一分配的 6 位整数编号。如果此代码以字母“C”开头，则表示取消。
- **StockCode**：产品（项目）代码。名义上的。唯一分配给每个不同产品的 5 位整数。
- **Description**：产品（项目）名称。名义上的。
- **Quantity**：每笔交易的每个产品（项目）的数量。数字。
- **InvoiceDate**：发票日期和时间。数字。生成交易的日期和时间。
- **UnitPrice** : 单价。数字。以英镑 (£) 为单位的产品单价。
- **CustomerID**：客户编号。名义上的。唯一分配给每个客户的 5 位整数号码。
- **Country**：国家名称。名义上的。客户所在国家/地区的名称。

### 数据地址:

[https://archive.ics.uci.edu/ml/datasets/Online+Retail+II](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II)
