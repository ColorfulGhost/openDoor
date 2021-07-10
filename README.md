# openDoor
use Raspberry Pi and 42 stepper motor for open door

# 用树莓派和42步进电机开发的开门装置

## 需求场景

公寓门禁卡就一张，不给多个卡。避免门禁卡遗忘、丢失，不在身边无法进入公寓里，被迫睡在公司╮(╯﹏╰)╭

## 设计与构想

我调研了这张门禁卡，想要通过复制门禁卡来做备用解决这个问题，但是加密卡无法复制所以复制卡的方案PASS。

既然复制卡实现不了就只能走物理上的开门了，虽然比较繁琐，但是想了下流程应该可以实现。

所需物品如下：

1. Raspberry Pi开发板
2. 42步进电机
3. 12V5A开关电源
4. A4988驱动器
5. 42步进电机支架（非必须 便于固定）
6. 皮带滚轮（非必须 便于拉取门把手增加阻力）
7. 继电器（非必须 为了避免A4988长时间通电烧坏与省电）
8. 杜邦线若干
9. 矿泉水一瓶（非必须 为了减少电机拉把手的扭力）
10. 毛线或者阻力比较大的绳子
11. 电焊胶水（固定电机支架在门上和其他用途）

以上就是需要准备的材料，下面是环境的搭建

## 所需开发环境

1. Nodejs (推荐最新版本)
2. Python (推荐最新版本)
3. pip (跟Python版本对应，Raspberry Pi上的Python不自带pip包管理)

PS: 由于是2年前做的细节都忘记了 只能回忆给大概
