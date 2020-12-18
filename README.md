# 写在前面

### ☉关于作者

 作者并非专业前端人员，仅自学过一段时间css，因为无法接受百度轻因为百度更新影响导致的界面崩溃，故尝试修改。

 可能代码质量并不能和真正的前端人员相比，但是我依旧在尽力去学习CSS这个语言，也希望再未来可以将更好的视觉体验带给大家。

 作者同时为一名高三学生，需要参加2021届的高考，时间有限，如果出现新的bug可能并不能及时更新，请见谅。

 顺便再打个广告，https://github.com/zhuozhiyongde/Alfred_HeWeather_Workflow，这是我自己写的一个Alfred查询天气的workflow，如果有mac用户有这方面的需求可以下载哦~



### ☉关于反馈

 Stylish反馈太垃圾了，新建了一个石墨文档，如果有意见/需求请到此反馈：https://shimo.im/docs/YgJ9grYK8kvRwYjK

 

### ☉关于代码

 本代码依托Baidu Lite构筑，加入了相当一部分的我自己的代码，以适应百度样式的更新/加入新功能/融合我的理解。

 本代码开源，且允许自行修改、构筑新的分支。

 部分代码来自于@CWorld的Pure Baidu，也是一个很棒的百度样式，不仅支持搜索界面还支持其他百度站点，推荐下载（如果觉得他的更好就不用下这个了）

部分代码改编自Baidu Lite，再次致谢@pan_cao。



# 更新历史

### Baidu Art V2.0.5

- 修复了分辨率大于1920px时的bug问题。



### Baidu Art V2.0.4

- 月考终于考完了，明天就要和电脑说拜拜了，抓紧时间爆肝出来了百度知道的搜索/主页/结果三大页面的美化，均是类比着百度轻做的哦！
- ↑换用MacBookAir预先体验了一下，查出来不少bug，头秃，改了半天终于改完了，希望大家使用愉快~



### Baidu Art V2.0.3

- 诈尸处理了一下这段时间收到的问题，由于缺乏Windows测试环境，可能会导致macOS上我认为已经修复的Bug在Windows下复现，如果出现，请留言。
- 增添了对于百家号页面的适配。
- 距离高考越来越近，考试也越来越频繁了，下次更新可能遥遥无期，先对大家说声抱歉了！



### ﻿Baidu Art V2.0.2

- 临时诈尸一天修改了部分卡片的选择问题、长度不等问题。
- 删去了饱受诟病的背景（其实我是蛮喜欢的…），但源代码就在第一部分Line 97，如果你想自定义可以自行修改！
- 关于反应的百度多栏无法使用的问题，很抱歉代码存在冲突，我先把这个需求记下啦，以后可能增添多栏功能。
- 其他问题暂无精力修复，请等待至十一假期，届时我会抽空修复最近的bug。



### Baidu Art V2.0.1

- 修改了加入背景后的若干bug，包括为顶栏导入背景等。
- 任然没有搞清楚选项怎么用，默认设置了隐藏站点栏，和一个天空背景，如果需要更改，请参照第一部分的注释修改。更改隐藏策略请修改第50-79行，首先删去选项1-3部分的代码，然后按照注释取消被注释的代码；背景请更改第84行，删去即默认#F1F1F1纯色背景，或者在Url里填入你的自定义背景。



### Baidu Art V2.0.0

> 重写了整个样式，现在可以独立于百度轻原样式工作了。

