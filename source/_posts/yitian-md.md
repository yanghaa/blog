---
layout: matin
title: yitian.md
date: 2019-03-10 18:09:09
tags:
---

倚天GM命令全集

Go 移动
格式：/go #zone x y人物名称

  2 修罗村        3 精灵村           4 矮人村           5 拉逊沙漠         6 新人修炼场
100 混乱森林    101 石之沙漠       102 蒂尔旷野       103 吉尼草原       104 特伦特森林
105 矮人矿井    106 秘密地牢1层    107 秘密地牢2层    108 秘密地牢3层    109 精灵猎场
110 淡水湖      111 金字塔1层      112 金字塔2层      113 金字塔3层      114 混乱地牢1层
115 混乱地牢2层 116 混乱地牢3层    117 秘密地牢4层    118 秘密地牢5层    119 奈潘城外
120 死亡之谷(外)121 死亡之谷(内)   122 火龙洞        1028 奈潘城内      2000 战前集合地

附：新地图的代码(如果您有增加新地图,输入/go时请加坐标才可以使用)
123 金字塔4层   124 法师之家       125 混乱地牢4层   126 王者之家        127 新龙洞
128 死灵岛      129 精灵猎场       130 淡水湖      131~4 混乱地牢N层,无怪

说明：
/go #2  就是到2号地图(修罗村)
/go #120 300 300  就是到死亡之谷(外)修理处
/go 玩家 到玩家身边.注意这个命令必须是该玩家与你在同一个地图才可以使用,可以先/pf 玩家



常用的命令



/shop                   在线手动更新商店物品数量     
/pu                     /pureger的简写，清除当前屏幕上所有怪物，,NPC不可清除
/score                  显示你的服务器运行了多长时间
/not  内容              广播，所有地图里的人都能看见，GM发布游戏公告使用
/znot 内容              广播，限于当前地图有效
/tran 人物名称          /transfer的简写，召唤(同一地图内使用)，对方无提示确认
/sum  人物名称          召唤(不同一地图内使用)，需要对方确认
/dc   人物名称          踢玩家下线
/not  内容              广播，所有地图里的人都能看见，GM发布游戏公告使用
/znot 内容              同一地图里的人都可以看见
/zreset .               增加自己所在地图的怪物(BOSS刚死,使用此命令,BOSS直接更新)
/zreset *               增加所有地图的怪物
/mute 人名 时间          禁止人物发言  3600(时间) 为一小时. 默认为一小时
/u 人名                 /unaffect的简写，恢复使用者的状态,包括所有魔法,禁言，技能,犯罪状态(不清除犯罪值)
/siege                  开放攻城，删除当前服务器目录下siegetime.dat文件，再次输入siege将立即取消攻城
/gm                     GM隐身模式
/tree move 坐标         移动树木到指定坐标附近,不带坐标将直接清除当前屏幕所有树木
/shutdown               服务器重新启动(部分gm号可以用)
/pf 人名                普通人只是显示是否在线，GM则显示目标在哪个地图
/castle                 开攻城后，用这个命令观察.
/it 人名                /itempurge的简写 清空一个玩家物品（不包括钱）
/skillban  人名         当某玩家没有加入对应公会,而GM直接将魔法或技能刷出时,玩家该项将是黑色不可用状态,此时只需再次加入该公会,然后GM使用此命令清除黑色状态(要恢复的话目前的方法是到人物的数据文件，在魔法数据部分有个02改成00便可)
/who .                  GM使用时,显示在线人数和当前地图人数
/sh .                   等同于!
/nosh                   将看不对别人消息.再次输入取消屏蔽状态
/clan                   显示帮助信息
/oload                  此命令用于刷出目标. 无实际使用意义
/reload                 用于重新加载服务器参数.比如修改了怪物参数..使用后更新,注意,当前地图上所有怪物将是旧参数.必须重新刷出的才是新设置后的参数怪物将是旧参数.必须重新刷出的才是新设置后的参数
/castleking 帮会名称    手动设置城主帮会拥有,
/castleking gm  设置城为gm这个帮会
/castledamage           设置攻城参数.无实际使用意义
/resetquest 人名        这是早期防止使用钓鱼外挂的问题设置命令,无实际使用意义
/majiang                查看麻将排行
/uhuhu                  官方正版验证
/sneak 人物名称         使用后进入无形状态,比如:你打怪后,怪打不到你,将穿透
/excard                 此命令官方作为交易月卡使用
/save 人名              手动保存玩家数据
/save all               手动保存当前地图所有玩家数据
/marry                  是结婚命令，需要在大天使面前使用
/divorce                是离婚命令，需要在大天使面前使用
/lottery                手动开奖
/quit                   退出游戏
/set 人名 outlaw 数字   此命令用于设置人物犯罪值.最小3,最大不能超过32767
/fury of god            英译为 疯狂的上帝
/boot                   不知道如何使用
/temp                   不知道如何使用
/score                  显示时间（不知道是系统时间还是开了服务端多久）无实际使用意义
/yell 内容              世界喊话命令. 仅限于本服使用
/money                  当玩家钱负后,修复负钱问题,如果下线,负数将被清零,使用此命令将无效.
/restore                加满HP MP              
/clan new 帮名          组建帮会，组建帮会需要25万elk、25万elk和等级80以上
/clan dismiss           解散帮会

