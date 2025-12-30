+++
title = '《最终幻想12: 黄道年代》超功利白金攻略'
date = 2025-12-30T14:56:00+08:00
draft = false
+++
# 最终幻想12: 黄道年代 - 白金/全成就攻略

## 参考

- [天幻专题站](http://ff12.ffsky.cn/) **建议遇到任何资料上的疑问都可以先查天幻专题站，翻译对照表我放在 [腾讯文档](https://docs.qq.com/sheet/DRHVnUkpzVWZIb0hC) 了**
- [TZA完美攻略(英文)](https://github.com/chrisdevisser/ff12-tza-guide)
- [Steam社区地图+宝箱攻略(英文)](https://steamcommunity.com/sharedfiles/filedetails/?id=1292596668)

## 介绍

- 本攻略包含了白金流程的所有内容，并且对于和无脑快速白金思路无关的内容，只会给予一点额外提示或者干脆略过，完成本攻略也意味着完成了:
    - 公会等级 **永生诸神** (这甚至是本游戏的一个速通赛道)
- 本攻略尽量照顾初次游玩的玩家，会在一些需要一定理解的技巧方面给出建议

### 写这个攻略的动机

目前天幻有完整的资料站，也有很详细的攻略，但是存在以下几个问题:

- 没有针对重制版(黄昏年代)的新中文翻译(虽然翻得一坨屎)的资料
- 路线并非很优，或者有些攻略对新人不友好
- 经常要查询不同的页面去完成特定的奖杯内容
- 大多比较矜持不够功利，导致整体不够爽快，比如:
    - 拒绝三神器
    - 拒绝用考验模式获取装备
    - 不提示可以顺手击杀的稀有敌人或出现条件苛刻的敌人，导致后期补起来需要东奔西走

<!--more-->

### 职业和召唤兽

这个攻略用了 [TZA完美攻略(英文)](https://github.com/chrisdevisser/ff12-tza-guide) 里的职业和召唤兽分配，你也可以按照自己的喜好来分配，其实对于白金来说影响没那么大，不管怎么组合，按照注意事项来其实都没有特别的难点

### 关于AC

- AC(Area Change)是指切换小地图区域，通常用于刷新宝箱或者怪物，英文攻略里也叫ZC(Zone Change)或者Zone N Areas(切换了N个区域)
- 1AC是指切换一次小地图区域再切回来
    - 就是A-\>B-\>A
    - 可以刷新地图上的可再生宝箱
- 2AC是指切换到过和本区域不同的两个区域
    - 比如A-\>B-\>C-\>B-\>A(线性地图)或者A-\>B-\>C-\>A(环状地图)都算2AC
    - 可以刷新地图上的大部分怪物，但部分稀有怪除外(一般需要完整切换大地图，或者存档后读取)，会特别说明
    - 可以用A-\>B，读取自动存档后回到A的方式模拟2AC，但是此法会失去Chain(同类敌人连锁)累计

### 宝箱格式

- 只有值得注意的宝箱会写在攻略里，为了奖杯必须拿到的宝箱内容前面会加星号(\*)
- [数字坐标] 道具名 (出现概率%, 随机到此道具的概率%)
    - 数字坐标会标在配图上
    - 出现概率%是你进入这个区域时出现的概率，可以通过1AC来刷新
    - 随机概率%是两个概率的叠加，没有随到钱的概率乘以随到此道具的概率

### 商人购买

- 攻略中提示的魔法和招式购买是应对无神器流程的，没什么用的可能会延后购买，其实有钱可以看到就买下来，反正奖杯要求全魔法全招式，和宝箱一样，为了奖杯必须购买的前面会加星号(\*)
- 饰品之类的一般是为了后面打Boss规避某些异常，钱够的话建议一定要按照攻略提示购买，遇到会给你加某些异常的Boss，可以对应地装备该异常无效的饰品
- 有钱的话各种药可以多买点，用药解除异常或者回血/复活的后摇比较小，和魔法比更利于提高输出效率

### 地图标记

- (R) 表示稀有敌人，但是符合特定条件或者刷新大地图后就会重复出现，建议路过就杀掉，避免之后补图鉴的时候跑马拉松。有时候刷不出来可以先看一下图鉴，是不是不小心顺手杀了没注意
- (T) 表示稀有狩猎讨伐敌人，击杀获取讨伐证就不会再出现，可能会有要偷取的道具，请务必不要急于击杀，如果不小心击杀了可以立即读取自动存档挽救。当然，本攻略只有一个骷髅龙 **迈思** 有要偷的道具，其他见面就杀也没问题
- (U) 表示宝藏瓮，一般是地图，也有贵重道具，不过本攻略不依赖任何宝藏瓮里的贵重道具
- (M) 表示委托敌人
- (E) 表示召唤兽
- (!!) 表示任务/委托相关的可交互物件，可能会有前置条件，没提的话可以不管，一般都是支线事件
- 数字表示宝箱

### 随机掉落

- 本攻略基本不依赖随机掉落(需要的地方会特别指出)，但是掉落物毕竟可以卖钱，前中期没有 **猫耳风帽** 的情况下也是不错的经济来源，所以能捡的就捡一下。
- 心得书交易品提供的额外掉落也挺值钱，但是因为猫耳风帽来钱太快，所以意义也不大，攻略中只需要购买一本心得书。
- 需要偷取的道具，装备 **盗贼之袖** 可以大幅提升偷到的概率，并且可以同时偷到多个道具(一般的敌人分为几个概率档位的偷盗道具，盗贼之袖会让每个档位都独立随机)，所以需要偷的时候一定要装备上。
- 提升Chain连锁数可以提高各种道具的掉落率，但是连锁等级提升需要尽量不拾取道具(只有当连锁的数字变成白色并闪烁时不会有拾取惩罚)，因此本攻略不会基于高连锁等级来设计。
    - 心得书掉落不受连锁等级影响。
- 盗猎: 本攻略不需要盗猎，并且在自动行动里开盗猎遇到不能盗猎的敌人会影响推进效率，如果不追求完美的话可以全程不盗猎。

### 一些提示

- 绝大多数动作的目标都可以是敌我双方的，按R1就可以切换敌我和NPC
- 作战布局里的各种buff，debuff，解除buff类的魔法和道具，不需要加条件，直接选 **眼前的敌人** 或者 **我方一人**，也会在适用条件的时候才适用，比如 **驱魔** 只会对有buff的敌人使用， **解毒药** 只会对中毒的我方使用， **大浮空** 只会对没有浮空的队友使用，因此大多数条件指令都没有买的必要
    - 一个例外是偷东西怕偷完了还会继续偷，这里有个小技巧就是，设为对 **HP=100%的敌人** 偷盗，这样一般你偷了一下，队友再打一下不是满血了，就不会继续偷了

## 翻译对照表

- [腾讯文档](https://docs.qq.com/sheet/DRHVnUkpzVWZIb0hC)
- 其中宝箱的翻译对照表是对照的 [天幻专题站国际版宝箱](http://ff12.ffsky.cn/map/map.htm) 的编号

## 三神器简单获取方法的视频

- [B站地址](https://www.bilibili.com/video/BV1FSBCBpEXx)

## 敌人所在地图检索表

- 在 [这里](/posts/ff12/foes/)

## 游玩过程中必定获得的奖杯，不单独标注获得时机

- *【突击前锋】 已执行战斗300次以上的证明。*
- *【魔法射手】 已使用魔法200次以上的证明。*
- *【暴力执行者】 已使用招式100次以上的证明。*
- *【无影快手】 已盗取成功50次以上的证明。*
- *【极度屠杀者】 至今已打倒500只以上怪物的证明。*
- *【伊瓦利斯行者】 至今已移动50000步以上的证明。*
- *【富有大户】 至今已获得100000GIL以上的证明。*
- *【纪录保持人】 已赚取500000公会点数的证明。*
- *【挥金如土】 至今已消费1000000GIL的证明。*
- *【双面卖家】 至今已卖掉1000个以上宝物的证明。*
- *【英雄】 队伍平均等级已超过50的证明。*
- *【十项全能】 所有人已取得48000执照点数的证明。*

## 那尔比纳城塞

- 上楼梯瑞克斯变成一个人后击杀三个帝国兵，然后回头存档，请务必不要覆盖这个存档!!!，之后伪随机摸宝箱要用
    - 获得奖杯: *【为了祖国】 以新兵身分跟阿凯迪亚帝国交战过的证明。*

## 拉巴纳斯塔

- 梵恩: 枪骑兵
- 游戏正式开始，主线一般跟着小地图提示走都就行，只会简单提一下要点，主要提示和奖杯相关、以及提升强度或效率的行动

### 沙海亭

- 接受委托: **失散番茄**
- [托玛吉] 开始委托: **失散番茄**

## 东达玛斯卡沙漠

### 沙段山丘

- (M) 失散番茄
    - 获得奖杯: *【加芭纳红花】 首度打倒了悬赏怪物的证明。*

## 拉巴纳斯塔

- 回城触发主线剧情，打开小地图界面会有目标指示，跟着指示走，出南门去草原

## 居扎草原 - 旱季

### 游牧民族聚落

- 主线剧情
    - 获得阴石的情报
    - 潘妮萝加入: 黑魔道士

### 托姆丘陵

![托姆丘陵](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/000.png)

- [34] \***盲目** (100%)
- 南边有全地图仅有的一只狂暴蛇，至少杀一只，影响奖杯，不要漏过了

### 幼小水晶的河畔

- 主线剧情
    - 获得阴石
    - 去周围区域集满100%完成月牙石

## 加蓝赛兹水路

- 不管委托什么的，先继续主线

### 第10主水路

![第10主水路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/004.png)

- [29] 蚕丝衣 (70%, 30%) 要等之后绕过来才能拿
- [32] 锤矛 (70%, 27.5%)

### 北部辅助水路

- (R) 剃刀鳍 (杀人鱼10%概率变异, 2AC刷新)

## 拉巴纳斯塔王宫

![拉巴纳斯塔王宫](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/006.png)

- [7] 奥尔阿奇亚手环 (100%)

## 加蓝赛兹水路

- 主线剧情
    - 巴夫雷尔: 赤魔战士
    - 法兰: 白魔道士
    - 可以用作战布局了，作战布局的指令都是店里买的，按照需要可以买一些，大多数在本流程里都没用，奖杯不要求买完，主要有用的有:
        - 我方各角色 (诱饵用)
        - HP或者MP小于比例的我方(自动回复用)
        - HP最低的敌人(boss群殴从低到高击杀用)
        - HPmax最高的敌人(带小怪的boss偷盗/破坏用)
        - HP=100%的敌人(偷盗用)
- 中段的主线Boss弱火，法兰自带火焰魔法随便打

### 第11主水路

![第11主水路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/007.png)

- [20] 裤袜 (75%, 30%)

## 主线剧情

- 水路尽头的主线Boss要注意回复
- 之后被抓，跟着指示走，先赤手空拳打一架，然后取回装备

## 柏尔海姆地下道

- 注意杀一只模仿怪(拟态宝箱)

### 配电设备区块

![配电设备区块](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/008.png)

- [1] 2510 gil (100%)
- 购买 \***解毒**, \***发声**: 510 gil

### 第29作业区快

![第29作业区快](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/009.png)

- [4] 尖帽 (75%, 30%)

### 第36作业区快

![第36作业区快](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/010.png)

- [16] 战斗挽具 (100%)

### 第四总站

- 主线Boss: 模仿怪女王 (弱冰)
    - 不要让小怪偷太多电，可以分一个人去打小怪

## 获得钻石手环

- 回到游戏标题，选TRIALS，在第一关的宝箱里开出 **钻石手环**，然后进入第二关后立即退出，并且读取自动存档，这样就获得了 **钻石手环**(比西沙漠的获取方式更安全快捷)

## 东达玛斯卡沙漠

### 沙原天板

![沙原天板](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/002.png)

- [25] 菱纹手环 (55%, 25%)
- [31] \***施毒** (100%)
- (R) 涅赫贝特 (击杀一只以上的鸡鸵后20%概率出现)

### 小营地

- 萤火虫 (100%)

## 拉巴纳斯塔

- 主线剧情
    - 队友全部离队
    - 跟着小地图指示走，巴修入队
    - 巴修: 猎长
    - 获得奖杯: *【将军归来】 从那尔比纳城塞生还的证明。*
    - 去沙海亭，另外两人也归队了
- 然后开始清理委托

## 拉巴纳斯塔

- 沙海亭
    - [托玛吉] 完成委托: **失散番茄** (没错之前虽然显示讨伐完成了，但是奖励我们还没拿，之后的完成委托都以拿到奖励为准)
    - 接受委托: **铁克斯达**, **花仙人掌**, **亡灵**
    - [加斯里] 开始委托: **铁克斯达**
- 市区北部 - 公会总部
    - [蒙布朗] 接受紧急委托: **鸵鸡**, **巨岩龟**
- [作战布局店] 稍微买点可能有用的，那些乱七八糟的敌方条件大多都不用买，本流程也用不到
- [外门前广场] 购买地图: 630 gil
- [西门 飞空艇总站] 摸神器计划启动，立即坐飞空艇 **悠闲航班** 前往那尔比纳城塞
    - 悠闲航班上有一个七姐妹支线，和奖杯无关

### 了望甲板

- (神弓) 支棱 (1%, 1%)
    - 这里介绍一个简单获取方法，已经对PS5主机上初始化随机数的变化进行了改进，我录了视频，地址在攻略开头 (仅适用于PS4版本; PC版请自行研究RNG工具，或者直接打mod; Switch版最难拿，请自行搜索视频攻略)
        - 给 **梵恩** (注意这里只有梵恩能摸宝箱)装备 **钻石手环**
        - 飞空艇走到了望甲板后退出，游戏会有个甲板自动存档
        - 完全关掉游戏重启后快速读取我们之前准备的瑞克斯的存档，使用PS4主机玩的话砍自己两刀，使用PS5主机玩的话砍自己6刀(如果反复几次序列出不了就少砍一刀)，然后一直给自己放回复魔法(MP不够就摸蓝水晶)直到出现连续三次的数字是97,94,95(如果20次以内不出这个序列，退出游戏重来)
        - 按OPTION后再按□退回主菜单
        - 读取甲板自动存档，走到箱子旁边，等小孩子从父亲走到中间栏杆停下的时候摸，必出
    - 本流程建议至少摸三把，摸6把也可以，省得切换了。
    - 因为神弓不需要执照就能装备，能解决99.9%的问题，所以后面的武器宝箱除了特殊场景需要的其他就不摸了

## 那尔比纳城塞

- 购买 \***雷电**, \***暗波**: 700 gil
- 在传送水晶旁边的商人那里买点洋葱矢，神弓要用
- 向南往王都方向走

## 东达玛斯卡沙漠

### 小营地

- [丹特罗] 开始委托: **花仙人掌**

### 沙纹迷宫

![沙纹迷宫](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/001.png)

- [19] \***沉默** (100%)
- (M) 花仙人掌
- (R) 喧闹草 (每杀一只矮仙人掌，有33%概率出现)

### 小营地

- [丹特罗] 完成委托: **花仙人掌**
- 然后穿过王都往南去 **居扎草原**

## 居扎草原 - 旱季

### 游牧民族聚落

- [达妮亚] 开始委托: **鸵鸡**

### 基惹士河沿岸北侧

![基惹士河沿岸北侧](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/012.png)

- (M) 鸵鸡 (先击杀所有敌人然后1AC)

### 游牧民族聚落

- [达妮亚] 完成委托: **鸵鸡**
- 然后回到王都往西去 **西达玛斯卡沙漠**

## 西达玛斯卡沙漠

### 加尔提亚丘陵

- [南边] (M) 铁克斯达

### 风纹之地

![风纹之地](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/053.png)

- [36] 钻石手环 (25%) 已经有了，不过看在防雷的份上也可以拿一下

### 热浪升起的平地 (南部)

![热浪升起的平地 (南部)](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/014.png)

- [28] 奥尔阿奇亚手环 (100%)

## 拉巴纳斯塔

- [沙海亭 加斯里] 完成委托: **铁克斯达**
- 心得书交易品前置，这里只是列举一下，本攻略理论上只要摸公告板20次->购买魔剑士的心得就可以完成整个流程了
    - [市区西部 牟斯鲁市集] 对话 **加斯里** (->猎人的心得)
    - 摸公告板40次 (20次->魔剑士的心得，40次->龙骑士的心得)
    - 魔法商店对话25次 (->魔道士的心得)
    - 防具商店对话15次 (->学者的心得)
    - 武器商店对话30次 (->骑士的心得)
    - 任意商店对话100次 (->贤者的心得)
- 此时7本心得书应该出现在交易品利了，价格都不一样，根据价格就可以知道是什么心得。等有钱了再买吧，再次强调一下: 本攻略只需要魔剑士的心得!
    - 18000: 猎人的心得 (魔兽、怪鸟系)
    - 19000: 骑士的心得 (巨人、昆虫系)
    - 22000: 龙骑士的心得 (龙族、植物系)
    - 25000: 贤者的心得 (元素、精灵系)
    - 22000: 学者的心得 (物质系)
    - 20000: 魔剑士的心得 (软体生物、不死系)
    - 21000: 魔道士的心得 (魔法生物系)
- [魔法商店] 购买 \***复明**, \***疗伤**, \***火焰**: 580 gil
- [招式店] 购买 \***窥伺探测**, \***急救**: 1000 gil
- [闹区北部 密尔哈] 开始委托: **亡灵**

## 加蓝赛兹水路

- [最终处理区块] (M) 亡灵 (弱雷)

## 拉巴纳斯塔

- [闹区北部 密尔哈] 完成委托: **亡灵**
- [西门 飞空艇总站] 找到巴夫雷尔，推进主线剧情

## 空中都市卜耶巴

- 地图: 720 gil
- [魔法店] 购买 \***魔防壳**, \***物防护**, \***止移**: 1000 gil
- [招式店] 购买 \***充能**: 1500 gil

## 路苏魔石矿

### 欧坦桥

![欧坦桥](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/015.png)

- [7] 托布卡普帽 (75%, 30%)
- (R) 飞天蝠 (20%概率出现在左右两侧)

### 第1运送路

![第1运送路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/016.png)

- [12] \***算术** (100%)

### 苏尼亚平行桥

- 这里可以Chain连锁骸骨打钱升级，把和魔剑士的心得买了，其他心得书你看着办，一般一趟把骨屑刷到99个差不多就够了
    - 获得奖杯: *【不屈不挠】 战斗连锁已达成50连锁以上的证明。*

### 第2矿区采掘场

![第2矿区采掘场](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/017.png)

- [16] 钢颈甲 (70%, 35%)
- 主线剧情
    - 这里有个bug，如果主线剧情跑掉再回来，宝箱就不见了，想拿这个宝箱可以冲过去看，没出就读取自动存档，当然，因为我们有神弓了，这里也可以杀光敌人而不逃跑

## 空中都市卜耶巴

- 主线剧情: 把数字撑到100%，最快的方法是去[浮云亭]里吼两声，之后跟着地图标记走
- 都市地图全开了，注意逛一下各个区域(主要是最东边那个区域)，奖杯要用
- [魔法店] 购买 \***复活**, \***水流**, \***止动**: 3200 gil
- [浮云亭] 接受委托: **尼德霍格**
- [采掘场前小广场 艾可姆] 开始委托: **尼德霍格**
- [库斯空中广场 皮利卡] 开始委托: **巨岩龟**

## 路苏魔石矿

### 第1运送路

![第1运送路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/016.png)

- (M) 尼德霍格

### 第2矿区采掘场

![第2矿区采掘场](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/017.png)

- (M) 巨岩龟

## 空中都市卜耶巴

- [库斯空中广场 皮利卡] 完成委托: **巨岩龟**
- [采掘场前小广场 艾可姆] 完成委托: **尼德霍格**
    - 注意: 不要卖掉奖励里的 **巨蛇外壳**
- 继续推主线，去救人了

## 战舰利维坦

### 大型货柜仓库

![大型货柜仓库](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/018.png)

- [5] 大反射的魔片 (100%)
- [6] 大反射的魔片 (100%)
- [9] 链板甲 (80%, 37.5%)
- [10] 牧羊人短衫 (80%, 37.5%)

### 第１禁闭室

- 主线剧情，雅雪加入
    - 获得奖杯: *【缘分】 救出了达玛斯卡公主的证明。*
    - 雅雪: 骑士
- [商人] 购买 \***缓慢**: 200 gil

### 副控制室

![副控制室](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/019.png)

- [19] \***ＭＰＨＰ** (100%)  错过也没关系，后面有地方补

### 中层东侧区块

![中层东侧区块](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/020.png)

- [11] \***催眠** (100%)  错过也没关系，后面有地方补
- [12] 钢铁甲 (75%, 30%)
- 之后是主线Boss，切菜

## 西达玛斯卡沙漠

- 这里有个商人，我们买点东西:
    - 购买三个 **黑带**: 1800 gil
    - 购买两个 **玫瑰胸饰**: 2400 gil
    - 购买 \***暴雪**, \***中疗伤**, \***劲风**, \***重力**: 5740 gil
    - 购买 \***盗猎**, \***时间攻击**: 7000 gil
- 先从西沙漠走回王都接一个委托，这样避免之后来回奔波

### 中央断层

![中央断层](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/013.png)

- (R) 菲地尔 (每次进入20%概率出现)

## 拉巴纳斯塔

- [沙海亭] 接受委托: **飞龙领主**
- [阿玛尔武具店 夏亚尔] 开始委托: **飞龙领主**

## 大沙海那姆·焉萨

### 第１工厂东侧油槽

![第１工厂东侧油槽](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/176.png)

- [2] \***ＭＰＨＰ** (100%) 当你没摸战舰上的才会出现，算是官方补救措施，防止你错过奖杯
- [4] \***催眠** (100%) 当你没摸战舰上的才会出现，算是官方补救措施，防止你错过奖杯

### 第1石油工厂

![第1石油工厂](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/021.png)

- (R) 菠萝榴弹怪 (20%概率出现，注意不仅出现在图示位置，也可以出现在中间圆环和右下圆环，刷的时候建议扫一下全部可能位置)
- [11] 斗篷 (75%, 32.5%)
- [12] **金色护身符** (100%)  LP获得量翻倍，用法你懂的
- [14] 三角帽 (75%, 32.5%)

### 中央结点

- 从东北进入 **杰尔提尼安洞窟**

## 杰尔提尼安洞窟

### 地之森

![地之森](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/022.png)

- [46] \***黑暗杀法** (100%)
- 出去到 **风化的岸边**

## 大沙海那姆·焉萨

### 风化的岸边

![风化的岸边](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/023.png)

- [11] 飞速头盔 (70%, 22.5%)
- [13] 龟壳项圈 (100%)
- (R) 伊姆杜基德 (击杀所有敌人后等待)
- 原路返回

## 大沙海奥格·焉萨

- 开始击杀兀鲁坦·焉萨族 (需要杀100只，所以最好Chain连锁)

### 大型油槽基地

![大型油槽基地](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/024.png)

- [25] \***反射** (100%)
- [29] 魔法师之服 (75%, 40%)
- [32] 亚麻铠甲 (75%, 40%)

### 第2石油工厂

![第2石油工厂](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/025.png)

- [46] 皮颈甲 (75%, 37.5%)
- (R) 流放的兀鲁坦·焉萨族 (击杀100只兀鲁坦·焉萨族后出现，PS4版没有更新翻译修正，还是叫兀鲁坦·焉萨族，注意看是稀有怪物就行了)

## 大沙海那姆·焉萨

- 这里有个剧情
    - 在蓝水晶旁和莫古对话
    - 然后去西边看到一群兀鲁坦·焉萨族在围攻一只大乌龟
    - 杀了以后回到蓝水晶小地图东边的高台触发剧情后回蓝水晶处长剧情后获得伊克希洛果实
    - 下一个主线Boss用了伊克希洛果实可以降低他的伤害，但是因为我们有神弓，这玩意儿基本没用，所以可以不拿。

### 女王治理的沙原

![女王治理的沙原](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/026.png)

- (R) 巨大炸弹 (Chain连锁数到22后出现，可以出现在西半部分各个角落，不仅限于这个位置)
- [38] \***平衡** (100%)

### 热风吹下的高台

![热风吹下的高台](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/027.png)

- (M) 飞龙领主
- [45] 雏鸟披肩 (100%)
- [47] 战工帽 (75%, 35%)
- [48] 咏唱长袍 (75%, 35%)
- [50] 闪光魔帽 (75%, 35%)
- [52] 2918 gil (100%)

### 温暖消逝之路

- 这里有一个商人，我们买点东西:
    - 购买三个 **西阵织带**: 2400 gil
    - 购买 \***停顿**: 900 gil
- 主线Boss: 迦楼罗 (弱暗波)

## 瑞斯沃尔王墓

### 攻壁之室

- 主线Boss: 恶魔墙+恶魔墙 (弱劲风)
    - 本来这两个Boss需要大反射的魔片打，但是有神弓其实几下就秒了
- 打完后回头可以摸墙上的隐藏宝玉，从出现的新楼梯下去推门出去可以拿到隐藏区域的箱子 **崩炮的魔片**

### 大通廊

![大通廊](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/028.png)

- (R) 巴尔穆 (Chain连锁12只搜捕蝠)
- [1] \***驱魔** (100%)
- [3] \***匿迹** (100%)

### 北翼通廊

![北翼通廊](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/029.png)

- [6] 咏唱长袍 (80%, 35%)
- 触摸 **北翼台座**

### 南翼通廊

![南翼通廊](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/030.png)

- [12] 大急速的魔片 (100%)
- [18] 闪光魔帽 (80%, 35%)
- [19] 厚重外套 (75%, 35%)
- (R) 突变巫妖 (巫妖低HP分裂时20%变异，神弓攻击太高，换低伤害武器打吧)
- 触摸 **南翼台座**
- 从新开的道路进入火焰回廊

### 火焰回廊

![火焰回廊](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/031.png)

- [20] 凤凰尾巴 (100%)
- [21] 嗜血剑 (100%)
- [22] \***随机魔法** (100%)
- [23] 万灵药 (100%) **注意: 万灵药至少留5个，后面留着打考验模式100层用**
- 主线Boss: 白羊座召唤兽 **魔人贝利亚斯** (弱水)
    - 给 **梵恩**
- 可以选择第二职业了
    - 梵恩: 破坏者
    - 巴夫雷尔: 机工士
    - 法兰: 时空魔战士
    - 巴修: 武士
    - 雅雪: 弓箭手
    - 潘妮萝: 武僧
- 离开王墓时主线战斗加剧情
    - 获得奖杯: *【魔雾失控】 取得了「晓之断片」的证明。*

## 拉巴纳斯塔

- 接下来是大段的自由活动时间
- [市区西部 牟斯鲁市集 公会商店] 购买 \***油液**, \***诱饵**: 2800 gil
- [阿玛尔武具店 夏亚尔] 完成委托: **飞龙领主 (先交任务，不然可能公会等级不够下面的部分委托不会出现)**
- [公会总部] 接受紧急委托: **金钱龟**
- [沙海亭] 接受委托: **恩克多拉斯**, **凯罗葛洛斯**, **白慕斯**, **圆环龙**, **马莉莉丝**
- [沙海亭 酒馆老板] 开始委托: **马莉莉丝**
- [闹区北部 巴尔查克] 开始委托: **圆环龙**
- [西门 索尔贝] 开始委托: **白慕斯**

## 西达玛斯卡沙漠

- 从 **热浪升起的平地** 进入 **杰尔提尼安洞窟**

## 杰尔提尼安洞窟

### 引诱异端的岩窟

![引诱异端的岩窟](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/032.png)

- [3] 萤火虫 (100%)
- (M) 马莉莉丝 (弱水流, 吃缓慢, 盲目)
    - 击杀敌人后在阳光照进来的地方慢慢等，直到出现

### 风纹之地

- 固定沙尘暴天气
- (M) 圆环龙 (弱火焰, 吃缓慢, 盲目)

## 大沙海奥格·焉萨

### 中央结点

- 东北进入 **杰尔提尼安洞窟**

## 杰尔提尼安洞窟

### 地之森

- 推石头连通道路

## 大沙海奥格·焉萨

### 东侧结点

![东侧结点](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/033.png)

- [17] 开面盔 (70%, 35%)
- 东北进入 **杰尔提尼安洞窟**

## 杰尔提尼安洞窟

- 向西再向东南

### 落沙黑暗

![落沙黑暗](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/034.png)

- 推石头
- [10] 钻石手环 (100%)

### 海的尽头

![海的尽头](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/035.png)

- [25] (隐藏区域) 盗贼之袖 (25%)

### 沙漏山谷

![沙漏山谷](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/036.png)

- [17] 锁子甲 (90%, 45.5%)

## 拉巴纳斯塔

- [公会总部] 完成委托: **马莉莉丝**
    - 奖励里的 **巨蛇外壳** 不要卖掉
- [闹区北部 巴尔查克] 完成委托: **圆环龙**
- [沙海亭] 接受委托: **欧特洛斯**
- [闹区北部 席克族小偷] 开始委托: **欧特洛斯**

## 加蓝赛兹水路

### 西部水量调整区

![西部水量调整区](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/037.png)

- (M) 白慕斯 (弱火焰, 吃盲目, 催眠)

## 拉巴纳斯塔

- [西门 索尔贝] 完成委托: **白慕斯**

## 东达玛斯卡沙漠

### 小营地

- 对话 **丹特罗**，帮忙送口信

### 涅布拉河岸边

![涅布拉河岸边](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/003.png)

- [39] 手镯 (55%, 25%)
- (R) 贪食者 (三分钟不击杀任何一个仙人掌)

### 涅布拉河沿岸聚落南侧

- 对话 **丹特罗的太太** 两次
- 拾取 **谢姆贝的贝壳** (聚落外面岸边三个 聚落内岸边两个) (注意: 拿全影响后面的奖励)
- 对话 **丹特罗的太太**

### 小营地

- 对话 **丹特罗**
- 拿取营地内的两个 **涅布拉伤药** (注意: 拿全影响后面的奖励)

### 涅布拉河沿岸聚落南侧

- 对话 **丹特罗的太太**，要你去收集 **峡谷花露水**

### 涅布拉河沿岸聚落南侧

- 对话 **齐格力** 到达对岸
- 对话 **路克瑟拉**
- 回到南岸对话 **丹特罗的太太**
- 对话屋后地上的 **仙人掌的花?**
- 对话 **齐格力**，剧情后可以进入东沙漠北部区域了

### 尤玛大沙丘

![尤玛大沙丘](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/038.png)

- [49] 骨头盔 (75%, 32.5%)
- [50] 骨铠甲 (75%, 32.5%)

### 断裂沙地

![断裂沙地](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/039.png)

- 获取全部三个 **峡谷花露水** (注意: 拿全影响后面的奖励)
- [59] 黑头巾 (80%, 32.5%)
- [63] 海盗外套 (80%, 32.5%)
- [70] 狂战士 (100%)
- [71] 钻石头盔 (80%, 25%)

### 涅布拉河沿岸聚落南侧

- 对话两次 **丹特罗的太太** (如果之前没有问你要，此时会交出巨蛇外壳，反正保证整个流程里把巨蛇外壳交出去就行了)
- 1AC后对话屋后的病人(如果前面按照攻略拿全了，会是一个莫古族)，获得 **巴尔海姆地下道的钥匙** 和 **金色护身符**
    - 很好，第二个 **金色护身符**

## 那尔比纳城塞

- 北方出口守卫触发事件
- 租陆行鸟，到北出口，守卫离开，可以直接进入莫斯佛拉山地了 (也可以直接从东沙漠进入，随便你，这个剧情还有点意思可以看看)

## 莫斯佛拉山地

- 此区域晴天会出现 **火之元素**，杀一只，完成【说书人】奖杯的怪物图鉴需要用，之后各种天气对应的元素都会提示击杀，注意不要错过

### 远眺顶端的山路

![远眺顶端的山路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/040.png)

- (R) 反击狼 (每只座狼7%概率变异)

### 传出水声之处

![传出水声之处](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/041.png)

- 购买地图: 2400 gil
- [24] 盗贼之袖 (100%)

### 岩板耸立之路

![岩板耸立之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/042.png)

- [28] 雕花长靴 (100%)
- [29] 钻石甲 (75%, 30%)
- [30] 黑装束 (75%, 30%)

### 北侧山麓

![北侧山麓](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/043.png)

- [35] 金属无袖衣 (70%, 30%)

### 降下东风之桥

![降下东风之桥](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/044.png)

- [42] 万灵药 (80%)
- 向北进入萨利卡树林

## 萨利卡树林

### 叶缝阳光之路

![叶缝阳光之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/045.png)

- (R) 史皮 (每杀一只 **幸运兔** 15%概率出现)

### 疗愈回响之路

![疗愈回响之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/046.png)

- [33] \***劝诱** (100%)
- 再往前就是一个比较难的Boss了，暂时不打，我们回头

## 杰尔提尼安洞窟

### 沙漏山谷

![沙漏山谷](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/036.png)

- (R) 厄姆司提 (在东边隐藏区域等15s, 就会出现在对面的常规区域)

### 阿思罗萨大流沙

- 摩羯座召唤兽 **愤怒灵帝亚卓梅列克** (弱冰, 装备防雷防具)
    - 给 **巴修**
- 获取3个 **染血首饰** (杀邪尸, 心得书30%概率掉落)，不要卖掉

### 芭兰卡断层

- 这里有洞窟的地图可以摸，但我不建议摸，毕竟并非奖杯需求，真要摸的话注意一路狂奔，这里的上古壳龙是全游戏最强普通怪

## 柏尔海姆地下道

- 在东沙漠用钥匙打开地下道入口 (注意有南北两个入口，这钥匙是开的北边那个门)

### 第5特别作业区

![第5特别作业区](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/047.png)

- [41] 妖术师之服 (90%, 25%)
- [43] 护身头巾 (90%, 25%)
- (R) 锁定者 (每次进入有20%产生, 是一个拟态宝箱, 6%概率偷得死亡使者, 无神器流程的必拿装备，我们有神器就随意了)

### 东西旁道

![东西旁道](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/048.png)

- [48] \***毒域** (100%)
- [49] 柔术装/烈火箭 (90%, 25%)
- (R) 小拟态虫 (20%概率出现)

### 洁拜亚连结桥

![洁拜亚连结桥](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/049.png)

- [61] 恶魔铠甲 (90%, 25%)
- [62] \***魔防破坏** (100%)

### 西部新坑道区

![西部新坑道区](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/050.png)

- [69] 轻飘飘法冠 (90%, 25%)
- [72] 力量腕套 (90%, 25%)
- [74] 称人结饰 (90%, 25%)
- [75] 玛瑙戒指 (90%, 25%)

### 第7总站衔接路

![第7总站衔接路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/051.png)

- [76] 浮雕皮带 (25%)

### 第7总站

![第7总站](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/052.png)

- 双子座召唤兽 **死亡天使札尔耶拉** (先杀小怪, 注意回复, 注意防各种异常状态，有神弓不难)
    - 给 **法兰**
- [77] 倒转的魔片 (100%)
- [78] 万灵药 (100%)
- 这里出去就到了 **加蓝赛兹水路** 东南角

## 加蓝赛兹水路

### 南部取水廊

- (M) 欧特洛斯 (弱火焰, 吃盲目, 催眠)
    - 上全女性角色队伍才会出现 (怎么爱好和我一样)

## 拉巴纳斯塔

- [闹区北部 席克族小偷] 完成委托: **欧特洛斯**
    - 获得 哈拉胡提的火焰
    - 获得 曛黑碎片
- [西门] 对话 **林札特**
- [外门前广场] 对话 **寇杰**
- [闹区北部] 对话 **诺顿**

## 西达玛斯卡沙漠

![西达玛斯卡沙漠](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/053.png)

- [!!] 风之方位轮

## 拉巴纳斯塔

- [西门] 对话 **林札特**，获得 **读风罗盘**

## 居扎草原 - 雨季

- 注意: 在主线剧情抵达 **戈利夫族村落佳哈拉** 前固定为雨季

### 往王都的大道

![往王都的大道](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/054.png)

- [!!] 枯萎的树木: 给予冲击

### 游牧民族聚落

![游牧民族聚落](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/055.png)

- [萨丁] 开始委托: **凯罗葛洛斯**
- [5] \***治疗** (100%)
- [!!] 枯萎的树木

### 基惹士河沿岸北侧

![基惹士河沿岸北侧](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/056.png)

- [!!] 枯萎的树木

### [W] 战士之河

![[W] 战士之河](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/057.png)

- (R) 雨中舞者 (每次进入20%概率出现)
- 1AC切出雨天，打一个雷之元素

### 托姆丘陵

![托姆丘陵](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/058.png)

- [!!] 枯萎的树木

### 流星原

![流星原](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/059.png)

- [!!] 枯萎的树木
- (M) 凯罗葛洛斯 (弱火焰)

### 幼小水晶的河畔

![幼小水晶的河畔](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/060.png)

- [!!] 枯萎的树木
- [娜瑙] 开始委托: **金钱龟**

### 巨兽足迹

![巨兽足迹](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/061.png)

- 反复进出直到协助NPC班沙特提示你金钱龟出现
- (M) 金钱龟 (弱雷电)
- (U) 爱之羽翼 (鸵鸡支线用，本流程没用)

### 幼小水晶的河畔

- 阅读 **潮湿的信**

### 游牧民族聚落

- [萨丁] 完成委托: **凯罗葛洛斯 (但是还有后续)**
- 之后一路向南，穿过 **欧兹莫内平原** 向西南来到 **戈利夫族村落佳哈拉**

## 戈利夫族村落佳哈拉

- 购买地图: 1730 gil
- 购买 \***解石**, \***中火焰**, \***逆治**: 4700 gil

### 古人山丘

![古人山丘](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/062.png)

- 主线剧情
    - 一路和人对话，最后和最长老乌博尔·卡对话，然后长过场
- [1] 雉鸡吊饰 (100%)
- [小长老苏古慕] 开始委托: **恩克多拉斯**
    - 和战士海森姆(桥的守卫)对话了解委托详情

## 欧兹莫内平原

### 豪罗绿地

![豪罗绿地](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/063.png)

- [31] 平行矢 (75%, 25%)

## 居扎草原

- 注意草原的季节变化
    - 从现在开始旱季和雨季开始交替
    - 1小时雨季2小时旱季循环(游戏内菜单右下角可以看到的那个时间)
    - 记下当前时间以方便之后快速判断季节 (本流程需要切一次雨季两次旱季)

### 在旱季时

- 对话 **长老波露诺雅** (**萨丁** 的 **凯罗葛洛斯** 讨伐后续)
    - 不影响奖杯
- [娜瑙] 完成委托: **金钱龟**
    - 获得 **福波斯的釉药**

### 在雨季时

- 萨丁 (凯罗葛洛斯讨伐收尾)
    - 不影响奖杯

### 碎裂谷

![碎裂谷](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/064.png)

- (M) 恩克多拉斯 (弱劲风)
    - 击杀所有敌人后1AC出现
- (R) 猛牛毛鳄 (击败恩克多拉斯后，每次进入有20%概率出现)
- (R) 耶亚洛斯 (击杀猛牛毛鳄后出现)

### 茂密之蛇

- 杀一个 **戈利夫族**，如果没出就2AC刷新

## 葛尔摩大森林

### 遮蔽光明之路

![遮蔽光明之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/065.png)

- (R) 米德加尔特巨蛇 (20%概率出现)
    - 可能出现在中路各处

## 叶露特村里

- 购买地图: 60 gil
- 购买 \***复原**, \***中雷电**, \***石化**: 6600 gil

### 指引之宫

![指引之宫](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/066.png)

- [3] \***急速** (100%)

## 戈利夫族村落佳哈拉

- [小长老苏古慕] 完成委托: **恩克多拉斯**
    - 拿到第三个 **金色护身符**

## 加蓝赛兹水路

- 记得击杀一只水之元素 (西部水量调整区、第10主水路和第11主水路出现，需要在 **加蓝赛兹水路** 里呆满10分钟才会出现)

### 中央控制区块

- 关闭 **第3区·水位控制装置**

### 第３处理区辅助水路

![第３处理区辅助水路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/067.png)

- 关闭 **水门**
- [44] 翡翠领圈 (100%)

### 中央控制区块

- 打开 **第3区·水位控制装置** 和 **第10区·水位控制装置**
- 关闭 **第4区·水位控制装置** 和 **第11区·水位控制装置**

### 第４处理区辅助水路

![第４处理区辅助水路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/068.png)

- 关闭 **水门**
- [47] \***阿基利斯** (100%)
- (R) 杜劳娜 (在水路里呆5分钟以上后, 每15s增加5%出现概率, 没出现就1AC刷一下)

### 中央控制区块

- 打开 **第11区·水位控制装置**
- 关闭 **第3区·水位控制装置**

### 第１处理区

- 天蝎座召唤兽 **不净王酋库雷因** (装备 **黑带**)
    - 给 **巴修**

### 中央控制区块

![中央控制区块](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/069.png)

- 推一下金牛座召唤兽前置
    - 打开所有水位控制装置
    - 关闭 **第11区·水位控制装置**
    - 关闭 **第4区·水位控制装置**
    - 打开 **第11区·水位控制装置**
    - 关闭 **第3区·水位控制装置**
    - 打开 **第4区·水位控制装置**
    - [小的!!] 拾取 **暗淡碎片**

## 欧兹莫内平原

- 主线剧情
    - 在大森林入口那个蓝水晶旁碰到士兵，给他们恢复剂，他们就会把陆行鸟借你
    - 出去左手就是去 **黑涅魔石矿** 的陆行鸟捷径 (很好找，多转一下就看到了)

## 黑涅魔石矿

### 第１期采掘现场

![第１期采掘现场](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/070.png)

- [13] \***肉斩骨断** (100%)
- 之后一路切换开关到达目的地，主线Boss没难度，打完看剧情

## 拉巴纳斯塔

- [沙海亭] 接受委托: **伊休坦**

## 戈利夫族村落佳哈拉

- [大长老札亚鲁] 开始委托: **伊休坦**

## 黑涅魔石矿

### 第１期坑道

- (M) 伊休坦 (在东南角拿地图的地方)

## 戈利夫族村落佳哈拉

- [大长老札亚鲁] 完成委托: **伊休坦**

## 拉巴纳斯塔

### 市区西部 牟斯鲁市集

- [公会商店] 购买 \***吸血**, \***高涨**: 8000 gil
- [公会商店] 购买三个 **钢铁护膝**: 3000 gil

## 葛尔摩大森林

### 叶声刺耳之路

![叶声刺耳之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/071.png)

- 刷两个  **骷髅头** (清理完敌人后就会爬黑暗骸骨, 心得书10%概率掉落)，不要卖掉
- (R) 戟刀领主 (黑暗骸骨Chain连锁数21以上出现)
- 先不去南边的幻妖森林

### 遥望广场

![遥望广场](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/075.png)

- [10] 格斗琥珀 (100%)

### 沉眠大树广场

![沉眠大树广场](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/076.png)

- [11] 9872 gil (100%)

### 枝叶开散之路

![枝叶开散之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/077.png)

- (R) 费罗 (20%概率出现)
- [14] 黑带 (80%, 30%)

### 沉于绿意之路

![沉于绿意之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/078.png)

- [17] 菱纹手环 (80%, 32.5%)
- 向东来到 **帕拉密纳大峡谷**

## 帕拉密纳大峡谷

- 一路向东北进入 **布尔欧密谢司**

## 布尔欧密谢司

- 购买地图: 3215 gil
- 购买两个 **称人结饰**: 2000 gil
- 购买 \***中暴雪**, \***狂暴**, \***中暗波**, \***齐疗伤**: 10100 gil

## 拉巴纳斯塔

- [沙海亭] 接受委托: **锐爪豹**
- [公会总部] 接受紧急委托: **捣蛋鬼**, **蚁狮怪**

## 飞空艇 (至 卜耶巴)

- 如果缺**传送石**的话，可以坐悠闲航班，然后在右侧商店购买

## 空中都市卜耶巴

- [史泰拉斯宅第 尼瑞] 开始委托: **蚁狮怪**

## 路苏魔石矿

### 第９矿区采掘场

![第９矿区采掘场](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/079.png)

- (M) 蚁狮怪 (弱劲风)
- [32] 靛蓝 (100%)
- [37] \***防御破坏** (100%)

## 空中都市卜耶巴

- [史泰拉斯宅第 尼瑞] 完成委托: **蚁狮怪**

## 布尔欧密谢司

### 白沙小路

- [席姆斯] 开始委托: **锐爪豹**
- [陆行鸟商嘉蒂] 开始委托: **捣蛋鬼**
- 推进主线: 进入神殿，长剧情

## 帕拉密纳大峡谷

- 差不多大家都开了3个魔雾技了，建议平时魔雾匣满了就放一下魔雾联手技，当做休闲也免得最后刷的时候太辛苦，可以出的联手技请看攻略末尾，最后记录一下自己出过哪些联手技了

### 结冰小溪

- 捣蛋鬼 (弱点会切换, 吃催眠, 沉默, 盲目)
    - 1AC反复切换直到莫尼提示捣蛋鬼出现
    - 这个Boss低于一定的血线会无敌+大陨石，不会打的话会比较吃力，有两种打法:
        - 到1/3血左右就用魔雾技秒掉，可以顺便刷刷全联手技，可以搓出的联手技请看攻略末尾
        - 一直催眠他，然后用吸血或者毒化(此时还买不到)这种不会惊醒他的魔法直接磨死
    - 获得奖杯: *【神射手】 已讨伐捣蛋鬼的证明。*
- 击杀一个冰之元素

### 卡瑞丹大冰河

![卡瑞丹大冰河](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/080.png)

- [47] \***致死一击** (100%)
- (R) 命符拥抱者 (击杀所有敌人)

### 冰龙之骨

![冰龙之骨](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/081.png)

- (M) 锐爪豹
- [27] \***苏生** (100%)

## 弥利亚姆遗迹

### 高风回廊

![高风回廊](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/082.png)

- [1] 碧玺戒指 (100%)
- [2] 碧玺戒指 (100%)
- [3] 战斗挽具 (100%)

### 英明回廊

![英明回廊](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/083.png)

- [4] 寒冰盾 (100%)
- 记下游戏时间，在这个迷宫里要待至少30分钟以刷出稀有怪 **尼葛穆尔**

### 对面守护

![对面守护](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/084.png)

- [5] ~65000 gil (5%, 5%)
- [6] 终极万灵药 (10%, 2.5%)
- [7] \***倒数** (100%)
- 如果打完迷宫还没到30分钟，可以刷刷[5], [6]这两个宝箱等 **尼葛穆尔**

### 剑王守护

- 击杀一个黑暗噩梦

### 远谋回廊

![远谋回廊](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/085.png)

- 主线: 旋转三个石像向中间
- [9] 红宝石戒指 (100%)

### 钢铁守护

![钢铁守护](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/086.png)

- [20] 贤者戒指 (100%)

### 剑王守护

![剑王守护](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/087.png)

- (R) 尼葛穆尔 (等待30分钟以后)
- 进入西边隐藏通道，记得先装备 **钢铁护膝**

### [隐藏区域] 离别步廊

![离别步廊](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/088.png)

- [8] 魔防壳盾 (100%) 对付亚兹马特用，务必要拿!
- (R) 原型炸弹 (油塔20%概率变异)

### 修练大厅

![修练大厅](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/089.png)

- 主线Boss: 双鱼座召唤兽 **背德皇帝玛提乌士** (弱雷电)
    - 给 **雅雪**
- [21] 万灵药 (100%)
- [22] 高涨的魔片 (100%)
- 主线: 获得 **霸王之剑**

## 布尔欧密谢司

### 白沙小路

- [席姆斯] 完成委托: **锐爪豹**
- [陆行鸟商嘉蒂] 完成委托: **捣蛋鬼**
    - 获得 **得摩斯的黏土**
- 购买 \***毒化**: 4000 gil
- 购买两个 **轻飘飘法冠**: 2400 gil
- 交易品: 骇人坛子
    - 卖出 **得摩斯的黏土**
    - 卖出 **哈拉胡提的火焰**
    - 卖出 **福波斯的釉药**
    - 现在不一定买得起，等以后买得起了再买，购买立即跳杯
        - 如果买不起的话，不要硬攒钱，而是有50000就去拉巴纳斯塔公会商店买 **猫耳风帽**，至少买满三个给后备队员装备上，很快钱就不愁了
    - 获得奖杯: *【圣杯】 已取得骇人坛子的证明。*

### 光明之室

- 主线看剧情
    - 获得奖杯: *【做梦的贤者】 从神都布尔欧密谢司启程的证明。*
    - 剧情结束后，对话门外的 **基迪亚教长老**，获得 **断罪魔石**

## 萨利卡树林

- 传送到 **疗愈回响之路**，向西北进入 **远古聚会庭园**
- 击杀Boss: 炸弹王 (弱水流, 吃沉默, 止动, 缓慢)
    - 这会开启通往死都的道路
- 西南方向是直接进入死都的，我们不走那边，先一路往北走到湿地

### 白色斑点之路

![白色斑点之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/090.png)

- [50] 坚钢帽 (75%, 25%)

## 拿普留士湿地

- 这里的敌人闪避率较高，可以装备 **浮雕皮带** 打

### 失去声音之路

- 对话 **玛克雷欧**: 选完所有对话选项 (金牛座召唤兽前置)

### 诱入梦乡的平原

![诱入梦乡的平原](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/091.png)

- [22] 马汀之衣 (75%, 25%)

### 蒙受激励之地

- 这个黄水晶是伪装的敌人，要小心
- 然后我们先传送回去接委托

## 拉巴纳斯塔

- [沙海亭] 接受委托: **沃帕兔**, **精神吸取者**, **血腥蝠**, **亚特蒙斯**, **罗比**, **播雷马**
- [公会总部] 接受紧急委托: **凯萝特**
- 接下来推一下金牛座召唤兽前置
    - [达朗的家] 对话 **洛肯莫**
    - [闹区南部] 对话 **菲洛**
    - [外门前广场] 对话 **想不起来的女子**
    - [牟斯鲁市集] 对话 **市场的商人(班葛族)** 询问到给出提示
    - [尤格里魔法店] 对话 **酒馆的帝国兵**
    - [闹区北部] 对话 **凯兹**
    - [闹区南部] 对话 **菲洛**
    - [尤格里魔法店] 对话 **酒馆的帝国兵**
    - [达朗的家] 对话 **洛肯莫**

## 叶露特村里

- [精灵居住的大树 妮菲莉亚] 开始委托: **沃帕兔**

## 葛尔摩大森林

### 叶声刺耳之路

![叶声刺耳之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/071.png)

- (M) 沃帕兔
    - 会乱跑，请他吃一个 **狂暴** 或者 **酒神之酒** 就老实了

## 叶露特村里

- [精灵居住的大树 妮菲莉亚] 完成委托: **沃帕兔**

## 戈利夫族村落佳哈拉

- [安祥大地 战士谷罗姆] 开始委托: **精神吸取者**

## 黑涅魔石矿

### 第１期采掘现场

![第１期采掘现场](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/070.png)

- 保持 \>90% MP
- (M) 精神吸取者

## 戈利夫族村落佳哈拉

- [安祥大地 战士谷罗姆] 完成委托: **精神吸取者**

## 那尔比纳城塞

- [贾基姆市集 布洛荷] 开始委托: **亚特蒙斯**
- [外郭西广场 摩根] 开始委托: **罗比**
- [飞空艇总站 萨玛德莉雅] 开始委托: **凯萝特**

## 莫斯佛拉山地

### 传出水声之处

- 购买 \***大劲风**: 5700 gil
- [行商瓦康萨] 开始委托: **播雷马**

### 北侧山麓

![北侧山麓](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/043.png)

- (M) 亚特蒙斯

## 东达玛斯卡沙漠

- [涅布拉河沿岸聚落南侧 381号囚犯] 开始委托: **血腥蝠**

## 柏尔海姆地下道

### 西部新坑道区

![西部新坑道区](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/050.png)

- (M) 血腥蝠

## 东达玛斯卡沙漠

- [涅布拉河沿岸聚落南侧 381号囚犯] 完成委托: **血腥蝠**

## 萨利卡树林

### 年轮层迭之路

![年轮层迭之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/092.png)

- (M) 播雷马 (弱暴雪)
- (R) 匿踪蛙 (20%概率出现)
    - 出现时是隐身的，注意观察，对己方任意带反射的角色扔一个魔法弹到他身上，才会现身和你战斗

## 拿普留士湿地

### 诱入梦乡的平原

![诱入梦乡的平原](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/091.png)

- 从西北的隐藏道路进入 **雾气蠢动之路**

### 雾气蠢动之路

![雾气蠢动之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/093.png)

- [25] 万灵药 (100%)
- [26] 4416 gil (100%)
- [27] Ｃ９Ｈ８Ｏ４ (100%)
- (R) 威列尔 (HP \< 20% 时出现)

### 俯瞰永恒的高台

- (M) 罗比 (弱水流)
    - 小心大量的骷髅敌人，想练级可以多呆一会儿

### 绝命的岸边

![绝命的岸边](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/094.png)

- [33] \***瞬移** (100%)
- [37] 蛋白石戒指 (25%)

### 灭亡王家的广场

![灭亡王家的广场](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/095.png)

- [42] 筒形外套 (75%, 27.5%)
- 装备 **钢铁护膝** 后进入死都(不然你会理解什么是连环爆炸)

## 死都拿普迪斯

- (R) 赫维涅克 (在死都内击杀6只超灵体后出现)

### 孕育力量回廊

![孕育力量回廊](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/096.png)

- [4] 力量绑带 (30%, 35%)
- [6] 翡翠领圈 (100%)

### 皓白承诺回廊

![皓白承诺回廊](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/097.png)

- [8] 巨人之盔 (30%, 35%)
- [12] \***信心** (100%)

### 崇高者之室

![崇高者之室](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/098.png)

- [18] 枪骑兵铠 (30%, 35%)
- [19] 碧玉礼袍 (30%, 35%)
- [20] 黑法袍 (100%)
- [26] \***勇气** (100%)
- [!!] 这里是隐藏商人，交互后出现
    - 购买满3个 **力量腕套**
    - 记住这个地方，之后还要来买东西

### 美妙旋律之室

![美妙旋律之室](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/099.png)

- [28] \***大物防护** (100%)
- [33] 西普诺斯之冠 (30%, 35%)
- [35] 白面具 (100%)

### 光芒四射回廊

![光芒四射回廊](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/100.png)

- [40] \***大沉默** (100%)
- [41] 赫米斯靴 (25%)
- [43] 脉轮头带 (30%, 35%)
- 从这头出去就到了萨利卡树林西南侧

## 萨利卡树林

- 不要击杀任何敌人

### 叶缝阳光之路

- 杀掉路上所有幸运兔以免被 **凯萝特** 当成了食粮
- (M) 凯萝特 (装备 **黑带**，可以给他上反射把回复魔法弹到我们身上)
    - 获得奖杯: *【花花公子】 已讨伐凯萝特的证明。*

## 莫斯佛拉山地

- [行商瓦康萨] 完成委托: **播雷马**

## 那尔比纳城塞

- [贾基姆市集 布洛荷] 完成委托: **亚特蒙斯**
- [外郭西广场 摩根] 完成委托: **罗比**
- [飞空艇总站 萨玛德莉雅] 完成委托: **凯萝特**

## 西达玛斯卡沙漠

### 中央断层

- 击杀一个精灵诺玛 (沙尘暴天气，热浪升起的平地也有，请务必此时击杀，不然打完大地龙就比较难刷出沙尘暴了)
- 然后向北到 **沙漠回廊** 再向东进入 **龙巢**

### 龙巢

- 击杀Boss: 大地龙 (弱劲风)
    - 可以从这里进入东沙漠北部了

## 萨利卡树林

### 树木夹缝

- 主线剧情: 找齐莫古后向东进入 **丰恩海岸**

## 丰恩海岸

### 波拉波拉沙地

![波拉波拉沙地](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/101.png)

- [24] 西阵织带 (70%, 25%)

### 茂列亚海岸

![茂列亚海岸](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/102.png)

- (R) 阿普萨拉斯 (杀死至少10只 **食人鱼** 后出现，**食人鱼** 在 **里希塔海岸** 和 **伐度海岸** 有，注意进入 **猎人营地** 会重置计数)
- 击杀一个 **班葛族**

### 乌阿福卡海角

![乌阿福卡海角](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/103.png)

- [38] 羔皮 (70%, 25%)

### 哈卡维岸边

![哈卡维岸边](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/104.png)

- [50] 魔法手套 (70%, 25%)

### 猎人营地

- 地图: 1800 gil
- 购买 \***混乱**, \***大火焰**: 8200 gil
- 可以补点药，尤其是多买点万能药备用
- 在北边坐着的人身旁拾取 **第11矿区的钥匙**

## 莫斯佛拉山地

### 传出水声之处

- 做一下天秤座召唤兽支线
- 对话 **研究员打扮的男子**
- 开启 **东北风祠堂**
- 开启 **东东风祠堂**
- 开启 **东南风祠堂**

### 灰白之檐

![灰白之檐](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/105.png)

- [20] \***状态复制** (100%)
- 给 **基沙尔蔬菜**，骑陆行鸟，上山穿行到 **传出水声之处** 西侧

### 传出水声之处

![传出水声之处](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/041.png)

- [25] 龟壳项圈 (100%)
- 开启 **西西风祠堂**
- 推下 **风化的岩石**
- [26] 6636 gil (100%)
- 开启 **西北风祠堂**
- 回到山上从中间往北

### 知悉天边的山脊

![知悉天边的山脊](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/106.png)

- [45] 驱魔的魔片 (100%)
- [46] 大反射的魔片 (100%)

### 苍蓝山顶

- 天秤座召唤兽 **审判灵树艾克斯迪司**
    - 死血时会物理免疫，用魔法打，注意他有永久反射，装 **蛋白石戒指**，或者给自己上反射后对自己放魔法
    - 给 **巴修**

## 丰恩海岸

### 开麻山丘

![开麻山丘](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/107.png)

- [78] 钢铁礼帽 (70%, 25%)
- [83] 反射铠甲 (70%, 25%) 这玩意儿如果顺到了也少穿，穿了加不上血

## 椎塔大草原

- 注意击杀一个席克族

### 欧利福札克山丘

![欧利福札克山丘](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/108.png)

- [27] \***大浮空** (100%)

### 无名泉

- 对话 **来自帝国的旅行者**
    - 获得 **封魂钥匙**

### 终焉与启程庭园

![终焉与启程庭园](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/109.png)

- (R) 塔拉斯各 (Chain连锁至少22只蛇怪)

### 三界交会的草原

![三界交会的草原](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/110.png)

- [56] \***大盲目** (100%)
- 给流浪的陆行鸟喂 **基沙尔蔬菜**，或者去 **丰恩海岸** **猎人的营地** 租陆行鸟，就可以在 **椎塔大草原** 最东端进入 **榭洛比台地**

## 榭洛比台地

- 在本区域要刷任何装备都请佩戴 **钻石手环** (但本攻略没有必要)

### 艾尔亚尼斯旧大道

![艾尔亚尼斯旧大道](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/111.png)

- [101] \***远距攻击** (100%)
- [!!] 装备 **支棱**，可以在此处看到彩蛋

### 北部阶丘

![北部阶丘](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/112.png)

- (R) 异冻 (杀光敌人后出现)

### 河岸阶丘

![河岸阶丘](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/113.png)

- 击杀一个精灵温迪努(雨天出现，1AC刷新天气)
- [36] \***重启** (20%)

## 巴冯海姆

- 购买地图: 4180 gil
- 这里的商人可以购买 **传送石** 了

## 索亨地下宫殿

- 卸下 **钻石手环**
- 推进主线，钥匙开门

### 面对亮暗大厅

- 主线Boss: 蔬菜人们

## 索亨地下宫殿

### 修道者歇息场所

- 4936 gil (100%)
- 大急速的魔片 (100%)

### 寻找自我之路

![寻找自我之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/130.png)

- [19] 冲击的魔片 (100%)

### 时光水洞

![时光水洞解谜](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/115.png)

- 上图为解谜走法

![时光水洞](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/114.png)

- [28] 樱啭 (100%)
- [29] \***千根针** (100%)

### 寻找自我之路

![寻找自我之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/130.png)

- [23] 终极万灵药 (100%)

### 时光水洞

- 东北方向抵达 **接受宿命之路** 的东端

### 接受宿命之路

![接受宿命之路解谜](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/116.png)

- 上图为解谜走法

### 面对暗光大厅

- 主线Boss
- 5个100%出现的宝箱

### 摆脱诱惑之路

- (R) 卡部斯 (进入本区域时25%概率同时出现雪怪和深狱炼魔，全灭他们后出现)

## 阿凯迪斯旧城区

### 隙缝风小巷

- 主线: 对话 **情报贩子裘尔**，然后和所有人对话掌握情报和回去再找他，按照他的提示找人再对话，就可以进入帝都了

## 帝都阿凯迪斯

- [布渥德招式店] 购买地图: 3530 gil
- [查里洛特魔法店] 购买 \***大雷电**: 7000 gil
- [查里洛特魔法店] 对话 **茱莉** (这个剧情只有之前在那尔比纳城塞用陆行鸟进入莫斯佛拉山地才会触发)
- [查里洛特魔法店] 对话 **洛肯穆** (金牛座召唤兽前置)
- [古兰修道具店 公告板] 接受委托: **黑暗钢龟**
- 多买点至高治疗剂: 520 gil (为大战召唤兽 **泽罗姆斯** 做准备)
- [温特武器·防具店 想回故乡的男子] 开始委托: **黑暗钢龟**

### 迎风小巷

- 对话 **政民奥托** (金牛座召唤兽前置)

## 索亨地下宫殿

### 摆脱诱惑之路

- (M) 黑暗钢龟

## 弥利亚姆遗迹

- 在传送台上使用 **断罪魔石**
- 巨蟹座召唤兽 **断罪暴君泽罗姆斯** (提前上好buff, 装备 **力量腕套**, 小怪多可以用魔雾技清场)
    - 给 **法兰**

## 帝都阿凯迪斯

- [查里洛特魔法店] 对话 **洛肯穆** (金牛座召唤兽前置)
- [温特武器·防具店 想回故乡的男子] 完成委托: **黑暗钢龟**
- 然后开始主线的配对小游戏，必须把28个叶章都拿了才能进入帝都的上层(涉及全地图访问奖杯)，下面是连线列表

### 尼尔巴斯区

- 声援的研究员 (店门口) - 失败的研究员 (中央)
- 不知如何说明的绅士 (中央) - 蓝钻的妇人 (西)
- 喜好运动的妇人 (中央) - 喜好读书的研究员 (在店门口奔跑)
- 关注的绅士 (中央) - 兜售的男子 (商店东边)
- 想改变气氛的妇人 (东北) - 退休的妇人 (东北)
- 下定决心的研究员 (东南) - 原为研究员的绅士 (中央)

### 利安纳区

- 美食研究家 (西) - 不擅做菜的妇人 (作战布局店)
- 塔罗牌的女子 (作战布局店东) - 撰写幸福小说的女子 (作战布局店东)
- 布局的绅士 (东南) - 收到卡片的妇人 (西)
- 为进货而开心的绅士 (西南) - 等候进货的妇人 (东南)
- 旅游团的女子 (最东南端) - 卜耶巴的妇人 (东南)
- 销售蔬菜的女子 (最东南端) - 销售蔬菜的男子 (西南)
- 捡到信件的绅士 (招式店) - 浪漫的妇人 (东南)

### 托朗特区

- 知悉历史的老人 (东) - 想了解历史的绅士 (西南)
- 单恋的绅士 (西南) - 单恋的妇人 (东南)
- 大楼的绅士 (南) - 造型奇怪的绅士 (西南)
- 鲁特琴的女子 (北) - 鲁特琴手 (西南)
- 服饰店的妇人 (西北) - 金钱过剩的绅士 (东北)
- 卖票的母亲 (西北) - 卖票的女孩 (东南)

### 穆尔别瑞区

- 喜好旅行的妇人 (东南) - 旅行生活的绅士 (最西北端)
- 掉眼泪的妇人 (最西北端) - 关心家人的女孩 (南)
- 戴首饰的男子 (东南/中央) - 戴首饰的女子 (东南)
- 家庭教师的妇人 (东北) - 家庭教师的绅士 (东北)
- 想要羽毛的女子 (魔法商店) - 想要羽毛的男子 (西北)
- 配件的妇人 (西北) - 居札的男子 (西北)
- 想成为审判者的男子 (西北) - 审判者的夫人 (中央)
- 魔道士的女子 (南/中央) - 学院的绅士 (西北)
- 长相酷似的男子 (西北) - 长相酷似的男子 (魔法商店)
- 随便找个商店就可以把28个叶章换成黑羽章

### 尼尔巴斯区

- 主线: 前往 **杰诺博区**

### 杰诺博区

- 主线: 剧情后前往 **老地方**

## 卓克罗尔研究所

- 一路切换红蓝墙上到70层 (切换解谜多尝试几次就行了，不难)

### 第70阶层

![第70阶层](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/117.png)

- [12] \***丢钱** (100%)  错过也没关系，后面有地方补

### 能源输送设施

- 主线Boss
    - 场地内有 **神圣的魔片** 和 **大急速的魔片**
    - 获得奖杯: *【与黑影交谈的男子】 和希德博士见过面的证明。*

## 港都巴冯海姆

- 注意逛一下各个区域(主要是白波亭那块最北边的区域以及飞空艇总站前的区域)，奖杯要用

### 白波亭

- 接受委托: **威拉尔**, **林德沃姆**, **无头魔人**, **歌利亚**, **夺命镰刀**
- [维埃拉族旅人] 开始委托: **威拉尔**

### 葛拉利纳市场

- 购买 \***大疗伤**, \***大暴雪**, \***大缓慢**, \***大暗波**: 29500 gil

## 那尔比纳城塞

- [贾基姆市集 波波尔] 开始委托: **夺命镰刀**
- [外郭西广场 巴隆格] 开始委托: **歌利亚**

## 帝都阿凯迪斯

- [布渥德招式店 想红的席克族人] 开始委托: **无头魔人**
- [迎风小巷 福尔蒙] 开始委托: **林德沃姆**

## 拉巴纳斯塔

- [公会总部] 接受紧急委托: **吉尔伽美什**, **比利士**

## 丰恩海岸

- 杀一个风之元素 (在 **波拉波拉沙地** 或者 **利玛特拉山丘**，需要下雨天，如果是晴天，需要从萨利卡树林或者椎塔大草原进出来刷出天气，阴天和下雨天之间可以1AC刷新)

### 猎人营地

- 对话 **头子**
    - 开启珍稀讨伐，我们先要去打一个热身珍稀怪(不算在30个珍稀讨伐里)

### 伐度海岸

![伐度海岸](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/118.png)

- 沿海有16个不可再生的宝箱，一路爽摸
- (T) 翡尼连斯 (在崖上东边尽头呆10秒，就会出现在海岸边)

### 猎人营地

- 对话 **头子**
    - 正式启动稀有狩猎讨伐，不算上面已经讨伐的 **翡尼连斯**，一共有30个稀有敌人要讨伐
    - 狩猎支线任务里的30个稀有怪的偷盗道具都是稀有唯一，也就是不会像其他敌人会偷到你不想要的非稀有道具，所以对于需要刷某些素材的玩家来说往往是最好的获取途径，只是本攻略也就要偷3个狮子座而已

### 提亚劳努海角

![提亚劳努海角](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/119.png)

- (T) 骷髅灰 (40%概率出现，也可能出现在山崖上)

## 榭洛比台地

### 交叉平原

![交叉平原](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/120.png)

- (T) 蓝血人 (40%概率出现)

### 费迪克河

![费迪克河](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/134.png)

- (T) 巨岛龟 (40%概率出现)

### 北部阶丘

![北部阶丘](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/112.png)

- (M) 威拉尔 (弱劲风)

## 港都巴冯海姆

- [白波亭 维埃拉族旅人] 完成委托: **威拉尔**
    - 获得 **龙鳞**

## 榭洛比台地

- 交互: 风车10号机
    - 给老人看 **龙鳞**
- 步行前往椎塔大草原

## 椎塔大草原

- 反复进出刷出阴天或者雨天
- 击杀一个土之元素 (**远古意念沉眠之地** 或 **崩裂的大地**，阴天出现，可以1AC刷新阴和雨)

### 瓦兹库夫丘陵

- (T) 格瑞玛钦 (夸尔10%概率变异)

### 看清一切之地

- (T) 克莉丝 (40%概率出现在地图上的左右两个建筑群周围)

### 终焉与启程庭园

- 1AC刷出阴天后委托怪才会出现
- (M) 林德沃姆 (弱劲风)

## 索亨地下宫殿

- [舍弃迷惘之路] (M) 无头魔人 (弱水流)

## 帝都阿凯迪斯

- [迎风小巷 福尔蒙] 完成委托: **林德沃姆**
- [布渥德招式店 想红的席克族人] 完成委托: **无头魔人**
- 购买 \***暗黑**: 6000 gil

## 萨利卡树林

### 白色斑点之路

![白色斑点之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/090.png)

- (T) 狂怒厉爪 (等60s, 没有发生击杀或捕食)

## 拿普留士湿地

- [失去声音之路] 剧情: 恩莫族人齐聚一堂
- [俯瞰永恒的高台] 祠堂剧情，获得 **无力的力量徽章**

### 诱入梦乡的平原

![诱入梦乡的平原](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/091.png)

- 击杀一个精灵琉司阿尔伏(雾天出现，可1AC刷新天气)
- (T) 阿黎约客 (40%概率出现)

## 死都拿普迪斯

### 孕育力量回廊

![孕育力量回廊](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/096.png)

- (M) 歌利亚 (弱暗)

### 皓白承诺回廊

![皓白承诺回廊](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/097.png)

- (T) 沃瑞斯
    - 这张地图有20%概率会出现 **暗之元素**
    - 用魔法激怒 **暗之元素**, 但不要击杀他, 引诱他通过(T)标志上下的两个小路口，沃瑞斯就会出现
- 交互 **厌恶之门**，进入Boss房间
- 击杀Boss **怒精** (弱水流, 装备 **力量腕套**, 吃 **缓慢**, **沉默**, **驱魔**)
    - 房间里有个金斧

### 崇高者之室

![崇高者之室](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/098.png)

- (M) 夺命镰刀 (HP \<10% 出现, 弱神圣)

### 美妙旋律之室

- 交互 **恐惧之门**，进入Boss房间
- 击杀Boss **冯巴巴头目** (弱神圣, 装备 **黑带**, 吃 **缓慢**, **沉默**)
    - 房间里有个崩炮的魔片

### 崇高者之室

- 交互 **绝望之门**，进入Boss房间
- 金牛座召唤兽 **轮回王卡奥斯**
    - 装备 **黑带** + **玫瑰胸饰**, 装备防风
    - 吃 **缓慢**
    - **驱魔**, **魔防破坏**, **防御破坏**, **毒化**, **暗黑** / **随机魔法** / **丢钱** (成本比较高，钱少不要用这个)
    - 如果感觉太难打不过，可以等后面买了 **倒转** 再来打，就是要多跑一趟
    - 注意一定要上了缓慢再打，复活队友要及时
    - 给 **潘妮萝**
    - 房间里有个 **终极万灵药**

## 那尔比纳城塞

- [外郭西广场 巴隆格] 完成委托: **歌利亚**
- [贾基姆市集 波波尔] 完成委托: **夺命镰刀**

## 弥利亚姆遗迹

- [对面守护] (T) 迈思 (击杀所有硬壳龙然后1AC出现)
    - 看下身上 **狮子座** 的数量，不足3个就偷满3个 (2AC刷新可以再偷)

## 拉巴纳斯塔

- [公会商店] \***倒转**, \***吸魔**: 10800 gil
- 交易品受诅咒的首饰，需要卖出:
    - 3个 **染血首饰**
    - 2个 **骷髅头**
    - 3个 **狮子座**
- 于是鲸齿吊坠入手
    - 可以玩逆转万能药了(也就是有3级万能药知识的角色装备 **鲸齿吊坠** 后给敌人扔一个万能药，于是挂上一排异常)，之后大多数的珍稀讨伐怪都吃逆转万能药，可以大大降低难度
    - 装备 **鲸齿吊坠** 的角色给队友用酒神之酒可以解除某些敌人附加的狂战士状态
    - 注意: 装备 **鲸齿吊坠** 的角色不要给队友乱用药

## 考验模式

- 打到50层
    - 遇到有利状态的Boss先给驱魔魔法或者驱魔的魔片 (之后的Boss都要这样处理，不再复述，注意驱魔的魔片要很后面才能购买，尽量用魔法)
    - 遇到不太好打的都可以上逆转万能药
    - 49层偷取 **缎带**
    - 50层偷取 **德罗之剑** (对付弱圣的敌人用，永久勇气和信心)
    - 注意装上 **盗贼之袖** 偷，没偷到就退回标题画面选 **TRIALS** 读取自动存档重来
    - 获得奖杯: *【最高审判者】 已通过考验模式50关卡的证明。*
- 再往后以现在的强度打起来会比较吃力，我们直接读取考验模式51层保存的存档继续玩主游戏。
    - 如果你不差时间，也可以再存一个存档后重新从第一层打起，重复以上流程摸3个 **缎带**，但这个时间成本总得来说不划算，毕竟后面流程里还有三个的缎带可以拿

## 居扎草原 - 雨季

- 居扎草原雨季和旱季各有一个稀有敌人，请自己根据当前游戏时间安排击杀时机

### 托姆丘陵

- 击杀一个 **精灵玛尔特** (暴雨才会出现，1AC刷出天气)

## 居扎草原 - 旱季

### 流星原

![流星原](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/133.png)

- (T) 纳查尼尔 (40%概率出现)

## 大沙海那姆·焉萨

### 风化的岸边

![风化的岸边](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/023.png)

- (M) 比利士 (弱水流)

### 黄沙抵达之地

![黄沙抵达之地](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/121.png)

- (T) 维克多 (40%概率出现)

## 大沙海奥格·焉萨

![大沙海奥格·焉萨](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/122.png)

- [南侧油槽通道] (T) 陆行鸟首领 (40%概率出现)
- [大型油槽基地 或 中央结点] 击杀一个 **精灵色拉曼多** (晴天出现，沙漠只有晴和阴两种天气，但需要切换大地图来刷)

## 路苏魔石矿

- 击杀一个凝视魔 (在苏尼亚平行桥/第2矿区采掘场/第３矿区采掘场呆7分钟后出现在队伍身旁, 建议在第3矿区采掘场等，因为其他区域出现时自带隐身状态，还要用魔法打自己反射才能让他现身)

### 它薛桥

- (M) 吉尔伽美什
    - 先杀安托奇
    - 源氏之盾 (HP 20-40% 盗取)
    - 源氏前臂 (HP \<20% 盗取)

- 用钥匙开门进入第11矿区采掘场

### 第11矿区采掘场

![第11矿区采掘场](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/123.png)

- (R) 宝石角 (杀光地图上的敌人，注意西南和西北角各有一个拟态宝箱)
- [43] 黄金牧师帽 (100%)
- [44] 治疗高顶盔 (100%)

### 拉薛桥

![拉薛桥](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/124.png)

- (R) 炮弹怪 (20%概率出现)

### 第５矿区采掘场

![第５矿区采掘场](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/125.png)

- [52] 加西莫多靴 (25%)
- [55] 光之圣袍 (100%)
- (T) 狄支玛 (黑暗领主5%概率变异, 很强, **驱魔**, 装备 **力量腕套**, 可以 **倒转** 打)

### 第６矿区北采掘场

![第６矿区北采掘场](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/126.png)

- [64] 马克西米连式铠甲 (100%)

### 第６矿区南采掘场

![第６矿区南采掘场](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/127.png)

- [59] 魔力骑兵盔 (100%)
- [63] 盖尔米那斯长靴 (25%)

### 作业准备区

![作业准备区](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/128.png)

- [66] \***崩炮** (100%)

### 第７矿区采掘场

- 吉尔伽美什
    - 倒转后没什么难度
    - 驱魔后优先杀安奇托 (逆转万能药)
    - 二阶段防催眠，三阶段防止动，四阶段防石化
    - 源氏之盔 (HP 20-40%HP 时盗取)
    - 源氏之铠 (HP \<20% 时盗取)
    - 获得奖杯: *【阿修罗之剑】 已讨伐吉尔伽美什的证明。*
- 正宗 (100%)

## 索亨地下宫殿

### 接受宿命之路

![接受宿命之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/129.png)

- (T) 魔雪怪 (进入本区域后在5分钟内击杀4只雪怪后出现)

### 寻找自我之路

![寻找自我之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/130.png)

- (T) 阿努比斯 (进入中间隐藏房间)

### 面对怒神大厅

![面对怒神大厅](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/131.png)

- 从 **接受宿命之路** 然后向西进入隐藏通道，用破烂钥匙开门打 **魔神龙**
    - 弱神圣, 弱火焰
    - 装备 **力量腕套**, **缎带**
    - **力量破坏**, **防御破坏**
    - 获得奖杯: *【闪亮救星】 已讨伐魔神龙的证明。*
- [48] 倒转的魔片 (100%)
- [49] 大急速的魔片 (100%)
- [50] 高涨的魔片 (100%)

## 拉巴纳斯塔

### [公会总部 蒙布朗] 完成委托: **吉尔伽美什**

## 加蓝赛兹水路

### 第10主水路

![第10主水路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/132.png)

- (T) 长吻毛鳄 (在这个位置等待15秒)

## 东达玛斯卡沙漠

### 断裂沙地

![断裂沙地](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/039.png)

- (T) 骇爪 (狂暴恐龙40%概率变异)

## 柏尔海姆地下道

### 洁拜亚连结桥

![洁拜亚连结桥](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/049.png)

- (T) 依叙汀 (每10秒提升2%出现概率，一直等就行)

## 西达玛斯卡沙漠

### 热浪升起的平地

![热浪升起的平地](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/014.png)

- (R) 迅狼 (击杀20只以上野狼后出现)

### 沙漠回廊

![沙漠回廊](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/135.png)

- (T) 皇帝狼 (击杀迅狼后40%概率出现)
- (R) 尘魔 (HP \<10% 出现) 因为凤凰尾巴可以秒他，其实在很多攻略里初期是拿他练级的，我们的流程因为有神弓就没必要练了

## 瑞斯沃尔王墓

- 这里往后，写着(游戏内时间分钟)的稀有敌人，冒号后面的数字就是表示分钟数，游戏内菜单右下角就能看到时间。
- 请根据你的当前游戏时间来安排之后几个稀有怪的猎杀顺序 (一共5个，搜索 “**游戏内时间分钟**”)

### 北翼通廊

![北翼通廊](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/029.png)

- (T) 僵尸领主 (游戏内时间分钟 :00 到 :29)

## 莫斯佛拉山地

### 通往天空之路

![通往天空之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/136.png)

- (R) 森林蝮蛇 (游戏内时间分钟 :10 到 :19)

### 知悉天边的山脊

![知悉天边的山脊](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/106.png)

- (T) 狄多 (40% 概率出现)

## 欧兹莫内平原

- [随风飘扬的草原 或 豪罗绿地] 击杀一个 **精灵西尔芙斯** (阴天出现，可以在大森林和平原之间进出刷天气)

### 大地螺旋

![大地螺旋](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/137.png)

- (T) 杀戮虫 (游戏内时间分钟 :10 到 :39，是一个拟态宝箱)

## 葛尔摩大森林

### 指针紊乱之路

![指针紊乱之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/138.png)

- (T) 钢壳快刀手 (游戏内时间分钟 :30 到 :59)
- 往南穿过 **叶声刺耳之路** 进入 **幻妖森林**

## 幻妖森林

### 迷惑现实之路

![迷惑现实之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/072.png)

- (R) 隐密兔 (击杀六只以上的地狱守门犬和所有塔尔塔罗斯, 20%几率出现)
- 击杀一个圣之元素
- 往南再往西可以进入 **黑涅魔石矿** 东边的角落，其实我们这个流程不需要 **贤者戒指**，不去也没关系

## 黑涅魔石矿

### 第２期坑道

![第２期坑道](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/073.png)

- [41] 贤者戒指 (25%)
- [42] 大劲风的魔片 (100%)

## 幻妖森林

- 小地图是扭曲形态，但是我们按下L3依然可以看正常的小地图

### 古代终焉之处

![古代终焉之处](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/074.png)

- [33] 雏鸟披肩 (25%)  为了后面练级，一定要刷出来

### 黑影舞动之路

![黑影舞动之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/139.png)

- (T) 惊骇守卫 (魔镜骑士40%概率变异，没出就2AC刷新吧)

### 飘香花朵庭园

![飘香花朵庭园](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/140.png)

- 主线Boss: 大王花 (弱劲风)
- [34] 小镇的苹果白兰地 (100%)
- [35] 至高治疗剂 (100%)

### 白魔钟爱之路

![白魔钟爱之路](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/141.png)

- (R) 加葛诺特 (游戏内时间分钟 :00 到 :10)
- [39] \***大驱魔** (100%)
- [43] 金色护身符 (100%)  这个时候基本没用了，除非你早点过来拿

### 睿智冰原

![睿智冰原](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/142.png)

- [49] 高涨腰链 (100%)
- 解谜: 在圆形建筑内注视纹章，然后视角旋转找出会浮现出图画的方向走

### 思绪的尽头

![思绪的尽头](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/143.png)

- [63] \***大反射** (100%)
- 解谜: 叫出 **白羊座·贝利亚斯** 召唤兽就可以开门 (注意要先解纹章的谜抵达开门处并交互一下门)

## 基鲁菲冈

### 水之门

- 主线Boss: 代达洛斯 (弱神圣)

### 水层都市特里玛拉

![水层都市特里玛拉](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/144.png)

- 注意打一个精灵德克阿尔伏 (也会出现在水层都市澳达)
- [2] 腰带 (100%)
- [U] 地图要等打完水晶迷宫的主线Boss回来才会出现
- [!!] 隐藏道路

### 水层都市澳达

![水层都市澳达](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/145.png)

- [7] 神盾 (100%)
- [!!] 隐藏道路

### 水层都市浩米卡

![水层都市浩米卡](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/146.png)

- [9] \***大催眠** (100%)

### 火之门

![火之门](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/147.png)

- [10] 小镇的苹果白兰地 (100%)
- [11] 万灵药 (100%)
- [12] 格斗琥珀 (100%)
- [!!] 隐藏道路
- 主线Boss: 专制暴君 (弱冰)

## 水晶巨界

### 地图全览

![地图全览1](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/156.png)
![地图全览2](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/157.png)

- 地图标识:
    - 罗马数字是传送门
    - 英文单词和字母是十二星座的控制装置和闸门(首字母对应装置)，触摸控制装置后可以解锁对应的闸门(下层触摸装置后就可以解锁，上层则需要触摸装置后再去触摸对应的闸门才能解锁，部分星座还有限时)
- 我们先往下走打主线Boss

### 石炭纪

![石炭纪](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/148.png)

- [2] 盗贼之帽 (100%)
- 触摸 VII 传送到 VI

### 二迭纪

![二迭纪](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/149.png)

- [4] 黄金头饰 (100%)
- 触摸 V 传送到 IV

### 三迭纪

![三迭纪](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/150.png)

- [5] 忍者衣 (100%)
- [6] 大地之衣 (100%)
- 触摸 **双鱼座(Pisces)** 解锁通过 P，或者触摸 **白羊座(Aries)** 解锁通过 A
- 触摸 III 传送到 II
- 触摸 I 传送到 **风之门**

## 基鲁菲冈

### 风之门

![风之门](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/158.png)

- [13] 大急速的魔片 (100%)
- [14] 倒转的魔片 (100%)
- 主线Boss: 人马座召唤兽 **密告者休米哈查** (主线召唤兽都随便打)
    - 给 **巴夫雷尔**
    - 触摸南端的传送装置，获取 **契约之剑**
- 注意: 不要传送，我们原路返回探索一下 **水晶巨界**

## 水晶巨界

### 石炭纪

![石炭纪](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/148.png)

- 触摸 **天蝎座(Scorpio)** 解锁通过 S
- 触摸 IX 传送到 X

### 泥盆纪

![泥盆纪](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/151.png)

- (T) 水晶骑士 (从 XX 出发，向东南顺时针或者向西南逆时针转一圈回到原地后出现)
- 触摸 **射手座(Sagittarius)** 解锁通过 S1
- 触摸 XI 传送到 XIII

### 志留纪

![志留纪](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/152.png)

- [11] 贤者之杖 (25%)
- 触摸 **双子座(Gemini)** 解锁通过 G1
- [13] 橡胶紧身衣 (100%)
- 触摸 **双子座(Gemini)** 解锁 G2
- 回头走 XIII 传送到 XI

### 泥盆纪

![泥盆纪](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/151.png)

- 触摸 **射手座(Sagittarius)** 解锁通过 S2
- 触摸 XII 传送到 XIV

### 志留纪

![志留纪](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/152.png)

- 触摸 **狮子座(Leo)** 解锁通过 L1
- [15] \***大魔防壳** (100%)
- [XIV] (R) 拉尔拔吞噬者 (弱神圣)
    - 杀256个敌人后出现，觉得太难可以等下一次来的时候再打
    - 各个传送点周围地图会大量刷死灵类的敌人，刷256个敌人其实很简单
- [17] 桂冠 (100%)
- 触摸 **狮子座(Leo)** 解锁通过 L2
- 触摸 XV 传送到 XVI

### 奥陶纪

![奥陶纪](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/153.png)

- 触摸 **天秤座(Libra)** 解锁通过 L1
- [21] 守护戒指 (100%)
- 触摸 **摩羯座(Capricorn)** 解锁通过 C1
- 触摸 **处女座(Virgo)** 解锁 V1
- 触摸 **天秤座(Libra)** 解锁 L2
- 触摸 XVII 传送到 XVIII

### 寒武纪

![寒武纪](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/154.png)

- (R) 恶灵 (禁忌生命5%概率变异)
    - 要是等级低打不过可以等下一次来的时候再打
- 处女座召唤兽 **圣天使雅尔提玛** (弱暗波, 装备 **缎带**, 装备防神圣)
    - 获得奖杯: *【堕天使】 已讨伐雅尔提玛的证明。*
    - 给 **梵恩**
- [27] 石中剑 (100%)
- [28] 尖峰 (1%, 4%)
    - 这里介绍一个简单获取方法，已经对PS5主机上初始化随机数的变化进行了改进，我录了视频，地址在攻略开头 (仅适用于PS4版本; PC版请自行研究RNG工具，或者直接打mod; Switch版最难拿，请自行搜索视频攻略):
        - 只上阵一个会回复魔法的角色，关闭作战布局，卸掉武器保留防具(因为后面要打自己，别把自己打死了)，装备 **钻石手环**
        - 在 **雅尔提玛** 前的蓝水晶房间留一个存档后完全关掉游戏重开并读取存档
        - 如果是PS5主机的话就先砍自己4刀(PS4主机不用)
        - 然后给自己回复5次
        - 接着反复进地图直到刷出宝箱(一般15次之内可出，没出退游戏重来)
        - 一直砍自己直到出现连击，开宝箱得到852G
        - 再进出4次地图，宝箱出现，必得 **尖峰**
    - 建议至少刷一个给T用
- 触摸 **宝瓶座(Aquarius)**
- 触摸 XVIII 传送到 XVII

### 奥陶纪

![奥陶纪](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/153.png)

- 解锁通过 A1
- 触摸 **摩羯座(Capricorn)** 解锁通过 C2
- 触摸 **金牛座(Taurus)** 解锁通过 T2
- [23] \***大急速** (100%)
- 触摸 **金牛座(Taurus)** 解锁通过 T1
- [25] 狩神弓 (100%)
- 我们不走 XXI，那边要游戏最后再来
- 触摸 XVII 传送到 XVII

### 寒武纪

![寒武纪](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/154.png)

- 触摸 XIX 传送到 XX

### 泥盆纪

![泥盆纪](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/151.png)

- 触摸 X 传送到 IX

### 石炭纪

![石炭纪](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/148.png)

- 触摸 VIII 传送到 **火之门**
- 之后原路返回基鲁菲冈入口

## 港都巴冯海姆

- 购买 \***大复活**, \***冲击**, \***大重力**: 21600 gil
- 购买 \***步数攻击**: 4800 gil
- 继续推进主线

## 黎铎亚纳大瀑布

### 悠久时光庭园

![悠久时光庭园](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/159.png)

- [2] 教士礼袍 (75%, 25%)
- [8] 祭司之帽 (75%, 25%)
- (T) 阿贝利斯克 (30%概率出现)

### 竞技场

![竞技场](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/160.png)

- [14] 神圣长枪 (75%, 25%)

### 邃古都市

![邃古都市](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/161.png)

- [20] 雉鸡吊饰 (100%)
- [25] 雕花长靴 (100%)
- (R) 帕尔 (杀光敌人后1AC出现)

## 大灯塔下层

### 满足渴望的广场

![满足渴望的广场](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/162.png)

- 主线Boss: 骸多龙 (弱神圣)
- [1] 狂战士 (25%)
- [2] 中疗伤的魔片 (75%)
- [3] 红宝石戒指 (100%)
- [4] 高涨的魔片 (75%)

### 始原之层 外围

![始原之层 外围](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/167.png)

- 外围敌人掉落的黑珠子能拾取的尽量拾取，主线需要3个，后面地下需要168个
- [10] 赫米斯靴 (100%)

### 吹拂异风的迷途沙丘

- 主线Boss: 群魔殿 (弱劲风)

### 始原旋廊１

![始原旋廊１](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/168.png)

- [16] 恶魔之盾 (100%)
- [19] 龙头盔 (100%)
- 至少击杀10个大太法师(不要用快速存档读取的方式刷新，用2AC)

### 始原旋廊２

![始原旋廊２](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/169.png)

- [23] 长兜帽 (100%)

### 始原旋廊３

![始原旋廊３](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/170.png)

- [29] 奥汀神枪 (100%)
- [30] \***神圣** (100%)

### 始原旋廊４

![始原旋廊４](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/171.png)

- [31] 崩炮的魔片 (100%)
- [32] 万灵药 (100%)
- [47层] (R) 毗湿奴 (击杀至少10大太法师后出现)

### 至次境域

![至次境域](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/172.png)

- [35] 大反射的魔片 (100%)
- [36] 黑面具 (100%)
- 主线Boss切菜

## 大灯塔中层

### 奉献夹缝

- 选择解除东南门的封印(封知的祭坛，会封印小地图，但是我们按下L3依然可以看正常的小地图)

### 封杀之层

![封杀之层](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/173.png)

- [2] 蛋白石戒指 (100%)
- [4] 加西莫多靴 (100%)
- [9] 密涅娃马甲 (100%)

### 受难之层

![受难之层](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/174.png)

- [10] 宙斯锤矛 (100%)
- [16] 腹弩S (100%)

### 幻惑之层

![幻惑之层](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/175.png)

- [17] 巨龙铠甲 (100%)
- [20] \***丢钱** (100%)  只有当你没摸卓克罗尔研究所的时才会出现，算是官方补救措施，防止你错过奖杯
- [23] 腰带 (100%)
- (T) 复仇者 (40%概率出现，比较强，可以逆转打)

### 验真封域

![验真封域](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/177.png)

- [27] 村正 (100%)
- [28] 大急速的魔片 (100%)

### 吹拂异风的白色斗场

- 主线Boss，战斗时可以摸到的宝箱
    - 中疗伤的魔片
    - 至高治疗剂
    - 凤凰尾巴
    - 万灵药

### 验真封域

- 摸 **封知祭坛** 恢复小地图功能
- 坐电梯上到67F

## 大灯塔上层

### 至顶旋廊１

![至顶旋廊１](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/178.png)

- [可选] 连续摸两次 **绿之纹章** 进入陷阱地图，可以获取地图
- 摸 **黑之纹章**
- [3] \***火光** (100%)
- [可选] 摸非隐藏区域的 **绿之纹章** 两次可以完成开全图
- [东南隐藏区域] 摸 **绿之纹章**

### 至顶旋廊２

![至顶旋廊２](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/179.png)

- [6] \***闪热** (100%)
- [7] 白法袍 (100%)
- 摸 **赤之纹章**
- [8] 究极之刃 (100%)
- 摸 **供之纹章**
- 西北打破隐藏墙摸 **转移装置**
- [11] 万灵药 (100%)
- [88层] (R) 高塔 (20%概率出现)
    - 没出现就摸旁边的纹章回到79层再摸旁边的转移装置传回来刷新
- 主线: 狮子座召唤兽 **统治者赫修马伦** (弱劲风，主线Boss都是渣渣)
    - 给 **雅雪**

### 至天旋廊

![至天旋廊](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/180.png)

- [12] 黑暗物质 (100%)
- [14] 终极万灵药 (100%)
- 主线Boss: 希德博士 (弱神圣)
- 主线: 宝瓶座召唤兽 **黑暗之云法姆弗利特** (弱火焰)
    - 给 **巴夫雷尔**

## 拉巴纳斯塔

- 开始清理委托讨伐
- [公会总部] 接受紧急委托: **帝王凶恶巨兽**, **伊克西翁**, **神**
- [达朗的家 寇可敏] 开始委托: **帝王凶恶巨兽**

## 港都巴冯海姆

- 通关前的最后自由活动时间，我们有大把委托和遗留问题要处理
- [白波亭] 接受委托: **死亡凝视**, **迪亚布罗斯**, **夺灵魔**, **狂暴毛尔波尔**, **卡托布雷帕斯**, **法夫纳**, **派尔拉斯特**
- [白波亭 白波亭的女孩] 开始委托: **伊克西翁**
- [塞席欧街 李奇] 开始委托: **派尔拉斯特**
    - 要先赛跑，输赢无所谓，在这里赛跑赢100次分别有不同的奖励，但是你不会这么蛋疼吧

## 死都拿普迪斯

### 崇高者之室

- [隐藏商人] 购买 \***大复原**: 12000 gil
- [隐藏商人] 多买点 [b]高级麻醉药[/b]，毕竟路太远了

## 柏尔海姆地下道

- [配电设备区块] 购买 \***毒云**: 8500 gil

## 帝都阿凯迪斯

- 购买 \***大匿迹**, \***重力**: 6100 gil
- [飞空艇总站 喜好旅行的儿子] 开始委托: **死亡凝视**

## 飞空艇

- 一直坐高速飞空艇往返那尔比纳城塞，如果没出现就和喜好旅行的儿子再次对话后再坐飞空艇，直到他出现
    - 初始出现概率4%，之后每次翻倍
    - 遭遇后进入飞空艇内部，这趟航班上可以买到 **Ｃ９Ｈ８Ｏ４**: 700 gil
    - 上甲板打委托怪
- (M) 死亡凝视
    - 可以给自己上反射
    - 获得奖杯: *【头号飞侠】 已讨伐死亡凝视的证明。*

## 飞空艇总站

- [喜好旅行的儿子] 完成委托: **死亡凝视**

## 空中都市卜耶巴

- [采掘作业员居住区 米克里欧] 开始委托: **迪亚布罗斯**

## 路苏魔石矿

### 第11矿区采掘场

![第11矿区采掘场](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/123.png)

- (M) 迪亚布罗斯 (弱水流)

## 空中都市卜耶巴

- [采掘作业员居住区 米克里欧] 完成委托: **迪亚布罗斯**

## 布尔欧密谢司

- [神殿境内 艾伐努斯] 开始委托: **夺灵魔**
- [通往神殿的道路 依荷] 开始委托: **法夫纳**

## 帕拉密纳大峡谷

- 反复进出刷出大暴雪天气
- 不要进入 **结冰小溪**，否则大暴雪天气会结束

### 银流的起点

- 击杀一个精灵蕾西

### 卡瑞丹大冰河

![卡瑞丹大冰河](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/080.png)

- (T) 命符监视者 (杀光敌人出现)

### 银流的终点

![银流的终点](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/163.png)

- (M) 法夫纳 (弱雷电, 吃 **缓慢**, 装备 **红宝石戒指**, 如果用魔法打装备 **蛋白石戒指**)
    - 获得奖杯: *【血腥之龙】 已讨伐法夫纳的证明。*

## 基鲁菲冈

### 火之门

![火之门](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/147.png)

- (M) 夺灵魔

## 布尔欧密谢司

- [神殿境内 艾伐努斯] 完成委托: **夺灵魔**
- [通往神殿的道路 依荷] 完成委托: **法夫纳**

## 叶露特村里

- [精灵居住的大树 蕾提娜] 开始委托: **狂暴毛尔波尔**

## 幻妖森林

- 从基鲁菲冈的传送点出来，清空外面两个区域的所有敌人
    - 思绪的尽头
        - 1x 基鲁菲冈龙
        - 5x 凶恶巨兽
        - 9x 螳螂恶魔
        - 16x 巴西利斯克
    - 睿智冰原
        - 2x 凶恶巨兽
        - 15x 螳螂恶魔
        - 12x 巴西利斯克

### 思绪的尽头

![思绪的尽头](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/143.png)

- (M) 帝王凶恶巨兽 (倒转, 高涨腰链, 魔防破坏, 防御破坏)
    - 获得奖杯: *【王中翘楚】 已讨伐帝王凶恶巨兽的证明。*

### 飘香花朵庭园

![飘香花朵庭园](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/140.png)

- (M) 狂暴毛尔波尔 (弱劲风)

## 拉巴纳斯塔

- [达朗的家 寇可敏] 完成委托: **帝王凶恶巨兽**

## 叶露特村里

- [精灵居住的大树 蕾提娜] 完成委托: **狂暴毛尔波尔**

## 戈利夫族村落佳哈拉

- [安祥大地 战士长史匹涅鲁] 开始委托: **卡托布雷帕斯**

## 杰尔提尼安洞窟

### 海的尽头

![海的尽头](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/035.png)

- (T) 阿提克 (Chain连锁12只梅莉莎后1AC)

### 沙漏山谷

![沙漏山谷](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/036.png)

- (M) 卡托布雷帕斯 (弱神圣)

## 戈利夫族村落佳哈拉

### 安祥大地

- [战士长史匹涅鲁] 完成委托: **卡托布雷帕斯**
- 对话 **风水士尤格基尔**，告诉你可以去讨伐 黑涅魔石矿 里的凶恶敌人了 (蛇夫座召唤兽前置)

## 黑涅魔石矿

### 坑口分歧点Ｂ

- (T) 融化果冻 (切换开关, 50%概率出现, 没出就2AC刷新)
- 至此完成全部30个稀有讨伐，我们回去交一下任务拿缎带

## 丰恩海岸

- 狩猎圈
    - 热爱攻击的班葛族人: 给5个讨伐证
    - 热爱防御的班葛族人: 给5个讨伐证
    - 什么都好的班葛族人: 给20个讨伐证
    - 获得缎带
    - 旁边的狩猎圈商人处可以购买 **源氏前臂**: 447000 gil
        - 其他东西如果不差钱就全买下来吧

## 帝都阿凯迪斯

- [高层露台] 对话 **狩猎圈老板**
    - 获得各星座圣石x1
    - 因为有奖杯要逛遍所有地图，所以就来一下这里吧，顺便拿点东西，但不玩交易品是没用的

## 黑涅魔石矿

### 第２期采掘现场

![第２期采掘现场](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/164.png)

- [20] 决斗面具 (100%)
- [21] 北落师门 (100%)
- [24] 鲸齿吊坠 (25%)
- [25] 伟大头盔 (25%)
- [26] 头环 (100%)
- [29] 伏尔坎宁式T (100%)
- [31] 秘银剑 (100%)
- [!!] 获得字条

### 区间连结线Ｃ

![区间连结线Ｃ](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/165.png)

- [35] 倒转的魔片 (75%, 25%) 这是刷 **倒转的魔片** 最快的地方，可以为之后考验模式存上十几个
- [39] 高涨腰链 (25%)
- [40] 盖尔米那斯长靴 (100%)
- (R) 眩环眼 (击杀3个以上百目怪出现，第２期采掘现场也能出)

### 坑口分歧点Ｃ

- 唯一指定练级点，切换开关会出大量深渊蝠(再次切换不会再出，需要2AC刷新)
    - 记得装备 **雏鸟披肩**
    - 注意拉一个高HP角色 **高涨** + **诱饵** 硬扛
    - 传统打法是油液大火焰，但是神弓+烈火箭清场也不慢
    - 建议练到70级以上再继续

### 特殊采掘坑

![特殊采掘坑](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/166.png)

- 这里的敌人很强，还会即死，但是弱圣，可以用 **特罗之剑** 和 **神圣长枪** (之前拿了一把，港都也有卖) 打，比神器打得快
- 宝箱出现率不高，要反复刷，建议拿完宝箱后再切回上一个地图跑回来，留一个摸完道具的自动存档，防止一会儿万一佐狄亚克翻车了又要重新摸宝箱
- [48] 最强之矛 (1%, 100%) 列举一下，但是建议不刷
- [52] \***全疗伤** (100%)
    - 获得奖杯: *【符文指挥家】 已学会所有魔法的证明。*
- [53] \***魔攻破坏** (10%)
- [54] 勇气服 (25%)
- [57] 缎带 (15%)
- [59] 伟大护甲 (25%)
- [60] 领主法袍 (100%)
- [!!] 之前如果获得了字条，在这里可以获取2x终极万灵药, 3x酒神之酒

### 特殊作业场

- 蛇夫座召唤兽 **戒律王佐狄亚克**
    - 大招几率秒人，有点看脸，而且见面就是一个大招很难蚌
    - 血多的时候大招放得慢，红血后释放大招间隔极短，所以先不要攻击他，而是先充分破坏，魔法来不及复活建议用凤凰尾巴复活
    - 如果没有尖峰导致感受上太难，可以先不打伤害，而是充分防御破坏/魔防破坏，以免血量低的时候大招放太快大家都忙着救人了
    - 在红血的时候不要开倍速，然后手操黑魔放冲击或者毒云，不要用火光和崩炮，他们容易卡住指令队列；这Boss攻击破坏/魔防破坏对难度影响不大，毕竟你不上魔防壳吃他大招的话都被秒概率较高
    - 弱神圣，可以用特罗之剑或者神圣长枪打
    - 装备防暗 (有尖峰就装尖峰)，有黑面具就装黑面具，理论上此时至少有一个
    - 注意 **驱魔**
    - 请尽可能保持魔防壳状态，或者装备 **魔防壳盾**
    - 红血时会开物免盾+反射: 用魔法打，可以上反射轰自己(注意反射的情况下上不了倒转和高涨，会增加手操难度)，或者装蛋白石戒指
    - 给 **巴修**
    - 获得奖杯: *【黄道勇士】 已讨伐佐狄亚克的证明。*
    - 获得奖杯: *【伟大天敌】 已取得所有召唤兽的证明。*

## 大灯塔下层

### 满足渴望的广场

![满足渴望的广场](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/162.png)

- (M) 派尔拉斯特 (弱火焰)
- 摸电梯，可以去地下层了

## 大灯塔 地下层

- 坐电梯到地下层
- 进入地下层后如果发现有敌人就立刻坐电梯回来，如此往复，直到下去发现一个敌人都没有，就可以原地等伊克西翁出现了
- (M) 伊克西翁 (弱神圣)
- 地下有三层，每一层都有四个方位要放黑珠子，放超过了会爆掉重新放，需要数量都写在下面了

### 暗影之层

- 东北: 18个黑珠子
- 西北: 9个黑珠子
- 东南: 3个黑珠子
- 西南: 6个黑珠子

### 暗影之层 北外围

![暗影之层 北外围](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/181.png)

- [3] 靛蓝 (5%)
- [!!] 凤凰

### 暗影之层 南外围

![暗影之层 南外围](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/182.png)

- [6] 金色护身符 (70%, 10%)  没用了，不会还有人盘没开完吧
- [7] 雏鸟披肩 (70%, 10%)
- [8] 守护戒指 (20%)

### 暗昏之层

- 东北: 15个黑珠子
- 西北: 9个黑珠子
- 东南: 15个黑珠子
- 西南: 18个黑珠子

### 暗昏之层 北外围

![暗昏之层 北外围](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/183.png)

- [10] 浮雕皮带 (5%)

### 暗昏之层 南外围

![暗昏之层 南外围](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/184.png)

- [18] 鲸齿吊坠 (5%)

### 阴里之层

- 东北: 15个黑珠子
- 西北: 21个黑珠子
- 东南: 27个黑珠子
- 西南: 12个黑珠子

### 阴里之层 北外围

![阴里之层 北外围](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/185.png)

- 黑珠子不够的话可以在这里刷缎带的同时多多杀敌获取
- [20] 缎带 (10%)
- [22] 赫米斯靴 (70%, 10%)
- [24] \***攻击破坏** (10%)
    - 获得奖杯: *【绝招大师】 已学会所有招式的证明。*

### 阴里之层 南外围

![阴里之层 南外围](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/186.png)

- 获得奖杯: *【探险家】 已进入过所有地图的证明。*
    - 如果还没跳就是 **杰尔提尼安洞窟** 的 **芭兰卡断层** (有全游戏最强的99级普通小怪，所以之前没建议你去)还没去，攻略末尾收尾会去
- [31] 终极万灵药 (100%)
- [32] 川口塔峰 (2%, 1%) {佩戴钻石手环}
    - 这里介绍一个简单获取方法，已经对PS5主机上初始化随机数的变化进行了改进，我录了视频，地址在攻略开头 (仅适用于PS4版本; PC版请自行研究RNG工具，或者直接打mod; Switch版最难拿，请自行搜索视频攻略)
        - 只上阵一个角色，关闭作战布局，装备 **钻石手环**
        - 干掉所有敌人后把房间里的终极万灵药箱子摸掉，然后重新进房间，游戏会有个自动存档
        - 完全关掉游戏重启后快速读取我们之前准备的瑞克斯的存档，使用PS4主机玩的话砍自己两刀，使用PS5主机玩的话砍自己6刀(如果反复几次序列出不了就少砍一刀)，然后一直给自己使用回复魔法(MP不够就摸蓝水晶)直到出现连续三次的数字是97,94,95(如果20次以内不出这个序列，退出游戏重来)，然后再砍自己一刀必然格挡
        - 按OPTION后再按□退回主菜单
        - 读取房间自动存档，箱子出来了
        - 砍自己一刀，给自己加一次血，摸箱子必出神剑

### 目的地不明

- (M) 暗神 (弱神圣, 防神圣+防暗波)
    - 打到这里其实已经不算难了，毕竟是不物免的Boss，注意先杀他召唤的小怪后才能对本体造成伤害

### 阴里之层 北外围

![阴里之层 北外围](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/185.png)

- (R) 混沌之魂 (暗神狩猎结束后, 25%几率出现)

### 暗昏之层 南外围

![暗昏之层 南外围](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/184.png)

- (R) 光中之光 (击杀上面的 **混沌之魂** 后，不要读取自动存档不要离开地下)

## 港都巴冯海姆

- [塞席欧街 李奇] 完成委托: **派尔拉斯特**
- [白波亭 白波亭的女孩] 完成委托: **伊克西翁**

## 拉巴纳斯塔

- [公会总部 蒙布朗] 完成委托: **神**
- [公会总部 蒙布朗] 接受紧急委托: **亚兹马特**
    - 注意: 亚兹马特要完成全部H级委托才会出现

## 黎铎亚纳大瀑布

- 亚兹马特 (弱暗波)
    - 装上缎带，能装魔防壳盾就装魔防壳盾，否则保持魔防壳的buff
        - 因为缎带不能防即死，而这条龙的某个小招是即死，魔防壳状态下变成50%概率即死，大大提高了生存率
    - 主T诱饵+魔防壳盾+逆转开场
    - 攻击破坏和魔攻破坏到觉得打自己不疼了，关掉逆转改防御破坏到不能破坏为止
    - 主T负责输出，保持诱饵状态，喝酒神的酒或者给狂暴，狂战士状态输出
    - 其他角色负责大招死人的情况下拉人，只要不是运气太差，基本上也就是时间问题，4倍速磨个十几分钟也就过了
    - 获得奖杯: *【至尊猎人】 已讨伐亚兹马特的证明。*

## 拉巴纳斯塔

- [公会总部 蒙布朗] 完成委托: **亚兹马特**

## 水晶巨界

- 最后来打欧米茄mk.⑫
- 如果之前没打的话，现在可以装上缎带打拉尔拔吞噬者和恶灵了

### 石炭纪

![石炭纪](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/148.png)

- IX 传送

### 泥盆纪

![泥盆纪](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/151.png)

- XX 传送

### 寒武纪

![寒武纪](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/154.png)

- XVIII 传送

### 奥陶纪

![奥陶纪](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/153.png)

- XXI 传送 (通过 V1 和 C2)

### 泥盆纪

![泥盆纪](https://jiashu.1win.eu.org/https://raw.githubusercontent.com/soarqin/imgs/refs/heads/images/ff12tza/155.png)

- 欧米茄mk.⑫
    - 只有一种攻击方式: 用激光滋你，但是伤害极高
    - 攻击有5%概率对我方施加狂战士状态，注意用鲸齿吊坠+酒神的酒解除狂战士状态
    - 主T诱饵，全体倒转，攻击破坏到不疼以后关掉倒转再打
    - 此时因为Boss有伤害反弹，可以给主T诱饵+倒转，让他一个人打输出，其他人攻击他或者对他放高级魔法给他回血
    - Boss掉落欧米茄纹章，但是我们不做德罗之剑，不管他

## 杰尔提尼安洞窟

- [芭兰卡断层] 上古壳龙 (弱冰, 可以攻击破坏也可以逆转硬打，注意指令要选择HP最低的敌人打)
    - 最强普通怪，打完可以去角落拿一下地图，如果想收集全地图的话
    - 如果之前全地图访问的奖杯没跳，这时候应该跳了
    - 获得奖杯: *【编书人】 狩猎目录已收集齐全的证明。*

## 收尾

- 如果还没完成全部联手技，那么现在就随便找个有水晶的地图就近刷吧
    - Lv就是魔雾技消耗的格子数
    - 运气成分比较大，魔雾匣回复出不出纯看脸，有时候你剩4s刷5次都出不了一个魔雾匣回复
    - 有魔雾匣回复尽量选魔雾匣回复，这玩意儿想要的时候真不一定刷得出
    - 摸水晶可以回满魔雾条，所以多多尝试即可，黑洞最难，平时路上魔雾匣满了闲得无聊就可以搓一搓，反正有神弓基本不需要魔雾技/召唤兽救场
    - 注意: 留给你按键的总时间是定值的4s，但每次按成功会恢复一点时间(剩余时间较少的时候恢复得会更多一点)，刷新和恢复魔雾条都会消耗大约0.25s，所以前面有按就按，后面再根据各个级别已经按过的次数来选择
    - 联手技列表:
        - 炎之炼狱 Lv1 x3
        - 土之剧变 Lv1 x6
        - 水之喷发 Lv1 x2 + Lv2 x2
        - 风之狂喜 Lv2 x4
        - 蔽眼飞雪 Lv3 x4
        - 电弧爆破 L1 x2 + Lv2 x2 + Lv3 x2
        - 冷光 L1 x3 + Lv2 x3 + Lv3 x3
        - 黑洞 L1 x4 + Lv2 x4 + Lv3 x4
    - 获得奖杯: *【团结势力】 已施展所有魔雾技连手后之融合技的证明。*
- 此时公会等级也应该达到了 **永生诸神**，空贼藏身处全部角色都出现了

## 通关考验模式

- 我这里在通关之前先打考验模式，毕竟以通关作为白金收尾比较有仪式感
- 建议在 **黑涅魔石矿** **坑口分歧点Ｃ** 练到80级(至少给 **巨蟹座·泽罗姆斯** 和 **蛇夫座·佐狄亚克** 的两个角色要练到80，其他人70左右也够了)去打，最后10层会轻松不少(虽然弱模式也能打，但我们讲究的是无脑打)
- 打之前先去买满 **高级麻醉药** (**死都拿普迪斯** **崇高者之室** 隐藏商人)，**凤凰尾巴** + 各种异常状态解除药 + **酒神的酒** + **至高治疗剂** (帝都道具店都有)
- 85层以后尽量用诱饵+倒转打
- 部分我们之前打过的高血量高伤害Boss，打法都完全一致，总结一下:
    - 自带有利状态的Boss先给 **驱魔** 或者 **驱魔的魔片**
    - 给主T装备 **尖峰** (没有刷的话可以用其他闪避率高的盾)上 **诱饵**，全体上 **倒转**，**攻击破坏**/**魔攻破坏** 到不疼了，关掉 **倒转** 后带走(百层Boss血量都不算太高，除了97~99三层，其他都可以不 **防御破坏**/**魔防破坏**)
    - 如果是伤害反弹的Boss，不要关倒转，给主力输出手 **诱饵** + **倒转**，然后其他人攻击这个主力输出手给他回血
    - 如果有附加特殊异常的Boss，用 **鲸齿吊坠** 的逆转道具效果解除(比如用酒神的酒解除狂战士)
    - 如果Boss攻速特别快，那么在 **攻击破坏** 完成前可以用 **至高治疗剂** 回复，甚至直接攻击倒转后的队友(记得别带有闪避和格挡的装备)来代替回复魔法，因为这样后摇比较小，总体回复效率更高
    - 无法物理伤害的Boss，可以用 **冲击** 和 **毒云** 打，虽然输出不是最高的，但是因为攻速快，不容易卡住指令队列导致来不及回复或者拉队友
    - 当人倒得很快的时候不要慌，记住一点: 道具使用比魔法快。比如当只剩一个小伙伴还站着的时候，感觉拉人有点难，可以给自己吃一个 **倒转的魔片** 再拉队友，然后尽快给有倒转的人上 **诱饵**
- 第100层是唯一难点，单独说一下:
    - 不要加速游戏，用1倍速开始
    - 全体放好 **高涨**，或者装备 **高涨腰链** 入场
    - 让有 **巨蟹座·泽罗姆斯** 和 **蛇夫座·佐狄亚克** 的角色上场
    - 上来就召唤 **巨蟹座·泽罗姆斯**，召唤者装备 **鲸齿吊坠** 后给 **泽罗姆斯** 喂万灵药，同时 **泽罗姆斯** 给自己使用高涨的魔片，此时HP应该会变为1或者2，然后 **泽罗姆斯** 放大招，手速要快避免 **泽罗姆斯** 被打死，不过这时候敌人一般还没过来
    - 此时敌人至少倒下了两个，迅速召唤 **蛇夫座·佐狄亚克**，直接放大招，两到四套大招放完场上应该剩一个敌人
    - 如果怕 **蛇夫座** 的召唤者被秒的话，可以集中给他喂 **至高治疗剂**，比用魔法回复效率高
    - 在等待动作完成的间隙可以让装 **鲸齿吊坠** 的角色给剩下的敌人喂 **万能药**，减少他们的威胁，同时另一个人给 **蛇夫座** 的角色吃 **万灵药** 回满魔雾技条
    - 剩一个人的时候就可以全体开 **倒转** 虐杀了，当然你也可以继续 **蛇夫座**，只是这动画时间太长有点浪费时间
- 获得奖杯: *【大元帅】 已通过考验模式100关卡的证明。*

## 通关剧情

- 驾驶飞空艇直接冲入  **空中要塞巴哈姆特**
    - 打完全部讨伐后，主线Boss已经如同小儿科一般，想怎么切就怎么切
- 看完剧情，ED之前就跳通关杯
    - 获得奖杯: *【凭借自己的翅膀】 让伊瓦利斯恢复和平的证明。*

## 白金/全成就撒花

- 获得奖杯: *【伊瓦利斯的霸者】 已获得所有奖杯的证明。* (Steam版成就描述为“*已收集所有成就。*”)
