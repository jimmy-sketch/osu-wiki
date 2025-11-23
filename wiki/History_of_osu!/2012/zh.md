# osu! 2012 大事记

## 九月

![](img/2012-09_01.jpg "当时的 osu! 主菜单")

2012年9月17日，osu! 及其社区迎来了五周岁生日。为了庆祝这一时刻，从 2012年9月16日（18:00 UTC，正是 2007 年 osu! 最初诞生的时间）开始，全服玩家都被赠予了 24 小时的 [osu!supporter（支持者）](/wiki/osu!supporter) 资格。Peppy 本打算发布某个形式的 osu! 早期版本作为庆典内容，好让大家体验一下早期的 osu!，追溯这款软件的起源。遗憾的是，由于 `.dll` 文件版本冲突，Peppy 没能成功让它运行起来。不过他表示，总有一天会搞定这件事的。

相关链接：

- [osu! 五周年 (论坛帖子)](https://osu.ppy.sh/community/forums/topics/98349)

## 十月

![](img/2012-10_01.jpg "osu!mania 标志")

![](img/2012-10_02.jpg "编辑器左侧新增的物件独立音效设置")

2012 年 10 月 8 日，由 [woc2006](https://osu.ppy.sh/users/1105845) 开发的 osu!mania 模式终于在公开版本中正式上线了！除了这个重磅新模式，这次的更新还包括以下内容：

- 编辑器新增了针对单个物件的打击音效设置功能。([mm201](https://osu.ppy.sh/users/30655))
- [多人游戏](/wiki/Client/Interface/Multiplayer) 机制优化：即使血条归零（Fail），只要后续操作将血量回满，即可“复活”，继续游戏。（开启 [Sudden Death](/wiki/Gameplay/Game_modifier/Sudden_Death) 或 [Perfect](/wiki/Gameplay/Game_modifier/Perfect) 模组时除外）。
- 游戏内的在线排名列表支持滚动查看。
- 修复了[皮肤选择器](/wiki/Client/Options#skin)，现在的预览效果更真实了。

本次更新的主角无疑是 osu!mania。大批玩家涌入 osu!，只为尝试这个新模式。对于开发者的努力，有人大加赞赏，但也有人质疑它的判定，认为相比《O2Jam》，osu!mania 的判定过严且偏差严重。考虑到这次更新包体积巨大（约为 20MB），部分玩家因无法完成更新而报错，出现各类问题也在意料之中。还有人抱怨这次更新过于仓促，因为无论是排名系统、谱面提交、难度调整，甚至是玩法本身，都显得不够成熟和完善。在听取了社区的大量反馈后，部分问题在 11 月左右得到了解决，其余的也在持续优化中。

冷知识：如果玩家在更新 b20121008 版本之前就进入多人游戏大厅，那么 osu!mania 房间将会显示为 "3" 而且没有图标。当然，如果不更新客户端，你不仅玩不了这个模式，甚至连房间都进不去。

![](img/2012-10_03.jpg "未更新 b20121008 版本会导致多人大厅中的 osu!mania 模式的房间显示异常")

相关链接：

- [osu! release (b20121008): osu!mania (论坛帖子)](https://osu.ppy.sh/community/forums/posts/1825880)

---

![](img/2012-10_04.jpg "Peppy 展示的背景更换功能")

从 2012 年 10 月 29 日开始，拥有 osu!supporter 身份的玩家终于可以自定义主菜单背景了。本次更新中还包括：

- osu!mania 排名进入 Beta 测试阶段。排行榜将会在一周后重置。
- 新增按键状态显示。
- 性能优化。

这是一次针对性很强的更新，既修复了上个版本（osu!mania）遗留的问题，也带来了玩家梦寐以求的功能 —— osu!mania 的上榜。由于该模式的计分系统尚未经过全面测试，为了防止作弊分数上传，排行榜将每周（甚至更短时间）重置一次。这项测试持续了相当长一段时间，直到 2012 年 11 月 13 日的版本 20121113b 中才结束。

对于支持者（Supporter）来说，能把 osu! 背景换成自己喜欢的图片而不再是单调的纯色，算是一项特权。实话实说，这功能纯粹是个视觉噱头，不影响游戏平衡。不过要注意，你需要保持在线状态才能让背景*真正生效*，因为 osu! 需要联网验证你的 supporter 资格。

按键状态显示（Key Overlay）被认为是一个很棒的新功能。现在，无论是在回放还是观战中，你都能*直观地看到*玩家的操作细节——是键鼠双修，还是在那儿疯狂“单双键混按”。默认情况下，该功能只在回放或观战时开启。如果你想在自己玩的时候也看到它，可以在 [选项 -> 输入 -> 常规](/wiki/Client/Options#general.1) 中勾选“总是显示按键覆盖层 (Always show key overlay)”。起初这个悬浮窗位于屏幕顶部，但因为遮挡血条且容易分散注意力，后来被移到了屏幕右侧。

相关链接：

- [osu! release (b20121029) (论坛帖子)](https://osu.ppy.sh/community/forums/topics/103427)

## 十一月

2012 年 11 月 13 日，**osu!mania 排名正式实装 PP (Performance Points) 系统**。为了确保彻底清除伪造或作弊的成绩，排行榜进行了最后一次重置。

相关链接：

- [osu!mania score reset (论坛帖子)](https://osu.ppy.sh/community/forums/topics/105564)

---

在 2012 年 11 月 22 日，osu! 又迎来了一次更新，包括:

- 本地化支持，支持显示更多语言。
- 选歌界面优化：右键点击非当前选中的谱面，可直接呼出选项菜单，无需先左键点击选中。
- DirectX 性能改进。
- ([多人游戏](/wiki/Client/Interface/Multiplayer)) 大厅新增“快速加入 (Quick Join)”按钮。
- 回放/观战时可使用“Fun Spoiler Settings”。

来自 [osu! localisation project v2](https://osu.ppy.sh/community/forums/topics/104342) 的成果已实装。你可以在 [选项](/wiki/Client/Options) 页面的“图形 (Graphics)”标签下的“语言 (Languages)”中进行设置。

多人游戏大厅新增了“快速加入”按钮。点击后，系统会根据你已有的谱面，随机把你塞进一个房间。既然是随机“强制”进房，如果你发现进去后谱面难度极不友好（通常是 Insane 或者是你根本打不过的难度），请不要太惊讶。除非你觉得手动找房太麻烦，否则这个功能也就是个备胎，仅限娱乐。

相关链接：

- [osu! Public Release (b20121122) (论坛帖子)](https://osu.ppy.sh/community/forums/topics/106677)

## 十二月

![](img/2012-12_01.png "RBRat3 创作的插图")

2012年12月21日，osu! 迎来了一次重大版本更新。最显著的变化包括：

1. 支持宽屏显示
2. 谱面开始前加入加载界面
3. 选歌界面更加丝滑流畅
4. “Fun Spoiler Settings”更名为 [Visual Settings（视觉设置）](/wiki/Client/Interface/Visual_settings) 并移至屏幕底部
5. No Video（无视频）模组被移入视觉设置菜单中

大更新往往伴随着技术故障和 Bug，这次也不例外。宽屏支持虽然功能正常，但因为裁剪了画面的顶部和底部，导致部分背景图和视频显示怪异（比如角色被“砍头”，文字显示不全）。此外，[故事板](/wiki/Storyboard) 当时还不支持宽屏，导致屏幕两侧会出现黑边，画面看起来非常下载。这也给 [Catch the Beat（接水果）](/wiki/Game_mode/osu!catch) 模式带来了麻烦，因为在宽屏下，水果有时会掉落到本该是边界的黑边区域的*上方*。还有些故事板会出现错位（图片跑到了黑边上）。这些问题都是已知项，社区正在讨论并寻找修复方案。

相关链接：

- [osu! Public Release (b20121221) (论坛帖子)](https://osu.ppy.sh/community/forums/topics/110459)

---

2012年12月25日，又是一个圣诞节。新版本的 [bancho](/wiki/Bancho_(server)) 服务端在这一天发布，官方称其“减少了连接时的数据传输量，这意味着连接速度将提升 95%”。为了庆祝节日，当天的 osu!direct 功能对所有玩家免费开放。

相关链接：

- [Merry Christmas (bancho changes + free osu!direct) (Forum thread)](https://osu.ppy.sh/community/forums/posts/2005499)
