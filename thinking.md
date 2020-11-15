# Thinking1	常见的规划问题都包括哪些？ #
答：
1.LP：Linear Programming 线性规划
2.ILP：Integer Linear Programming 整数线性规划
3.MIP：Mixed Integer Programming 混合整数规划

# Thinking2	常用的规划工具包都有哪些？ #
答：pulp 、ortools 。 本节课使用的是pulp

# Thinking3	RFM模型的原理是怎样的 #
RFM指标：
Recency，最近一次消费时间间隔
Frequency，消费频率，一段时间（比如1年）内的消费次数
Monetary，消费金额，一段时间（比如1年）内的消费金额

RFM模型根据这三个指标作为xyz坐标轴，划分出了8个类别：

1、重要价值用户	高	高	高
2、重要发展用户	高	低	高
3、重要保持用户	低	高	高
4、重要挽留用户	低	低	高
5、一般价值用户	高	高	低
6、一般发展用户	高	低	低
7、一般保持用户	低	高	低
8、一般挽留用户	低	低	低

并将每个指标设定一定区间，将用户的信息根据区间进行打分，然后根据评判标准和得分，将用户进行分类。
