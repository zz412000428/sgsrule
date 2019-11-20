# 第二章：游戏用语

本章提要：

1、本章为游戏中用到的特定用语及其相关的操作规范。
2、技能表述是由数个用语加上无特殊含义的常规汉字构成，因此用语对于技能表述而言意义重大，只有使用规范的用语方能表达最准确、完整的牌面信息
3、部分用语带有常规操作（被代码框包围），操作规范在遵循的优先级中等价于游戏规则。
4、“<>”用来表示句子的成分，里面的文字在理解时可以在被此句子里能作为相同句子成分的描述替代。
5、请玩家基于三国杀这个背景理解用语，游戏毕竟与日常生活有所区别，若基于日常生活理解可能会导致有部分偏差。
6、身份局和其他模式均被使用到的用语将以身份局的视角来写，玩家玩其他模式时，参考该模式的基本流程也能很容易理解这些用语。
7、方便起见，在一些数学表达式中，用大家一眼就能看懂的汉字代替了它所描述的参数，虽有些不合规范，但在确保严谨的准确的前提下，能让大家理解时少拐一个弯。
8、出于完善规则和便于说明的需要，增加了部分在铲平中没有的用语或名词，并且进行了较为合理的命名

* [与牌相关的用语](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section1.md#与牌相关的用语)
    * [身份牌](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section1.md#身份牌)
    * [武将牌](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section1.md#武将牌)
    * [体力牌](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section1.md#体力牌)
    * [游戏牌](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section1.md#游戏牌)
    * [衍生牌](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section1.md#衍生牌)
    * [基本牌](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section1.md#基本牌)
    * [装备牌](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section1.md#装备牌)
    * [锦囊牌](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section1.md#锦囊牌)
    * [实体牌](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section1.md#实体牌)
    * [虚拟牌](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section1.md#虚拟牌)
* [与牌面信息相关的用语](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section2.md#与牌相关的用语)
    * [花色](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section2.md#花色)
    * [颜色](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section2.md#颜色)
    * [点数](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section2.md#点数)
    * [姓名](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section2.md#姓名)
    * [性别](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section2.md#性别)
    * [势力](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section2.md#势力)
    * [技能](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section2.md#技能)
    * [珠联璧合](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section2.md#珠联璧合)
* [与区域相关的用语](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#与区域相关的用语)
    * [区域](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#区域)
    * [牌堆](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#牌堆)
    * [弃牌堆](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#弃牌堆)
    * [武将牌堆](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#武将牌堆)
    * [处理区](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#处理区)
    * [手牌区](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#手牌区)
    * [武器区](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#武器区)
    * [防具区](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#防具区)
    * [进攻坐骑区](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#进攻坐骑区)
    * [防御坐骑区](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#防御坐骑区)
    * [特殊坐骑区](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#特殊坐骑区)
    * [宝物区](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#宝物区)
    * [装备区](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#装备区)
    * [判定区](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#判定区)
    * [角色的区域](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#角色的区域)
    * [武将牌上](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#武将牌上)
    * [武将牌旁](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#武将牌旁)
    * [仓廪](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#仓廪)
    * [府库](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#府库)
    * [维系区域](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#维系区域)
    * [废除<一个区域>](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#废除一个区域)
    * [恢复<一个区域>](https://github.com/guiling0/sgsrule/blob/master/Chapter2/Section3.md#恢复一个区域)