
## 背景

最近有在手机上写笔记的需求，去酷安上搜了一下笔记本APP，发现纯纯写作挺好的，强调**永不丢失**，能**多端同步**，但是它的 Markdown 渲染功能要付费（在[一期播客](https://sspai.fireside.fm/ep12)中听说他的渲染引擎是自制的，并非基于Webview ，可能更省电些 ~~稍微记点东西感知不大~~），身为 Markdown 中毒用户，这我怎么能忍，马上去 Play Store 上搜md编辑器，结果找到了个炒鸡好用的，**有 git 支持**的编辑器——[**GitJournal**](https://j10ccc.xyz/post/gitnotebook/https;//gitjournal.io)。

git 同步有多方便多安全就不用我多说了，同步的私人仓库是自己的，多端跨系统同步不需要任何软件，有个能上网的浏览器就行。于是我马上打开APP，绑定了git。

考虑到 git 同步的稳定性，我选择了 码云gitee ，国内仓库比起 github 的玄学提交速度好多了（提交时间一般由笔记数量决定）

## 配置流程

1.  Select a Git Hosting Provider —— Custom
2.  去[码云](https://gitee.com/)创建一个新私有仓库
3.  输入 Git Clone URL
4.  匹配公钥

值得注意的是码云匹配公钥时有点不同： 有添加个人公钥选项。

[![👆标题乱输，公钥复制粘贴APP内随机生成的](https://s1.ax1x.com/2020/07/22/Ub55h8.png)](https://s1.ax1x.com/2020/07/22/Ub55h8.png)

## 主要界面

### 首页展示样式

[![](https://s1.ax1x.com/2020/07/27/aFxTIS.jpg)](https://s1.ax1x.com/2020/07/27/aFxTIS.jpg)

### 设置界面

[![](https://s1.ax1x.com/2020/07/22/UbI9c4.jpg)](https://s1.ax1x.com/2020/07/22/UbI9c4.jpg)

主要功能有：（部分功能要付费解锁，但几乎都是鸡肋）

-   可选昼/夜模式
-   设置默认文件夹 笔记文件保存在`/data/user/0/io.gitjournal.gitjournal/app_flutter/journal/`
-   提交 git 账户信息
-   设置默认打开的编辑界面
-   文件储存设置
-   调试信息（只保留当天的，同步失败这里找原因）

### 文本编辑

-   编辑器模式

[![](https://s1.ax1x.com/2020/07/22/UbICjJ.jpg)](https://s1.ax1x.com/2020/07/22/UbICjJ.jpg)

-   渲染效果

[![](https://s1.ax1x.com/2020/07/27/akpgGF.jpg)](https://s1.ax1x.com/2020/07/27/akpgGF.jpg)

关闭黑夜模式是因为 To Do 在黑夜模式下前面的选项框看不清楚（背景灰色，框黑色）

## 总结

1.  编辑体验一般，偶尔做些笔记可以，但写文章不太行，markdown 要打大量的符号，无快捷添加方式，只能一个个从键盘里面选，效率低下，且无 highlight ，标题加粗斜体等行不够醒目。
    
2.  To Do 编辑体验良好，跟其他编辑器不相上下，写 To Do 记得把编辑器模式拨对（Checklist Editor）。
    
3.  渲染效果一般，该有的都有了。
    
4.  界面清晰明了，无过多花哨功能，并且有 markdown 加持，保证专注程度。
    
5.  git 同步点赞👍，省时省力（可结合 GitLab 同步到自己服务器中），且出错时能分析调试信息，保证同步有效性。
    
6.  部分功能解锁价格偏高（月季制度），付费功能偏弱（Play Store 评论区下，作者挺关心收费价格这点的，可以去还价）。
    

总体来说可以，日常够用，同类app中应该是最优选项了。~~哎？Play Store中好像没有同类app…~~