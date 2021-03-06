#3.1 博弈的扩展式表示

动态博弈的表述方式是扩展式表述——树

>应该清晰地表明参与方采取行动的次序，以及各参与方在作出每一行动的决定时所知道的信息，那么在这一要求下，博弈的战略所对应的是相机行动，即在什么情况下应选择什么行动，而不是简单的、与环境无关的行动选择。

##3.1.1 扩展式的要素

1.阶段
>动态博弈中一个博弈方的一次选择行为

2.参与人集合

>用N代表虚拟参与人“自然” 

3.参与人的行动顺序

>谁在什么时候行动；

4.参与人的行动空间

>在每次行动时，参与人有些什么选择。

5.参与人的信息集

>每次行动时，参与人知道些什么；

6.参与人的支付函数

7.外生事件（即自然选择）的概率分布

8.博弈树

>对完全信息动态博弈中的各参与方的一步又一步行动按先后次序展开的方式

##3.1.2 动态博弈的基本特点

>1.各个博弈方的选择和行为有先后之分；

>2.博弈方的选择很可能不是只有一次;

>3.不同阶段的多次行为之间有内在联系;

研究某个博弈方某个阶段的行为，或者将各个阶段的行为割裂开来研究并没有意义


##3.1.3 博弈的基本构造

1.结

>包括决策结和终点结两类,结满足传递性和非对称性。
>>决策结是参与人行动的时点
>>
>>终点结是决策人行动的终点.

>x之前所有结的集合为x的前列集P(x)
>
>x之后的所有结的集合称为x的后续集T(x)

自然假定是单结的，自然在参与人决策之后行动等价于自然在参与人之前行动但参与人不能观测到自然的行动。

2.枝
>枝是从一个决策结到它的直接后续结的连线,每一个枝代表参与人的一个行动选择。

3.信息集

>每个信息集是决策结集合的一个子集，该子集包括所有满足下列条件的决策结——
>>1.每个决策结都是同一个参与人的决策结;
>>
>>2.该参与人知道博弈进入该集合的某个决策结,但不知道自己究竟处于哪一个决策结.

4.博弈树的结与枝间的关系

>1.每一个结至多有一个其他结直接位于它的前面；
>2.没有一条路径可以使决策结与自身连接；
>3.博弈树有且仅有一个初始结。

5.构造博弈树规则
>1.一个参与人在决策前知道的事情必须出现在该参与人的决策结前;

>2.信息集必须准确的表达出来;

##3.1.4 完美信息博弈
>若博弈树的所有信息集都是单结的，则称其为完美信息博弈。

特点

>1.博弈中没有两个参与人同时行动;

>2.所有后行动者能确切的知道前行动者选择了什么行动;
>
>3.没有任何两个决策结是用虚线连起来;

注意：博弈树上是否出现连接不同决策结的虚线还取决于如何划决策结的顺序。
