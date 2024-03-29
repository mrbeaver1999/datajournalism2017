## 用不同的可视化工具呈现某一数据集
### 我从kaggle选用的数据集：  
**Greenhouse gas emissions in the Netherlands——Emissions from economic activity according to IPCC guidelines**  
*（荷兰的温室气体排放——根据IPCC经济指南的经济活动排放量）*

### 数据源：
见库文件**IPCC_emissions.csv**

### 所使用的的可视化工具：**Excel、venngage、tableau**

**1.Excel**  
Excel是从小学就开始接触的office工具，同样也是最基础的可视化工具，用起来相对熟悉很多。我将数据CSV源文件导入Excel后，对源数据进行了处理。因为选择的是温室气体排放这一文件，数据中包括“ID（编号）”“Bronnen（Emission source排放物来源）”“Perioden（Period year年份）”以及三类温室气体（CO2、CH4、N2O）每年的排放量（单位为百万千克），根据数据的特点，我决定对编号为0的T001176这一来源地2000-2017年的三类温室气体排放量的年同比增长率进行计算，并将结果转化为折线图进行展现。

**2.Venngage**  
venngage是一款国外免费的可视化工具，也属于比较基础入门且不需要写代码的简易工具，只需要根据你的爱好和需求选择模板进行编辑即可。在制作中也可以添加各式各样风格的text文本框、chart图表，icon标志等等，非常美观且实用，在图表中也可以通过setting来编辑图表，使得图表符合数据需求。但是也遇到了一些小问题，比如数据导入我需要手动输入，似乎不能复制粘贴，也不知道如何从外部导入数据；icon里面的图标加载不出来，加载出来的有很多无法拖到作品里，所以做出来有点丑陋；image上传图片也一直显示在上传中，无法上传成功，不知道是什么原因。但总体来说，venngage还是很适合我这个可视化傻瓜学生的。

**3.Tableau**  
Tableau同样也是一款国外的可视化工具，致力于帮助人们查看并理解数据。Tableau 帮助任何人快速分析、可视化并分享信息。新用户可以免费试用14天，正好拿来做了可视化的作业。Tableau也是一款比较容易上手的工具，只用在数据源中导入数据，在工作簿中选择你所需要的添加的字段并添加到工作区域内的相应部分即可。还会有智能显示帮助你挑选最适合的图表形式，还可以自定义字体、颜色、布局、形状等要素，只需要进行简单的拖动即可，非常简单便捷，并且它还会根据你数据源的变化实时进行变化，唯一的小问题是因为我计算的是增长率，在Excel中是一个百分比格式的数据，但tableau似乎不支持百分比格式的数据，自动转化为了数值格式，就不得不在Y轴重新标注了单位。但总体来说，做出来的效果图还是比较美观，用了之前下载的字体也显得不那么枯燥。但是相较于venngage来说，tableau我目前还没发现是否能做成像venngage那样类似海报式的样子，只能以单纯的图表呈现，无法配文本框和其他图案。

## 图表呈现(excel/venngage/tableau)
![excel](https://github.com/mrbeaver1999/datajournalism2017/blob/master/Excel%E5%9B%BE%E8%A1%A8.png)
![venngage](https://github.com/mrbeaver1999/datajournalism2017/blob/master/venngage%E5%9B%BE%E8%A1%A8.png)
![tableau](https://github.com/mrbeaver1999/datajournalism2017/blob/master/tableau%E5%9B%BE%E8%A1%A8.png)
