# 更新亮点

（[BrassicaEDB](https://brassicaedb.com/#/search/expression) ）**Gene Expression模块[1]更新 | 芸苔属基因表达分析**<br>

今天我们为大家介绍BrassicaEDB 2.0 平台的**Gene Expression模块**。我们团队对芸苔属研究需求进行了深入思考，经过多次讨论和迭代，本次更新重点解决了以下问题：<br>
① **操作简化**：设计了一站式表单面板，支持快速选择物种和输入基因 <br>
② **数据整合**：整合多个高质量RNA-seq项目，覆盖根、茎、叶、花、种子等组织<br>
③ **结果可视化**：提供四大动态图表，满足不同分析需求<br>

现在，让我们从最基础的操作开始，快速上手这个模块。

![](https://files.mdnice.com/user/64884/c8a19420-25d2-49f7-9fa2-f5995b90d3e0.png)


# 模块介绍

在中心法则中，基因转录是将遗传信息从 DNA 传递到 RNA 的重要环节，而 **RNA-seq 技术** 能够精确测量基因的转录水平，追踪其在不同组织、发育阶段或处理条件下的表达变化，甚至发现新的转录本和可变剪接事件。研究基因表达可以帮助我们解决这些问题：<br>

- 比较同一基因在不同部位或不同阶段的表达情况
- 比较不同基因在相同部位或阶段的表达差异
- 对不同的处理或胁迫条件，推测可能存在的调控机制


![](https://files.mdnice.com/user/64884/290b3d70-5f78-466a-853d-352948892f03.png)

# 模块使用

## 输入区域

我们设计了一个简洁直观的表单面板，只需三步即可开启基因表达分析：<br>
① **选择物种**：支持六大芸苔属作物一键切换<br>
② **输入基因**：粘贴基因ID或使用示例基因快速体验<br>
③ **检索项目**：默认推荐胚发育数据集，支持自定义筛选<br>

大家可以选择对应的物种和输入感兴趣的基因。在默认情况下，每个物种都有一个推荐的项目提供检索。这里我们简单演示一下。

![](https://files.mdnice.com/user/64884/92b9f87e-2f37-46b8-82f2-f23605dc0e1b.png)



### Step1: 物种与基因输入

首先我们切换不物种，查看示例基因的结果。同时，输入框支持自行粘贴基因，页面将自动识别并切换到对应物种。<br>

- **两种输入模式**：<br>
  ①直接粘贴基因ID（自动识别物种）<br>
  ②点击"示例"按钮，快速体验（推荐新手）<br>
- **智能提示**：输入框实时校验基因ID格式<br>

![](https://files.mdnice.com/user/64884/121adae8-c3bc-45be-8ae9-d4109d31e109.png)


### Step2: 项目筛选

我们为每个物种精选了**默认项目**（PRJNA641876），这是目前较为完整的芸苔属胚发育时空表达图谱。点击【More Projects】按钮，可探索更多项目。<br>


![](https://files.mdnice.com/user/64884/cfe2b716-c8b8-42fd-bf67-89c09a69420b.png)


我们此次更新最大的亮点是，提供了178 份不同的项目让用户自行选择感兴趣的组织和处理，来检索目标基因的表达情况，实现了：<br>

- **多维度筛选**：<br>
   按组织类型：根、茎、叶、花、种子等12类<br>
  按实验处理：正常条件、非生物胁迫、生物胁迫等3类<br>

- **灵活扩展**：点击【+】按钮，探索更多组织数据<br>


![](https://files.mdnice.com/user/64884/c4435417-bb5e-4c41-ad30-69d451beebc6.png)


- **项目直通NCBI**：点击编号即可查看原始数据详情<br>


![](https://files.mdnice.com/user/64884/119207b3-77d7-47d1-b2aa-7004640f156a.png)



### Step3: 提交检索

选择目标项目后：<br>

- 可在左侧输入区域看到当前选中项目和简介<br>
- 点击【Search】按钮，即可得到结果页面<br>


## 结果区域

在提交检索后，进入结果页面。基于基因的检索结果，我们不仅提供了详细的表达量数据，还配备了趋势图、热图、箱线图、柱形图等四大动态图表，帮助大家从不同角度解读基因表达模式。


![](https://files.mdnice.com/user/64884/c9ddebfe-3f66-42f6-b0e2-9946304d1e05.png)




### **图表工具**

每个图表右上角均配备实用工具：

- **原始数据查看**：可查看完整的原始数据
- **分区域截屏**：精准保存目标区域
- **图表转换**：不同类型图表自由切换
- **结果保存**：支持PNG格式下载保存


![](https://files.mdnice.com/user/64884/e5c60ff6-8a58-4849-ba60-ae32dea833bd.png)




### 表达量表格

- **固定Gene ID列**：方便快速定位目标基因<br>
- **横向滑动查看**：支持浏览完整样本的TPM值<br>



![](https://files.mdnice.com/user/64884/bddc4d6f-bdd1-451f-ab3f-80639839a5e3.png)



###  **四大图表：多维度解读**

在结果区域，我们提供了四种动态图表，帮助大家从不同角度分析基因表达数据。

| 图表类型 | 适用场景     | 特色功能           |
| :------- | :----------- | :----------------- |
| 趋势图   | 发育动态分析 | 直观显示表达趋势   |
| 热图     | 多基因比较   | 优化配色方案       |
| 箱线图   | 组间差异统计 | 展示数据分布       |
| 柱状图   | 特定样本对比 | 直观展示数据量高低 |


#### ① 趋势图：追踪发育动态

**适用场景**：分析基因在不同发育阶段的变化<br>

**特色功能**：直观显示表达趋势<br>

![](https://files.mdnice.com/user/64884/ae304b17-d2df-453f-9b1a-4a0b8661f9b7.png)


#### ② 热图：多基因快速比较

**适用场景**：比较多个基因在不同样本中的表达模式<br>

**特色功能**：优化配色方案，突出重点数据；可查看原始数据<br>


![](https://files.mdnice.com/user/64884/9c1f3603-0fd1-4389-8b0c-0e4b5fc77928.png)


#### ③ 箱线图：揭示组间差异

- **适用场景**：统计不同处理组间的表达差异<br>
- **特色功能**：清晰展示数据分布范围和中位数，便于组间比较<br>

![](https://files.mdnice.com/user/64884/c024a9a4-c5fc-4dcf-8d91-19e99006fc59.png)


#### ④ 柱状图：精准样本对比

- **适用场景**：比较特定样本或处理条件下的表达量<br>
- **特色功能**：直观展示表达量高低，便于快速对比<br>
![](https://files.mdnice.com/user/64884/e6b03643-f721-4acc-8cc5-ec1030c165fe.png)


### 结果保存

在图表的右上角，点击【<u>↓</u>】下载按钮，即可保存结果图片到本地。


![](https://files.mdnice.com/user/64884/c1f1394a-e861-446d-a7e5-6cea6cf45976.png)


# 结语

通过以上步骤，相信大家已经掌握了**Gene Expression模块**的核心使用方法。我们团队将持续更新更多模块的使用教程，并不断优化平台功能。<br>

##  **相关资源**


- **网站直达**：[BrassicaEDB](https://brassicaedb.com/#/search/expression)<br>
- **GitHub仓库**：[yuhong2024/brassicaedb](https://github.com/yuhong2024/brassicaedb)（欢迎Star🌟支持！）<br>
------

##  **问题反馈**

如果大家在使用过程中遇到任何问题，或有改进建议，欢迎通过以下方式联系我们：<br>

- **邮箱**：[wyhstar@email.swu.edu.cn](mailto:482218016@qq.com)<br>
- **GitHub Issues**：提交问题至仓库 [2] <br>

------
###  **相关链接**

[1] [BrassicaEDB Gene Expression](https://brassicaedb.com/#/search/expression)<br>
[2] [GitHub Repository](https://github.com/yuhong2024/brassicaedb)<br>


期待你的反馈与参与，让我们一起推动芸苔属研究的进步！ 🌱<br>

##  **往期回顾**
