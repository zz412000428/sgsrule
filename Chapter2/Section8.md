# 与操作游戏牌相关的用语

## <一张牌>移至<一个区域>
触发一个移动事件的操作，移动的牌为此牌，原区域为此牌所在的区域，目标区域为此区域。

## 使用
触发一个预使用牌事件，然后触发一个使用事件的操作。

`角色不能同时使用两张或两张以上的牌。`

## 打出
触发一个打出事件的操作。

`角色不能同时打出两张或两张以上的牌。`

## <一名角色>能如手牌般使用或打出<牌A>
若其于预使用/打出牌B的流程中选择牌B对应的实体牌的范围为其牌或手牌，且有特定的数量，则所有符合其选择牌B对应的实体牌的标准（除区域的标准外）的牌A也会进入其选择牌B对应的实体牌的范围。

> 例如：角色通过发动【丈八蛇矛】来使用普【杀】，能选择一张手牌和一张“辎”作为此【杀】对应的实体牌。

> 例如：没有手牌的荀攸通过发动【奇策】来使用【无中生有】，不能选择所有“辎”作为此【无中生有】对应的实体牌，因为此【无中生有】对应的实体牌须为荀攸的所有手牌而非特定数量的手牌；有手牌且装备区里有【木牛流马】的荀攸发动【奇策】，即使仓廪里有“辎”，也只能选择所有手牌作为此【无中生有】对应的实体牌。

## 重铸
角色重铸一张牌，即{其将此牌置入弃牌堆，然后摸一张牌的}操作。

`角色不能同时重铸两张或两张以上的牌。`

## 将<一张牌>置于/入<一个区域>
触发一个移动事件的操作，移动的牌为此牌，原区域为此牌所在的区域，目标区域为此区域。
此次移动按照目标区域的默认放置方式进行移动，且移至目标区域后按照目标区域的默认放置方式放置此牌。

`不能将一张武器牌/防具牌/进攻坐骑牌/防御坐骑牌/特殊坐骑牌/宝物牌并非因使用而置入一名武器区/防具区/进攻坐骑区/防御坐骑区/特殊坐骑区/宝物区里有牌或武器区/防具区/进攻坐骑区/防御坐骑区/特殊坐骑区/宝物区处于封印状态的角色的武器区/防具区/进攻坐骑区/防御坐骑区/特殊坐骑区/宝物区。`
> 例如：张郃发动【巧变3】能将一名角色的装备区里的防具牌置入没有装备防具牌的诸葛亮-火的装备区，但不能将一名角色的装备区里的武器牌置入另一名装备区里有武器牌的角色的装备区。

`对于“将X张<牌>置入<装备区或判定区>”这个操作来说，若并非是作为发动一个技能的消耗或唯一效果，或“▷”左边最近的一个效果，或选项中唯一能执行的无条件执行的效果，或须选择是否执行的效果，其执行此操作即其将min{此次移动的目标区域不处于封印状态的<牌>数,X}张<牌>置入目标区域。`

`对于“<一名角色/系统>将<所有……牌>置入<装备区或判定区>”这个操作来说，若并非是作为发动一个技能的消耗或唯一效果，或“▷”左边最近的一个效果，或选项中唯一能执行的无条件执行的效果，或须选择是否执行的效果，其执行此操作即其将所有目标区域不处于封印状态的<牌>置入目标区域。`

`并非因使用而将延时锦囊牌对应的实体牌置入一名角色的判定区，须先通过系统对其使用此延时锦囊牌的合法性检测（由被使用的牌的牌面信息中的“使用目标”产生的规则对合法性检测不产生影响）才能执行此操作。执行此操作会将此延时锦囊牌的原目标移出此延时锦囊牌的目标列表并生成一个与其具有对应关系的新目标并将新目标加入此延时锦囊牌的目标列表。`
> 例如：张郃发动【巧变3】能将A的判定区里的【兵粮寸断】对应的实体牌置入判定区里已经有【乐不思蜀】对应的实体牌的B的判定区，但不能置入贾诩或判定区里已经有【兵粮寸断】对应的实体牌的C的判定区。

> 例如：张郃发动【巧变3】，若其判定区里没有【兵粮寸断】对应的实体牌，其可将A的判定区里的【兵粮寸断】对应的实体牌置入其判定区。

