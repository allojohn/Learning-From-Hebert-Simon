##素材
### 希特勒是不是坏人
实证主义解释的局限

### 贝叶斯网络，
> 由于8/2的比例并非时间无关的稳定比例，或者其他什么原因（如保守起见），目前大多数贝叶斯垃圾过滤系统实际上将这个比例设为5/5，表示“无偏见”，不设先验。这就基本上将贝叶斯这个词扔掉了。但我个人觉得这并不能称为“无偏见”，如果现实就是“有偏”的，保持公平也是一种偏见，这让我忍不住想起P. Norvig讲的关于人工智能鼻祖Minsky的一则轶事：
In the days when Sussman was a novice, Minsky once came to him as he sat hacking at the PDP-6. 
"What are you doing?", asked Minsky. 
"I am training a randomly wired neural net to play Tic-Tac-Toe," Sussman replied. 
"Why is the net wired randomly?", asked Minsky. 
"I do not want it to have any preconceptions of how to play", Sussman said. 
Minsky shut his eyes. 
"Why do you close your eyes?", Sussman asked his teacher. 
"So that the room will be empty." 
At that moment, Sussman was enlightened.
根据P. Norvig的说法，Minsky是想告诉Sussman一个随机赋值的神经网络也是有模型（或偏见的），只是这很可能是一个极其复杂的模型，我们无法理解。你蒙上眼睛不代表这个屋子不存在，你不知道随机神经网络的模型是什么不代表它不存在。
但我忍不住YY了一把另一种解释：如果现实世界背后的模型本来就是“有偏”的，假装不引入“偏见”本身就是“偏见”。只不过我们所观察到的现实世界纷繁的表象往往只是一个局部有偏样本，导致我们看上去随机抽取的数据其实还是有偏的，如果我们蒙上眼睛骗自己说这就是真正随机的抽样，那么训练出来的模型肯定也是有偏的，为了补偿这种偏差我们有时候宁可扔掉从训练数据中得到的某些概率，这种方法往往导致长期来讲更靠谱（严格来说这里的术语是robust :P）的模型，尤其是在金融市场上，小聪明的人从短期趋势数据上自以为得到了靠谱的模型，把太多的赌注放在了一个建立在因在时间维度上没有随机采样而很可能有偏的数据集上得到的模型上，而真正智慧的玩家则会建议普通人最佳投资方法是无偏见地平均分配资金，避免因模型错误而导致的灾难，这一平均分配的极端形式就是——投资指数。

出处： 逃出你的肖申克（二）：仁者见仁智者见智？从视觉错觉到偏见

### 生物学基础
《认知科学揭秘》

### GEB中的解释
最终有一个稳定的层次