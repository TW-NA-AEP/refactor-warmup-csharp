# 重构线上练功房热身编程题
本项目为ThoughWorks内部【敏捷工程实践系列】之「重构」线上练功房热身编程题，两道题业务复杂度相对简单，预估花费 0.5 ~ 1小时完成。

目的：1. 热身；2. 摸底

## 开发环境
 - .Net Core 3.1
 - xUnit 2.4


## 超市收银机
#### 背景
老王经营了一家超市，之前找了一个Vendor开发了一款简化版的超市收银机。收银机的功能很简单：在顾客结账时，需要打印订单信息。之前的Vendor已经开发出了可以用的代码。


收银机一直都很难用，收银员经常跟老王抱怨。老王由于勤快，把超市做大了，寻思着找个好的Vendor把软件优化一下，并继续开发一些新功能。他听说TW在软件交付方面很擅长，擅长交付高质量的软件，于是找到了TW。

TW工程师接收后，却发现代码存在神一般的命名和谜一般的逻辑，所以为了更好地继续下去，不得已停下来对已有代码进行重构。

此时，你正好在该项目担当重构大任的骨干，接下来请你完成这一轮重构，让代码从`可用`到`简洁可用`。


#### 练功要求
1. 重构前运行测试，确保测试是通过的
2. 每修改一处代码，运行测试，确保测试是通过的，并做一次Commit，Commit信息描述你认为的代码坏味道和重构手法
3. 产品代码位于`refactor-gym-warmup`下的`Cashier`文件夹中
4. 测试代码位于`refactor-gym-warmup-test`下的`Cashier`文件夹中
5. 不要修改测试代码
6. 尽自己所能，尽可能多的找出坏味道，并重构掉


## 补充
每个小伙伴将该项目fork自己的GitHub账号下