## 扣置于/入
触发一个移动事件的操作，移动的牌为此牌，原区域为此牌所在的区域，目标区域为此区域。
此牌背面朝上进行移动，且移至目标区域后背面朝上放置此牌。

## 弃置
将一名角色区域里的牌移至弃牌堆的操作。

`A令另一名角色B弃置牌，是由B执行弃置的操作，即由B自己选择被弃置的牌；A弃置另一名角色B的牌，是由A执行弃置的操作，即由A选择被弃置的牌。`

`A不能弃置另一名角色B的……牌，即A在选择要弃置B的哪些牌时，不能选择B的……牌。`

>例如：杨修对一名角色发动【鸡肋】选择基本牌，其不能弃置为基本牌的手牌，但是其他角色能弃置其为基本牌的手牌。

`对于“<一名角色>弃置X张<牌>”这个操作来说，若并非是作为发动一个技能的消耗或唯一效果，或“▷”左边最近的一个效果，或选项中唯一能执行的无条件执行的效果，或须选择是否执行的效果，其执行此操作即其弃置min{其能弃置的<牌>数,X}张<牌>。`
> 例如：王基于回合内发动过三次【奇制】，然后杨修对王基发动【鸡肋】选择锦囊牌，有四张手牌（均为锦囊牌）的王基于弃牌阶段内不会弃置牌。王基于结束阶段开始时发动【进趋】摸两张牌（均为基本牌），然后执行将其手牌弃置至三张的效果即弃置手牌区里的两张基本牌。

`对于“<一名角色>弃置<所有……牌>”和“<一名角色>弃置<……的所有牌>”这些操作来说，若并非是作为发动一个技能的消耗或唯一效果，或“▷”左边最近的一个效果，或选项中唯一能执行的无条件执行的效果，或须选择是否执行的效果，其执行这些操作即其弃置所有能弃置的……牌。`
> 例如：已损失的体力值为3的孙坚发动【英魂】令只有一张手牌且装备区里没有牌的陆逊摸一张牌，然后弃置三张牌。陆逊摸一张牌后须弃置全部两张手牌，然后陆逊在这两张牌移至弃牌堆后-2能发动【连营】摸一张牌（不能再弃置此牌）。

## 弃
失去标记的操作。

## <一名角色>视为装备着<一个张装备牌>
一名角色视为装备着装备牌即其拥有此装备牌的防具技能但其装备区里没有装备牌。
> 例如：马超发动【铁骑】令装备区里没有防具牌的诸葛亮的带有“锁定技“标签的武将技能于当前回合内无效，诸葛亮受到【八阵】影响拥有的防具技能【八卦阵】不会受到【铁骑】的影响。

> 例如：未受伤的吴国太能对装备区里只有一张牌的黄月英和装备区里只有一张牌的诸葛亮（火）发动【甘露】。

## <信息为A的事物>视为<信息为B的事物>
<信息为A的事物>视为<信息为B的事物>，即该事物的该信息以B为准。

> 例如：刘禅在成为关羽（神）使用【杀】的目标后发动【享乐】，关羽受到【武神1】的影响能弃置一张红桃【麒麟弓】进行响应，因为此牌的牌名视为【杀】。

## <角色A>将……牌交给<角色B>
A将这些牌移至B的手牌区的操作。

`A与B可以是同一名角色`

`这些牌不能是B拥有的牌`

`“<一名角色>将……牌交给<……角色>”是指其选择X张……牌，同时选择Y名……角色（Y∈[1,X]），同时确定分配方式（即其准备将哪些牌交给这Y名角色中的哪名角色）（须确保其交给这Y名角色中的每名角色各至少一张牌，且合计交给这Y名角色X张牌），然后将这X张牌按此分配方式同时交给这Y名角色；“<一名角色>将……牌交给任意<……角色>”是指其选择X张……牌，同时选择Y名……角色（Y∈[1,X]），同时确定分配方式（即其准备将哪些牌交给这Y名角色中的哪名角色）（须确保其交给这Y名角色中的每名角色各至少一张牌，且合计交给这Y名角色X张牌），然后将这X张牌按此分配方式同时交给这Y名角色；“<一名角色>将……牌交给等量的<……角色>”是指其选择X张……牌，同时选择X名……角色，同时确定分配方式（须确保其交给这X名角色中的每名角色各一张牌），然后将这X张牌按此分配方式同时交给这X名角色。`