> What'new:
>
> - 适配了百度最新的更新（内容右549px变化至560px，标题栏字号加大等），恢复了原有格式。 ·重新按照body、content、tab三个分支构建了代码，保留了百度轻原有代码中的关键部分，并且加入了相当一部分的独立代码。
> - 更改了首页视图。（存在一个小Bug，搜索建议如果从首页跳转不会显示，需要刷新一下哦）
> - 可以修改背景了（但是不建议），修改方法为删除第7行的注释并且填入在任意图床获取的url图片，推荐路过图床，免登陆，最高上限10MB。
> - 取消了站点栏的显示，因为我实际体验根本用不上，未来可能对此增加选项（下次更新可能要等很久，因为我目前要准备高考，见谅）。 顺便再打个广告，[https://github.com/zhuozhiyongde/Alfred_HeWeather_Workflow](https://github.com/zhuozhiyongde/Alfred_HeWeather_Workflow，这是我自己写的一个Alfred查询天气的workflow，如果有mac用户有这方面的需求可以下载哦~)，这是我自己写的一个Alfred查询天气的workflow，如果有mac用户有这方面的需求可以下载哦~
> - 部分代码（标题选中特效）来自于@CWorld的Pure Baidu，也是一个很棒的百度样式，不仅支持搜索界面还支持其他百度站点，推荐下载（如果觉得他的更好就不用下这个了，当然我高考完也会抽出时间向大佬学习，适配百度的其他的网页，但是这个比较远了） 部分代码改编自Baidu Lite，再次致谢@pan_cao。
>
> ﻿



### Baidu Lite Repair V1.0.1

- 修复刚才发现的搜图时UI没有改变的问题。
- Safari用户可能需要手动调整.soutu-layer .soutu-url-btn{}处的margin-left值为50px，使得放大镜图标对齐。（原因是似乎Safari和Chrome的像素值不太一样？很怪。考虑到大多数人用Chrome，先以Chrome的为准。以后考虑增添浏览器选项以适配吧。）



### Baidu Lite Repair V1.0.0

修复@pan_cao的百度轻（https://userstyles.org/styles/123858/baidu-lite）由于最近百度UI更新导致的元素错位、部分失效问题。

前言：作者并非专业前端人员，仅自学过一段时间css，因为无法接受百度轻因为百度更新影响导致的界面崩溃，故尝试修改。能力、时间有限，如果出现新的bug请见谅。

由于尚未摸清楚css动画的实现，需要删除百度轻样式中的部分代码：

原百度轻代码内323-409行需要删去,目的是删去放大镜图标的贝塞尔曲线动画。

即.s_btn{}一直到.btnhover{}Baidu Lite Repair V2.0.1



# Issue/Request 问题/反馈区

### Issue1：百度主页https://www.baidu.com/的百度icon好像错位了

> 修复进度：修复完毕。



### Issue2：主页icon还是错位的，搜索界面参差不齐，建议能自己更改背景

- [图片1](https://s1.ax1x.com/2020/08/31/dL45hn.png)、[图片2](https://s1.ax1x.com/2020/08/31/dL5EAH.png)（新版Edge 85.0.564.41）

```
作者说：该问题已经通过Surface-Chrome上部分确认，包括卡片错位（个别卡片没有选择上），icon重叠且放大未得到确认，我想大概是不同浏览器css语法不同导致的bug，并且发现了在现有测试条件下，搜索图标不加载的新bug。
macOS下的Chrome、Safari仍保持正常。
Edge浏览器需要下载再检查。
目前缺乏时间去修复，预计下一次修复时间为十一假期，十分抱歉。
更改背景请参见版本更新说明，哪里有具体的方法可供参考。
```

> 修复进度：已知问题修复完毕（卡片错位），icon重叠无法确认。

﻿

### Issue3：搜索结果卡片错位，但还是能接受滴……

我是和“百度多栏”@[creampie](https://userstyles.org/users/312500)（https://userstyles.org/styles/127217/theme）联合使用的。



![img](https://uploader.shimo.im/f/bCzjYIk691nPXdnM.png!thumbnail)

还有不知道为什么……首页变成这样了@_@

![img](https://uploader.shimo.im/f/Iwwjn297gvzxaywE.png!thumbnail)

更不更新，，不着急……高考为重，加油鸭，快滚去学习23333

```
作者说：感谢使用。导致该bug出现的原因是两个样式存在代码冲突，请暂时卸载百度多栏样式以获得更好的视觉体验，有关多行的需求我收到啦！图标icon的显示在现有测试条件下并未确认，但这不是个例，我会想办法的。
有关学习，感谢您的提醒~
```

> 修复进度：预计增添需求（多行）。

﻿

### Issue4: 几个不成熟的小意见

高分屏(2k)单独进行更改搜索框尺寸,建议在400px-600px之间,搜索结果页建议将分块margin设置在5-10px,高分屏下间隙太大了,然后将nums_text的Color属性由#999改为白色或黑色,背景是浅色不容易看到灰色字体。

```
作者说：目前设备支持的最大分辨率1920x1200px（13寸MacBookPro）下，该样式工作良好。我现在缺乏win系统及高分屏的测试条件，如果您愿意的话，欢迎与我联系，帮我进行测试、定位等工作，如果可以的话请联系我（zhuozhiyongde@126.com）
```

> 修复进度：预计增添需求（高分屏适配）。



### Issue 5: 搜索结果页

> Google Chrome （iMac 5k）

以下代码导致宽度分辨率高于1920px时居中偏移

```
@media screen and (min-width:1921px){
  #container.sam_newgrid{ padding-left:158px; }
}
```

 

![img](https://uploader.shimo.im/f/MQqxXArNK2I8WAUU.png!thumbnail)

```
作者说：已经确定存在问题，并进行了修复，V2.0.5版本不再有此问题。
```

> 修复进度：完成修复
