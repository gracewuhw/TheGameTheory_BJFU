#1.1博弈论基本概念

##1.1.1代表性博弈模型

###1.囚徒困境

<table>
	<tr>
		<td colspan="2" rowspan="2" ></td>
		<td colspan="2">囚徒B</td>
	</tr>

	<tr>
		<td>坦白</td>
		<td>抵赖</td>
	</tr>

	<tr>
		<td rowspan="2">囚徒A</td>
		<td>坦白</td>
		<td>-6,-6</td>
		<td>0,-8</td>
	</tr>

	

	<tr>
		<td>抵赖</td>
		<td>-8,0</td>
		<td>-1,-1</td>	
	</tr>

</table>


* 每一个人的结局不仅取决于自身的选择,同时也取决于对手的选择

* 个人理性决策常导致集体非理性结果

---
###2智猪博弈

背景

>一大一小两头猪通过按食槽的按钮获得食物，每按一次按钮可得10个食物并且付出2个成本。

规则

>若大猪按按钮：大猪吃6个单位，小猪吃4个单位；若小猪按按钮：大猪吃9个单位，小猪吃1个单位；若一起去按：大猪吃7个单位，小猪吃3个单位；

问题

>哪头猪将会去按按钮

<table>
	<tr>
		<td colspan="2" rowspan="2" ></td>
		<td colspan="2">小猪</td>
	</tr>
	<tr>
		<td>按</td>
		<td>不按</td>
	</tr>
	<tr>
		<td rowspan="2">大猪</td>
		<td>按</td>
		<td>5,1</td>
		<td>4,4</td>
	</tr>	
	<tr>
		<td>不按</td>
		<td>7,-1</td>
		<td>0,0</td>	
	</tr>
</table>

* 多劳不多得

---
###3斗鸡博弈
>假设两只公鸡遇到一起，每只公鸡都有两个行动选择：进攻或后退。
>若鸡甲进攻，乙后退，则甲赢。双方前进，两败俱伤。

<table>
	<tr>
		<td colspan="2" rowspan="2" ></td>
		<td colspan="2">公鸡B</td>
	</tr>
	<tr>
		<td>进攻</td>
		<td>退后</td>
	</tr>
	<tr>
		<td rowspan="2">公鸡A</td>
		<td>进攻</td>
		<td>-4,-4</td>
		<td>1,-1</td>
	</tr>
	<tr>
		<td>退后</td>
		<td>-1,1</td>
		<td>-1,-1</td>	
	</tr>
</table>


* 双方都没有占优策略，存在两个稳定的状态（纳什均衡）

---
###4承诺行动
欧共体为打破波音公司的垄断，对空中客车公司进行战略性补贴（20个单位）。

>没有补贴

<table>
	<tr>
		<td colspan="2" rowspan="2" ></td>
		<td colspan="2">空中客车</td>
	</tr>
	<tr>
		<td>开发</td>
		<td>不开发</td>
	</tr>
	<tr>
		<td rowspan="2">波音</td>
		<td>开放</td>
		<td>-10,-10</td>
		<td>100,0</td>
	</tr>
	<tr>
		<td>不开发</td>
		<td>0,100</td>
		<td>0,0</td>	
	</tr>
</table>

>有补贴

<table>
	<tr>
		<td colspan="2" rowspan="2" ></td>
		<td colspan="2">空中客车</td>
	</tr>
	<tr>
		<td>开发</td>
		<td>不开发</td>
	</tr>
	<tr>
		<td rowspan="2">波音</td>
		<td>开发</td>
		<td>-10,-10</td>
		<td>100,0</td>
	</tr>
	<tr>
		<td>不开发</td>
		<td>0,120</td>
		<td>0,0</td>	
	</tr>
</table>


* 承诺行动是有成本的，承诺行动的成本越高，威胁就越是值得相信

---