`A将多个区域里的各一张牌交给B，即A将这些区域里每一个有牌的区域里的由A同时选择的各一张牌同时移至B的手牌区。`

## 拼点
触发一个拼点事件的操作。

## 摸……张牌
获得牌堆顶的……张牌的操作。

## 将<牌>弃置至<X>张
一个特殊的弃置牌的操作。
若这些牌数：大于X，执行此操作即弃置（这些牌数-X）张牌；不大于X，执行此操作即没有事发生。

## 将<牌>补至<X>张
一个特殊的摸牌的操作。
若这些牌数：小于X，执行此操作即摸（X－这些牌数）张牌；不小于X，执行此操作即没有事发生。

## 观看
查看相应牌的牌面信息的操作。

`观看一名角色的手牌默认观看其所有手牌。`

`一名角色观看暗置的牌时，这些牌依然是暗置的，即对除其外的角色依然不可见。`

## 展示
在某牌或技能的使用结算中，将背面朝上的牌翻转至正面朝上，然后除非被展示的是手牌且在此次使用结算的后续效果中须对此牌进行操作，否则须将此牌翻转至背面朝上的过程，或选择装备区里的牌的过程。此牌在展示的过程中并没有移动。

> 例如：吴国太对自己发动【补益】：
> 1、展示的手牌若为基本牌则将此牌翻转至背面朝上。
> 2、展示的手牌若不为基本牌，由于后续效果是弃置此牌，所以不能将此牌翻转至背面朝上。

> 例如：吕蒙（神）对小乔发动【攻心】，展示的小乔的一张手牌为黑桃（此牌的花色受到【红颜】的影响视为红桃），然后弃置此牌或将此牌置于牌堆顶。

`一名角色执行一个技能中展示一张牌的效果须同时记录下此牌的牌面信息，在此技能中的其他即时类效果中涉及的此牌的牌面信息皆以记录为准。`

`若一名角色没有手牌，任何角色不能执行令该角色与另一名角色同时展示手牌的操作。`
> 例如：没有手牌的张嶷不能发动【怃戎】；有手牌的张嶷不能对一名没有手牌的角色发动【怃戎】。

## 亮出
若角色亮出的是：

1、牌堆顶的牌，即其将牌堆顶的牌置入处理区。

2、牌堆里的一张……牌，即若牌堆里：有……牌，执行此操作即系统从牌堆里的所有……牌中随机将其中一张移至处理区；没有……牌，执行此操作即没有事发生。

3、背面朝上放置且不是牌堆顶或牌堆里的牌，即其将这些牌翻转至正面朝上。

> 例如：角色因判定而亮出牌堆顶的一张牌，即将牌堆顶的一张牌置入处理区。

## 交换手牌
交换双方手牌区里的所有牌的过程为：若双方的手牌区里均有牌，交换的双方先同时将自己手牌区里的所有牌扣置入处理区，然后同时将处理区里原本为对方所拥有的牌扣置入自己的手牌区；若仅有其中一方的手牌区里有牌，则其将其自己手牌区里的所有牌扣置入处理区，然后将这些牌扣置入另一方的手牌区。

## 交换装备区里的牌
交换A与B的装备区里的所有牌的过程为：若双方的装备区里均有牌，交换的双方先同时将自己装备区里的所有牌置入处理区，然后{若双方的装备区里均有与处理区里原本为对方所拥有的所有牌相同种的装备牌，系统将处理区里原本为双方所拥有的所有牌置入弃牌堆；若双方的装备区里均没有与处理区里原本为对方所拥有的所有牌相同种的装备牌，双方同时将处理区里原本为对方所拥有的所有牌置入自己的装备区；若仅A的装备区里有与处理区里原本为对方所拥有的所有牌相同种的装备牌，B将处理区里原本为A所拥有的所有牌置入自己的装备区，系统将处理区里原本为B所拥有的所有牌置入弃牌堆}；若仅A的装备区里有牌，则A将其装备区里的所有牌置入处理区，然后{若B的装备区里：有与处理区里原本为A所拥有的所有牌相同种的装备牌，系统将处理区里原本为A所拥有的所有牌置入弃牌堆；没有与处理区里原本为A所拥有的所有牌相同种的装备牌，系统将处理区里原本为A所拥有的所有牌置入B的装备区}

