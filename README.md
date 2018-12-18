# 甜橙金融初赛Rank5，复赛Rank14，复赛数据真的有毒......  
比赛链接：http://www.dcjingsai.com/common/cmpt/2018年甜橙金融杯大数据建模大赛_竞赛信息.html  
# 队名：摸金校尉
# 题目背景  
随着互联网+这一概念的不断发展，电商、出行、外卖等行业近些年也持续发展壮大，越来越多的商家进入这一市场。为了在激烈的竞争中拉取新用户，培养用户的消费习惯，各种类型的营销活动和补贴活动也是层出不穷。在为正常用户带来福利的同时，也催生了一批专注于营销活动的“羊毛党”。目前，羊毛党的行为越发专业化，团伙化和地域化，同套利黑产团伙的斗争，是一场永无止境的攻防战。机器学习模型是风控系统中实时识别和对抗黑产攻击的有效手段。面对黑产攻击手段快速多变，黑样本数据标签缺失等问题，目前除了LR,RF等耳熟能详的机器学习模型，基于RNN的深度学习模型，无监督学习模型等技术也被应用到同黑产的对抗中。  
# 设计目标  
通过训练学习用户在消费过程中的关联操作、交易详单信息，来识别交易风险。  
# 解决方案：  
我们队初赛复赛用的方案一样，名次上的变化嘛，，，一方面因为数据变化太大，另一方面我们自己对数据变化不敏感，所以这个排名真的是 皮。简单介绍一下我们的方案，如果非要给方案取个名字，我觉得基于信息融合和图谱规则学习的交易风险识别模型这个名称可以恰当的表达我们所做的工作。  
先给大家看个总体的思路。
## 基于信息融合和图谱规则学习的交易风险识别模型示意图：
![基于信息融合和图谱规则学习的交易风险识别模型](https://github.com/CuiNing6/2018-TianCheng/blob/master/img/1.png)

