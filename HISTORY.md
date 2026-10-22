# 开发过程

从鹈鹕骑车到恕瑞玛四人组，每一阶段都保留了完整可运行的 HTML。

## 01 · 鹈鹕单人骑行

绘制鹈鹕、单车与海岸背景，加入踩踏、车轮、围巾和暂停调速。

- 完整代码：[stages/01-pelican.html](stages/01-pelican.html)
- Git 标签：`stage-01-pelican`
- 提交：[`32808af`](https://github.com/Jiang-liran/shurima-cycling/commit/32808af29345e5584cabfeba8edb2d0d1418ba4d)

## 02 · 鳄鱼单人骑行

将主角换为绿色鳄鱼，加入鳞甲、长尾巴与摇尾动画。

- 完整代码：[stages/02-crocodile.html](stages/02-crocodile.html)
- Git 标签：`stage-02-crocodile`
- 提交：[`483cc69`](https://github.com/Jiang-liran/shurima-cycling/commit/483cc69df575236fd270e9188c776f1e7e060f11)

## 03 · 鹈鹕与鳄鱼一起骑行

把两位骑手放到同一场景，各自踩踏并在移动端错开排列。

- 完整代码：[stages/03-two-friends.html](stages/03-two-friends.html)
- Git 标签：`stage-03-two-friends`
- 提交：[`9a86b06`](https://github.com/Jiang-liran/shurima-cycling/commit/9a86b06b2de09a74f087c6c62e1eb4dccf16bb18)

## 04 · 加入小狗，三人骑行

新增棕色小狗、青绿色自行车、摆耳与摇尾动画。

- 完整代码：[stages/04-three-friends.html](stages/04-three-friends.html)
- Git 标签：`stage-04-three-friends`
- 提交：[`498e1cd`](https://github.com/Jiang-liran/shurima-cycling/commit/498e1cd3c1180b2771227e67a40a14afd957d2b7)

## 05 · 鳄鱼和小狗变为雷克顿与内瑟斯

将两名角色改为英雄造型，加入重甲、月牙巨刃、胡狼金冠和符文武器。

- 完整代码：[stages/05-renekton-nasus.html](stages/05-renekton-nasus.html)
- Git 标签：`stage-05-renekton-nasus`
- 提交：[`aee2870`](https://github.com/Jiang-liran/shurima-cycling/commit/aee287009074ce87e8af3979d473b73957eee167)

## 06 · 阿兹尔与泽拉斯加入四人组

将鹈鹕换为阿兹尔，新增泽拉斯及能量核心、浮动石甲和独立踩踏。

- 完整代码：[stages/06-four-champions.html](stages/06-four-champions.html)
- Git 标签：`stage-06-four-champions`
- 提交：[`b64e078`](https://github.com/Jiang-liran/shurima-cycling/commit/b64e0784c012a7bd47a2a618f5d025532de0c29d)

## 07 · 恕瑞玛沙漠与太阳圆盘

将海岸换为恕瑞玛沙漠，加入太阳圆盘、神庙、沙丘、遗迹与扬尘。

- 完整代码：[stages/07-shurima-desert.html](stages/07-shurima-desert.html)
- Git 标签：`stage-07-shurima-desert`
- 提交：[`a38baba`](https://github.com/Jiang-liran/shurima-cycling/commit/a38baba47b89ebc29cbc50b04ec17d005add1cf6)

## 如何切回某一阶段

```sh
git clone https://github.com/Jiang-liran/shurima-cycling.git
cd shurima-cycling
git switch --detach stage-01-pelican
# 用浏览器打开 index.html
# 返回最终版本：
git switch main
```

## 记录说明

这些提交在 2026-10-22 根据保留的阶段快照按需求顺序补建，未回填早于补建时间的提交日期。七份 HTML 均与对应快照逐字节一致；第七阶段与当前主页面一致。最后一个整理提交补齐封面、视频下载入口与本文档。原来的一次性上传保存在 `archive/initial-upload`，现有 `v1.0.0` Release 保持不变。