## 交换<两名角色>各一张确定的牌
交换双方的各一张确定的牌的过程为：交换的双方先同时将自己的那一张牌置入处理区，然后同时将处理区里原本为对方所拥有的牌扣置入自己的手牌区。

## 获得<牌>
一名角色将这些牌移至其手牌区的操作。
> 例如：郭嘉进行【闪电】的判定，结果为黑桃【酒】（两张黑桃【酒】的点数分别为3和9），在判定结果确定后-2能发动【天妒】获得此【酒】。然后郭嘉受到3点雷电伤害进入濒死状态，进行濒死结算，此时郭嘉能对自己使用此【酒】。

> 例如：周瑜（标）对小乔发动【反间】，小乔获得周瑜的一张手牌，然后展示此牌为黑桃，此牌的花色会受到【红颜】的影响视为红桃。

`对于“<一名角色>获得X张<牌>”这个操作来说，若并非是作为发动一个技能的消耗或唯一效果，或“▷”左边最近的一个效果，或选项中唯一可执行的无条件执行的效果，或须选择是否执行的效果，其执行此操作即其获得min{其能获得的<牌>数,X}张<牌>。`

`对于“<一名角色>获得<所有……牌>”和“<一名角色>获得<……的所有牌>”这些操作来说，若并非是作为发动一个技能的消耗或唯一效果，或“▷”左边最近的一个效果，或选项中唯一可执行的无条件执行的效果，或须选择是否执行的效果，其执行这些操作即其获得所有能获得的……牌。`

`A获得B的多个区域里的各一张牌，即A将这些区域里每一个有牌的区域里的由A同时选择的各一张牌同时移至A的手牌区。`

## 得到
牌移至一名角色的手牌区，即其得到这些牌。

> 例如：司马懿对自己发动【反馈】将装备区里的【白银狮子】移至其手牌区，即其因获得而得到此牌。

> 例如：刘备发动【仁德】交给法正两张手牌，法正在因交给而得到这些牌后-2能发动【恩怨1】。

`一名角色得到牌后须将所有手牌洗混，但若其是在某牌或技能的使用结算中得到牌，且在此次使用结算的后续效果中须对其中至少一张牌进行操作，则在得到这些牌后其须将除这些牌外的所有手牌洗混。`

## 失去<牌>/<手牌>/<装备区里的牌>
角色的牌移至除其手牌区和装备区外的区域，即其失去这些牌；角色的手牌移至目标区域，即其失去这些手牌；角色的装备区里的牌移至目标区域，即其失去装备区里的这些牌。

> 例如：虞翻对装备【八卦阵】的邓艾发动【直言】，邓艾摸一张牌，经展示为【藤甲】，然后邓艾使用此【藤甲】，先将此【藤甲】对应的实体牌置入处理区，在此【藤甲】对应的实体牌置入处理区后-2发动【屯田1】，然后将此【藤甲】对应的实体牌置入其装备区的同时将装备区里的【八卦阵】置入弃牌堆，在此【八卦阵】移至弃牌堆后-2能再发动一次【屯田1】。最后邓艾回复1点体力。

## 判定
触发一个判定事件的操作。

## 一名角色><操作>……所有<……牌>
若其没有……牌，其不能执行此操作。

## 合纵
一名角色的出牌阶段内的所有空闲时间点限一次，其能合纵至多3张带有“合纵”标识的手牌。
即其声明这些牌的牌名并选择：1.将这些牌（正面朝上移动）交给与其势力不同的一名角色，然后摸等量的牌；2.将这些牌（正面朝上移动）交给一名没有势力的角色。

## <一名角色><操作>（对应的实体牌为）牌堆/弃牌堆里的<一张……牌>
若牌堆/弃牌堆里：有其能操作的……牌，执行此操作即其从牌堆/弃牌堆里的所有其能操作的……牌中随机操作一张；没有其能操作的……牌，执行此操作即没有事发生。

## 洗牌
系统将弃牌堆里的所有牌置入牌堆，然后将牌堆里的所有牌洗混。