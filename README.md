# Block-Killer 「方块杀」

本文在 CC-BY-SA-4.0 许可协议下提供。

您可以自由地：

共享 — 在任何媒介以任何形式、任何用途，甚至出于商业目的，复制、发行本作品。  
演绎 — 在任何用途下，甚至出于商业目的，修改、转换或以本作品为基础进行创作。

但须遵守下列条件：

署名 — 您必须给出**适当的署名**，提供指向本许可协议的链接，同时标明是否（对原始作品）作了修改。您可以用任何合理的方式来署名，但是不得以任何方式暗示许可人为您或您的使用背书。  
以相同方式共享 — 如果您重制、转换或者基于本作品进行创作，您必须基于**与原先许可协议相同的许可协议**发布您贡献的作品。  
不得有附加限制 — 不得利用**法律术语**或者**技术措施**限制其他人做许可协议允许的事情。

This article is provided under CC-BY-SA-4.0 license.
You are free to:

Share — copy and redistribute the material in any medium or format for any purpose, even commercially.  
Adapt — remix, transform, and build upon the material for any purpose, even commercially.  
The licensor cannot revoke these freedoms as long as you follow the license terms.  

Under the following terms:

Attribution — You must give appropriate credit , provide a link to the license, and indicate if changes were made . You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.  
ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.  
No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

## 简介

这是一个以方块游戏为主要玩法的桌游，以现代方块对战为蓝本。

游戏的目标是组合你手上的方块与垃圾，攻击你的对手，令对手出局，并活到最后。

本游戏适合 3~6 人游玩。

## 游戏配件

* 方块牌 90 张

ZSJLTOI 7 种方块各 12 张，外加单元方块 6 张。

![所有方块牌](pic/card-block.png)

* 垃圾牌 111 张

见下图。

![所有垃圾牌](pic/card-garbage.png)

* 小方块若干

辅助操作用，包括由小方块（立方体）粘连拼接成的四连方块与若干单元块。

## 游戏规则

### 开始游戏

开始时，每位玩家分到 4 张方块牌与 4 张垃圾牌。

随机指定一名玩家，由这位玩家开始行动。

顺时针、逆时针方向轮流出牌均可，只需事先约定好。

### 抽牌、出牌

轮到某位玩家的回合时，该玩家需要抽取 1 张方块牌与 1 张垃圾牌，如果手上有 >=10 张垃圾牌且手上的方块牌数量 <5，可以改成抽取 2 张方块牌。

该玩家的回合结束后手上的方块牌数量必须 <6。也就是说，如果抽牌后手上有 6 张方块牌，则必须出牌。

此外的情况下玩家可以选择不出牌并跳过该回合。

#### 出牌方法（攻击）

玩家需遵循以下步骤出牌。

1. 指定要攻击的一名场上其他玩家。

2. 假想一个宽为 10 的方块场地，将想放置的垃圾牌按想要的顺序放入场地，垃圾牌允许翻转放置。垃圾与垃圾、垃圾与地板之间不得留有空列。一张垃圾牌只能使用一次。

3. 玩家可以将手上的方块牌以任意顺序，以下落式消除游戏的逻辑依次放入场地，一行填满时该行消除。方块只允许左右、向下移动，旋转，不能镜像。一张方块牌只能使用一次。

4. 当某个方块消行时，按照一定逻辑计算**攻击当量**。若手上有两行棋盘垃圾，则两行棋盘垃圾可以合并成一行实心垃圾，在放下第一块时消除。

5. 若确认方块摆放完毕，未被消除的垃圾行收回玩家手牌，所有使用掉的方块牌、被消除的垃圾牌进入弃牌堆。出牌过程中所有产生的攻击当量发送给指定的玩家。

#### 攻击当量计算

玩家的某一次消除分为两种，普通消除和旋转消除。旋转消除要求玩家消行的方块落定前最后一步是旋转且满足特定条件，不满足则是普通消行。

特殊消除：四行及以上的普通消除和旋转消除。如果打出特殊消除且上一次消除也是特殊消除，攻击额外 +1。该次消行记作 Back-to-back 消除。

行数 | 普通消除攻击 | 旋转消除攻击
:---:|:---:|:---:
1 | 0 | 2
2 | 1 | 4
3 | 2 | 6
4 | 4 | -

可以选择削弱一些满足其它特定条件的旋转消除，使其产生的攻击当量与普通消除相等。该次消行记作 Mini 消除。

可能会出现普通消除行数 >4、旋转消除行数 >3 的情况，这种情况下，超出的行数不提供攻击，只提供与多出行数相等的防御值，防御值优先于攻击生效且不能视作攻击当量。

\-

玩家也可以通过连击——连续的摆块均完成消行——增加攻击。连击数在消行开始时从 1 开始计数，方块未消行则清零。

连击奖励的攻击见下表。

连击数 | 普通消除攻击
:---:|:---:
1 | 0 
2 | 1 
3 | 1 
4 | 1 
5 | 2 
6 | 2 

#### 防御

防御方式与攻击方式相同，产生的**防御当量**与攻击当量 1:1 抵消。

若防御方抵消全部垃圾并有防御当量剩余，则剩余防御当量除以 2 向上取整后反打回攻击方，攻击方不得再次防御，需抽取对应数量的垃圾牌。

若防御方未能抵消全部攻击，则防御方要抽取剩余攻击当量数量的垃圾牌。

本轮出牌完毕后，进攻方顺位的玩家继续行动。

### 出局、胜利条件

任意时刻，若有玩家手上的垃圾牌数量 >12，该玩家出局。

最后一个未出局的玩家胜利。

## 可选特殊规则

### 毫不留情

基础攻击加强，多于 4 行的普通消行和多于 3 行的旋转消行，多出的行直接参与攻击计算，不提供防御值：

行数 | 普通消除攻击 | 旋转消除攻击
:---:|:---:|:---:
1 | 1 | 2
2 | 2 | 5
3 | 4 | 8
4 | 6 | 12
5 | 9 | 16


连击数 | 普通消除攻击
:---:|:---:
1 | 0 
2 | 1 
3 | 2 
4 | 2 
5 | 3 
6 | 3 