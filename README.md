# P40-GPU-Lottery

**2024年3月19日公告：中奖者[kafmws](https://github.com/kafmws)已领奖，活动结束，感谢大家。**

本仓库即日起进入存档状态。

------

BD4SUR的抽奖活动第二弹！报名参与抽奖活动之前，请务必通读本文。

![ ](girl-holding-tesla.png)

## 0. 抽奖者名单与开奖结果公示

**[中国福利彩票3D游戏第2024065期（2024年3月15日）开奖号码：469](https://www.cwl.gov.cn/c/2024/03/15/571026.shtml)**

**依据开奖办法，本次为有效开奖，中奖者编号为：19。**

获得抽奖资格人数为：25人。

|编号|GitHub ID|报名Issue|是否中奖|
|---|---------|---------|-------|
|0|[jinyouzhi](https://github.com/jinyouzhi)|[#1](https://github.com/bd4sur/P40-GPU-Lottery/issues/1)|❌|
|1|[svatyvabin](https://github.com/svatyvabin)|[#2](https://github.com/bd4sur/P40-GPU-Lottery/issues/2)|❌|
|2|[zbuibe](https://github.com/zbuibe)|[#3](https://github.com/bd4sur/P40-GPU-Lottery/issues/3)|❌|
|3|[celeron533](https://github.com/celeron533)|[#4](https://github.com/bd4sur/P40-GPU-Lottery/issues/4)|❌|
|4|[ideniece](https://github.com/ideniece)|[#5](https://github.com/bd4sur/P40-GPU-Lottery/issues/5)|❌|
|5|[llw9830](https://github.com/llw9830)|[#6](https://github.com/bd4sur/P40-GPU-Lottery/issues/6)|❌|
|6|[wonsage](https://github.com/wonsage)|[#7](https://github.com/bd4sur/P40-GPU-Lottery/issues/7)|❌|
|7|[LiDaiyan](https://github.com/LiDaiyan)|[#8](https://github.com/bd4sur/P40-GPU-Lottery/issues/8)|❌|
|8|[Argon-Pub](https://github.com/Argon-Pub)|[#10](https://github.com/bd4sur/P40-GPU-Lottery/issues/10)|❌|
|9|[booksword](https://github.com/booksword)|[#11](https://github.com/bd4sur/P40-GPU-Lottery/issues/11)|❌|
|10|[yana9i](https://github.com/yana9i)|[#12](https://github.com/bd4sur/P40-GPU-Lottery/issues/12)|❌|
|11|[Eminlin](https://github.com/Eminlin)|[#13](https://github.com/bd4sur/P40-GPU-Lottery/issues/13)|❌|
|12|[Cache-Cloud](https://github.com/Cache-Cloud)|[#14](https://github.com/bd4sur/P40-GPU-Lottery/issues/14)|❌|
|13|[deathxlent](https://github.com/deathxlent)|[#15](https://github.com/bd4sur/P40-GPU-Lottery/issues/15)|❌|
|14|[AcidProton](https://github.com/AcidProton)|[#16](https://github.com/bd4sur/P40-GPU-Lottery/issues/16)|❌|
|15|[starlovec](https://github.com/starlovec)|[#17](https://github.com/bd4sur/P40-GPU-Lottery/issues/17)|❌|
|16|[siphonelee](https://github.com/siphonelee)|[#18](https://github.com/bd4sur/P40-GPU-Lottery/issues/18)|❌|
|17|[avarbykira](https://github.com/avarbykira)|[#19](https://github.com/bd4sur/P40-GPU-Lottery/issues/19)|❌|
|18|[kelvinyu](https://github.com/kelvinyu)|[#20](https://github.com/bd4sur/P40-GPU-Lottery/issues/20)|❌|
|19|[kafmws](https://github.com/kafmws)|[#21](https://github.com/bd4sur/P40-GPU-Lottery/issues/21)|✔|
|20|[Nitromethane](https://github.com/Nitromethane)|[#22](https://github.com/bd4sur/P40-GPU-Lottery/issues/22)|❌|
|21|[m5s2l1](https://github.com/m5s2l1)|[#23](https://github.com/bd4sur/P40-GPU-Lottery/issues/23)|❌|
|22|[yugithere](https://github.com/yugithere)|[#24](https://github.com/bd4sur/P40-GPU-Lottery/issues/24)|❌|
|23|[wldd01](https://github.com/wldd01)|[#25](https://github.com/bd4sur/P40-GPU-Lottery/issues/25)|❌|
|24|[imlonghao](https://github.com/imlonghao)|[#26](https://github.com/bd4sur/P40-GPU-Lottery/issues/26)|❌|

## 1. 活动背景与奖品

**1.1 活动背景**

本人最近在搭建自有深度学习基础设施（炼丹炉），购买了若干P100和P40计算卡。<del>其中有一块P40计算卡到手发现并不是公版卡，显存略小。出于整齐的考虑，不想将这块卡与其他24GiB的公版卡混用，于是</del>（实际上是因为开了ECC，关掉就可以看到24GiB了）打算通过抽奖的形式，把这块卡赠送给有兴趣的同好。

**1.2 奖品**

奖品是一块 Nvidia Tesla P40 (24GiB) 计算卡，不含任何配件。[点击此处查看Datasheet](https://www.nvidia.com/content/dam/en-zz/Solutions/design-visualization/documents/nvidia-p40-datasheet.pdf)。P40是2016年上市的高端数据中心计算卡，性能约等于同时代的消费级显卡 GeForce GTX 1080 Ti，2024年3月市场价约700~900元。其优势是显存较大，且性能和价格较为适中，是入门AI大模型的不错的选择。作为数据中心计算卡，P40支持ECC，如果开启ECC，则可用显存为22.5GiB，并且运算性能会有6%左右的下降（使用[gpu-burn](https://github.com/wilicc/gpu-burn)实测得知）。

## 2. 报名

**2.1 报名时间和名额限制**

2024年3月13日（星期三）24点锁定抽奖名单。抽奖名单锁定后，不再接受报名。

获得抽奖资格的人数限制为1000人以内（含）。

**2.2 获得抽奖资格的条件**

你需要同时符合以下两个条件，才可能获得抽奖资格：

- 使用自己的GitHub账号，在本仓库发表报名Issue，表明抽奖意图。
- 同时，关注（Follow）本人（[BD4SUR@GitHub](https://github.com/BD4SUR)）的GitHub账号。

如果本人判断有作弊的迹象，例如有2个及以上的参与报名的GitHub账号可能对应同一个自然人，本人将拒绝作弊者参与抽奖。

## 3. 开奖

**3.1 抽奖者编号办法**

凡获得抽奖资格的报名者，将在第0节的表格中公示，并赋予编号。编号从0开始递增。编号的依据是提交报名Issue的时间顺序，时间早者，编号小。

**3.2 开奖时间**

2024年3月15日（星期五）开奖。

**3.3 开奖办法**

- 选取[中国福利彩票3D游戏](http://www.cwl.gov.cn/fcpz/yxjs/fc3d/)在开奖日期当天的开奖结果，记为`S`，`S`是一个位于[0, 999]闭区间内的整数。
- 抽奖名单锁定后，确认获得抽奖资格的人数记为`N`，`N`不大于1000。
- 福彩最大有效开奖结果 `Smax = N * 下取整(1000 / N) - 1`。
- 若`S > Smax`，则为无效开奖，开奖向后顺延一天。
- 若`S <= Smax`，则为有效开奖，中奖者在第0节的表格中的编号记为`k`，`k = S Mod N`，其中`Mod`指计算`S`除以`N`所得的余数。

## 4. 兑奖

**4.1** 本人将与中奖者积极联系，协商兑奖事宜。中奖者应当自行关闭自己发表的报名Issue，以公示知悉并承认开奖结果。

**4.2** 如果开奖7天后，本人没有联系上中奖者，或者因中奖者自身原因（例如拒绝领奖）导致无法兑奖，则从第0节的表格中剔除先前中奖者，重新开奖。

**4.3** 本人将以快递到付方式，将奖品寄给中奖者。若中奖者位于南京，也可约定当面转交奖品。

## 5. 权利与义务

**5.1** 这次抽奖活动为本人基于善意和诚信开展，目的是吸引听众、结交朋友、并使得闲置计算卡物尽其用。

**5.2** 报名，意味着理解并接受本文档中的全部陈述和约定。如果不理解或不接受本文档中的任何内容，请勿报名。

**5.3** 本人保留暂停、延迟、修改或者取消活动的权利，但是本人将尽最大可能保证活动顺利开展。

**5.4** 中奖者（受赠人）须保证：

- 不使用奖品（赠与物）从事任何违法违规行为。
- 因拥有或使用奖品（赠与物）所造成的任何收益、损失或法律责任，均由受赠人享受或承担。
- 计算卡功耗和发热较高，使用时请注意安全。请自备电源转接线。

**5.5** 本人（赠与人）保证、声明：

- 开奖成功之后，本人承诺必定兑现开奖结果，并尽快完成兑现和奖品（赠与物）交接。
- 本人放弃赠与后对此赠与物原有的一切权利和义务，保证不撤销赠与。
- 本人不对赠与物的可用性、性能、质量等性质作任何保证。
- 本人不提供与该赠与物相关的咨询与支持服务。（因为我自己也不懂，哈哈）

## 6. 其他说明

**6.1** 之所以使用GitHub记录抽奖全过程，是出于两点考虑。一是公开性，也就是说，任何人对本仓库所进行的任何修改，都可以在提交记录中看到。二是可以给参与者设定一个门槛。

**6.2** 本文采用比较严谨和正式的措辞，是为了尽可能体现公平、公开。

**6.3** 本人联系方式：bd4sur 艾特 qq.com。欢迎使用电子邮件联系。

