# 锦匣（JinXiaWinToolBox）
    
【中文说明[Github版](https://github.com/tp1415926535/JinXiaWinToolBox#%E9%94%A6%E5%8C%A3jinxiawintoolbox)/[Gitee版](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E8%AF%B4%E6%98%8E%E6%96%87%E6%A1%A3.md#%E9%94%A6%E5%8C%A3jinxiawintoolbox)】
[【English Description】](https://github.com/tp1415926535/JinXiaWinToolBox#jinxia-wintoolbox)    
*(如果这里图片加载失败，可以看Gitee版的说明)*  

![启动动画](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E5%90%AF%E5%8A%A8.png)   

**下载 [v1.0]**   
- 
  即将问世。
- 地址1：[Github]()   
- 地址2：[Gitee]()   
- 地址3：[蓝奏云]()   
   
<br>
   
**说明**   
-   
   
锦匣：Windows轻量工具集。   
当前版本包含以下工具：      
![主界面](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E4%B8%BB%E7%95%8C%E9%9D%A2.png)   
**前台工具**    
- 调色板：调色，颜色格式，取色   
- 比对：  生成文本差异结果   
- 尺：    真实尺寸，任意测量，长度换算   

**后台工具**    
- 窗顶：  置顶或取消，多种置顶方式   
- 速搜：  网站搜索、打开文件（夹）、网址，自动粘贴   
- 性能栏：实时CPU和内存显示，颜色自变   
- 日程：  时间段任务提示，自动切换   
   
<br>
   

**设计理念**
-   
- **锦匣**  
　之前写的想挂在后台的程序太多了，还分开占性能，每个都很随意。  
　统一图标和设置页，更加美观和正式。  
   
- **调色板**   
　通常调色、获取颜色码、转化颜色格式，一般都需要打开绘图软件，过程十分不便，所以把这个功能抽提出来。    
　同时为了更好的调色体验，不同格式（RGB,CMYK,HSB,HEX）的滑块与数值将全部同时显示，并提供了一键复制/粘贴功能。   
　另外还配有屏幕取色功能，颜色实时反馈在调色板中，进一步简化取色步骤。   
　以及一些附属功能，即记录颜色，鼠标坐标，放大取色视野等，将便利贯彻到底！   
 ![调色板界面](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E8%B0%83%E8%89%B2%E6%9D%BF.png)   
   
- **比对**   
　通常要比对两段文字，有两种选择：   
　· 一种是用眼睛看找不同，这太费眼睛，而且容易看漏；   
　· 另一种是新建两个Word文档，分别粘贴进去，然后都保存，最后再打开其中一个，再到菜单栏中找到比对文档的功能，选择刚才保存的两个文档，最后生成一个新文档…… 麻烦到放弃。  
　但是现在完全不需要牺牲眼睛或者时间，只需要简单的粘贴到程序的左右两个文本框，再点击按钮就能生成差异。    
　黑色代表不变文字，红色删除线代表删除文字，蓝色下划线代表新增文字。就是这么简单。
 ![文本比对界面](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E6%AF%94%E5%AF%B9.png)   

- **尺**   
　或许有时候知道一个尺寸，但是你已经没有了长度概念；又或许你想量某个东西，但是手上没有尺子，但是它可以帮你。   
　通过拉伸尺子可以实时得出长宽和面积；也可以预设单位和尺寸，得出真实的长度。   
　当然肯定还有花里胡哨的功能，比如滚轮调节透明度，或者改变尺子颜色等等。   
![尺子界面](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E5%B0%BA.png)    

- **窗顶**   
　这倒是常见，不过同系列程序让我感觉并不友好。    
　在这个工具中，你可以自定义快捷键、改变置顶的作用对象等等。    
　最重要的是，它会在你置顶/取消置顶窗体的时候提示你。     
![置顶提示](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E7%BD%AE%E9%A1%B6.png)    
  
- **速搜**   
　这个确实是有很多优秀的同系列程序。但这个程序的初衷就是便捷直达。   
　不论是搜索网页、打开网址、打开文件（夹），直出结果，不会有多余的选项，并且会自动粘贴复制内容到搜索栏中。   
　之前也用过Win的开始菜单搜索，但它默认用Edge和必应，不习惯。类似Listary这种选择搜索引擎则需要额外输入字符。本工具直接提供搜索引擎的切换，以及自动打开默认浏览器。   
![搜索栏界面](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E9%80%9F%E6%90%9C.png)   
  
- **性能栏**   
　远古时期的360悬浮窗后遗症，总想要看着CPU占用率。现在没装360就另外做了个悬浮窗，颜色也会随着占用率变化，透明度也可调节。   
![性能栏界面](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E6%80%A7%E8%83%BD%E6%A0%8F.png)   
  
- **日程**   
　完全找不到同款才自己开发的便签日程。    
　可以预先设定一天的日程，就能像便签一样挂着只显示当前的任务，并且每到时间会自动通知并切换下一个任务。双击日程还能显示当天日程分布。   
　对于专注和规划生活非常有帮助。    
 日程界面：   
![日程界面](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E6%97%A5%E7%A8%8B.png)     
 切换提示：    
![切换日程提示](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E6%97%A5%E7%A8%8B%E5%88%87%E6%8D%A2.png)     
<br>

**历史版本**   
-   
　**v1.0版**　2021/01

<br>
   
**单体工具链接**   
-   
　如果只想要工具集中的某一个工具，可以关闭其他的功能，或者选择下载单体工具的链接。
- [调色板](https://github.com/tp1415926535/ColorPanel)
- [窗顶](https://github.com/tp1415926535/TopTool)
- [速搜](https://github.com/tp1415926535/QuickSearchTool)
- [性能栏](https://github.com/tp1415926535/PerformanceDisplayWindow)
- [日程](https://github.com/tp1415926535/ScheduleRemindNote)
---

<br><br><br><br><br><br><br><br>

 # JinXia (WinToolBox)
![Launch Animation](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E5%90%AF%E5%8A%A8%20%E8%8B%B1.png)  
    
**Download [v1.0]**  
-  
- Download Link1: [GitHub]()   
- Download Link2: [gitee]()   
- Download Link3: [LAN Zou Yun]()  

**Introduce**  
-  
JinXia: Windows lightweight toolset.   
The current version includes the following tools:   
![MainForm](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E4%B8%BB%E7%95%8C%E9%9D%A2%20%E8%8B%B1.png)   
**Front desk tools**     
- ColorPalette: color matching, color format, color taking
- TextComparator: generate text difference results
- Ruler: real size, arbitrary measurement, length conversion

**Background tools**   
- TopTool: top or cancel, multi top mode
- QuickSearch: website search, open file (folder), web address, automatic paste
- PerformanceDisaplay: real time CPU and memory display, self changing color
- ScheduleNote: time period task prompt, automatic switch
  
**Screen shot**
- 
* ColorPalette   
![ColorPalette](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E8%B0%83%E8%89%B2%E6%9D%BF%20%E8%8B%B1.png)   

* TextComparator   
![TextComparator](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E6%AF%94%E5%AF%B9%20%E8%8B%B1.png)   

* Ruler    
![Ruler](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E5%B0%BA.png)   

* TopTool    
![TopTool](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E7%BD%AE%E9%A1%B6.png)   

* QuickSearch    
![QuickSearch](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E9%80%9F%E6%90%9C%20%E8%8B%B1.png)   

* PerformanceDisaplay    
![PerformanceDisaplay](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E6%80%A7%E8%83%BD%E6%A0%8F%20%E8%8B%B1.png)   

* ScheduleNote    
 NoteForm:   
![ScheduleNote](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E6%97%A5%E7%A8%8B%20%E8%8B%B1.png)   
 Switch Task Tips:   
![Switch Task Tips](https://github.com/tp1415926535/JinXiaWinToolBox/blob/main/%E6%88%AA%E5%9B%BE/%E6%97%A5%E7%A8%8B%E5%88%87%E6%8D%A2.png)

   
**Historical version**
-  
　**v1.0** 2021/01
  
  
**Single tool link**
-
If you only want one tool in the tool set, you can turn off other functions, or select the link to download separate tool.
- [ColorPalette](https://github.com/tp1415926535/ColorPanel)
- [TopTool](https://github.com/tp1415926535/TopTool)
- [QuickSearch](https://github.com/tp1415926535/QuickSearchTool)
- [PerformanceDisaplay](https://github.com/tp1415926535/PerformanceDisplayWindow)
- [ScheduleNote](https://github.com/tp1415926535/ScheduleRemindNote)