Set 设置
格式：/set 人名 设置的类型 设置的等级

/set ymir str 999       设置ymir力量999
/set ymir dex 999       设置ymir敏捷999
/set ymir int 999       设置智力999

/set ymir elk 999       设置ymir上钱加999  可以调21E   21000000000000000000
/set ymir dak 999       设置ymir下钱加999  可以调21E   21000000000000000000

/set ymir race elf      设置ymir变精灵
/set ymir race sent     设置ymir变修罗
/set ymir race dwarf    设置ymir变矮人
/set ymir sex male      设置ymir变男人
/set ymir sex female    设置ymir变女人
ps：矮人和精灵旧版本没有调换的角色，这些都是通过命令在线更换的，不需要下线，变成别的角色之后若本

身你穿了甲，拿下甲就会自己变，若你没穿甲时变的，穿上你变成后角色的甲就OK了！当然还有需要注意的是

若你拿了武器，最好取下来，因为角色变了之后，武器位置有改变，要是不先取下再拿的话，攻击怪物的时候

MTS会报错！

/set ymir hp 1000       设置ymir生命值为1000
/set ymir mp 1000       设置ymir魔法值为1000

/set ymir max_hp 1000   设置ymir的生命值为1000
/set ymir max_mp 1000   设置ymir的魔法值为1000

setskill可以缩写 /sets
/sets ymir 魔箭 252     设置ymir的小冰调到大师级(250是高手 251是专家 252是大师 )
/sets ymir 狂暴术 252   设置ymir的狂暴调到大师级

新GM命令
格式：/a ymir 999       设置ymir等级为999，

命令 /a（advace命令的简化）修改方法为在MT的0x176a7（8 9 a）
位置改原始的 E7 03 00 00 ==999 为你想要的最大等级（换成16进制换位）。
此修改可超过999级。至于最多能到多少你可以自己试！小心生命值和魔法值变负数哦！ 另外配合修改人物最

大生命值和最大魔法值命令修改。

load命令
/iload命令             添加东西到物品栏，可以简写为 /i
/i 魔力圣盔甲          添加一件魔力圣到你的物品栏里
/i 10 魔力圣盔甲       添加10件魔力圣到你的物品栏里
有些因为装备名字跟服务器里的名字不一样，刷不出来，可以直接打编号
/i 1 15000            1是数量，必须写，15000的物品编号


