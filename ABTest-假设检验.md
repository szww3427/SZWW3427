聊一聊ABTest的假设检验
======
  话说一个森林里有红色羽毛的鸟，你想知道到底有多少红色羽毛的鸟，于是有人告诉有10%的比例是红色羽毛的鸟，你可以接收这个10%，只要真是结果在浮动不超过1%你都认为这个人说的是有意义的。那么你该怎么去判断这个人说的对不对呢～  
  
  现在伟大的统计学给你提供了一种方法——假设检验。这个方法很简单的，教科书式的步骤如下：  
  1. 根据实际情况提出原假设和备择假设；  
  2. 根据假设的特征，选择合适的检验统计量；
  3. 根据样本观察值，计算检验统计量的观察值(obs)；
  4. 选择许容显著性水平，并根据相应的统计量的统计分布表查出相应的临界值(ctrit)；
  5. 根据检验统计量观察值的位置决定原假设取舍。