/mload命令            召唤怪物的命令,召唤到你的屏幕范围内，可以简写为 /m
/m 高级石头人         召唤高级石头在你的附近
/m 10 高级石头人      召唤10个高级石头在你的附近
这里有个特例:吉尼草原上著名的女人“娜菲亚”不要打错了.其实原本翻译过来是"娜菲娅"
补充：“使者”也是可以用这个命令召唤出来的，不管哪个地图都可以。


/gload命令            召唤怪物小队的命令，可以简写为 /g

/g 1                  召唤高级狂战士为首的怪物组
/g 2                  召唤堕落魔法师为首的怪物组
/g 3                  召唤金色史莱姆为首的怪物组
/g 4                  召唤僵尸为首的怪物组


group.sc内定义的怪物组号

1         高级狂战士（狂乱战士、狂怒战士、高级狂战士）
2         堕落魔法师（野猪巫师、野猪将军、堕落魔法师）
3         金色史莱姆（大史莱姆、金色史莱姆）
4         僵尸（僵尸、吸血魔王）
5         混沌怪（混沌怪、女巫、巫师）
6         巫师（黑暗狂战士、巫师）
7         蝙蝠王（蝙蝠王、蝙蝠）
8         红蜘蛛王（红蜘蛛王、鬼脸蛛、）
9         木乃伊首领（木乃伊首领、木乃伊）
10        法老（斯芬克斯、法老）
11        法老王（斯芬克斯、法老王）
12        高级狂战士（狂乱战士、狂怒战士、高级狂战士）
13        堕落魔法师（野猪巫师、野猪将军、堕落魔法师）
14        金色史莱姆（大史莱姆、金色史莱姆）
15        僵尸王（僵尸王、吸血魔王）
16        混沌怪（混沌怪、女巫、巫师）
17        初级魔法师（初级魔法师、黑暗狂战士）
18        混沌魔王（混沌魔王、女巫、巫师）
19        美杜沙（美杜沙、史前巨鳄、死魂灵、蜥蜴弓箭手）
20        独眼巨人（独眼巨人、蜥蜴弓箭手、死魂灵）
21        石像兽（石像兽、蜥蜴弓箭手、地狱犬）
22        里奇（里奇、骷髅弓箭手、骷髅护卫）
23        利爪兽（利爪兽、骷髅弓箭手、地狱犬）
24        海妖（海妖、克雷林）
25        骷髅护卫（骷髅护卫、骷髅弓箭手）
26        独眼巨人（独眼巨人、蜥蜴弓箭手）
27        骷髅魔王（骷髅魔王、骷髅将军、骷髅弓箭手）
28        骷髅王（骷髅王、骷髅将军、骷髅弓箭手）
29        火龙（火龙、地狱犬、女巫）

/load系列命令到此告一段落 上面是系统默认的，可以自己添加！


/oload    是系统物品
1         火堆
2         树
3         树
4         树
5         树
6         城门  （左下至右上）
7         城门  （左下至右上）
8         城门  （左下至右上）
9         城门  （左下至右上）
10        城门  （左下至右上）
11        城门  （左下至右上）
12        城门  （左下至右上）
13        城门  （右上至左下）
14        城门  （右上至左下）
15        城门  （右上至左下）
16        城门  （右上至左下）
17        城门  （右上至左下）
18        城门  （右上至左下）
19        城门  （右上至左下）
20        内城门（左下至右上）
21        内城门（左下至右上）
22        内城门（左下至右上）
23        内城门（左下至右上）
24        内城门（左下至右上）
25        木门  （左下至右上）
26        木门  （左下至右上）
27        木门  （左下至右上）
28        木门  （左下至右上）
29        木门  （左下至右上）
30        木门  （左下至右上）
31        木门  （右上至左下）
32        木门  （右上至左下）
33        木门  （右上至左下）
34        木门  （右上至左下）
35        木门  （右上至左下）
36        木门  （右上至左下）
37        大木门（右上至左下）
38        大木门（左下至右上）
39        隐门石柱