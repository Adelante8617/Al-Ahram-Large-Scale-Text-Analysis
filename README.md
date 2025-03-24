# 《金字塔报》在2011年埃及革命中的话语分析： 
## 基于大模型的大规模文本挖掘研究

# Al-Ahram: Large Scale Text Analysis

本项目为 **北京大学[第三十三届“挑战杯”系列](https://bbs.pku.edu.cn/v2/post-read.php?bid=454&threadid=18858837)赛事作品**

## 作者
黄柏喻 @[Adelante8617](https://github.com/Adelante8617)

沈靖期 @[blukyshen](https://github.com/blukyshen) 

翁维

## 关键词

大语言模型, 数字人文, 埃及社会, 大规模文本处理

## 作品简介

本研究以2011年埃及革命前后的[《金字塔报》(The Al-Ahram)](https://english.ahram.org.eg/)为研究对象，结合文本挖掘技术和批判性话语分析理论，探讨该报纸在革命中的话语演变。研究基于《金字塔报》的OCR文本结果，设计算法调用大语言模型，降低OCR识别错误对文本处理的影响。通过大规模文本挖掘，我们分析了该报纸如何在革命不同阶段塑造政府与抗议者的形象，揭示了其话语立场的动态变化。

研究发现，报纸在革命初期的报道倾向政府，强调抗议活动的破坏性、突出安全部队的维护作用。随着革命的推进，该报纸逐渐调整话语策略，对抗议者的正面描述增多，并在后期倾向支持革命。本文还分析了该报纸在更长时段内话语的演变，揭示其如何适应革命前后社会权力结构的变化，并考察了其商业化、公共服务化转型及言论自由相关报道的变化。研究表明，在埃及社会权力结构调整的过程中，媒体话语不仅反映了政治动荡，也受到了商业、公共服务及言论自由等领域的显著影响。

方法论方面，本研究采用关键词共现分析、情感极性分析等量化手段，验证了“从粗到细的文本检索-理解”模式的可行性，并展示了前沿数字技术与经典人文理论结合的研究潜力。此外，本研究基于阿拉伯语文本，为大模型在处理阿拉伯语等低资源语言方面提供了宝贵的参考。

## 数据结果

部分结果在 [HuggingFace 仓库](https://huggingface.co/datasets/Adelante/arabic-qa-largebatch).

## 部分结果可视化

我们的图像主要使用Matplotlib、Seaborn、Plotly.js 制作。

对图像内容的解读见论文。

### 关键词共现热力图（*点击图片跳转至可交互版本*）

<a href="https://adelante8617.github.io/Al-Ahram-Large-Scale-Text-Analysis/heatmap.html">
   <img src="https://github.com/Adelante8617/Al-Ahram-Large-Scale-Text-Analysis/blob/main/docs/heatmap_static.png" alt="Heatmap" width="800" />
</a>

### 归一化的主题-情感分布图

<img src="https://github.com/Adelante8617/Al-Ahram-Large-Scale-Text-Analysis/blob/main/docs/Normalized%20Emotion%20Distribution.png" alt="Sentiment-Topic Co-occurence" width="800" />

### 情感度量重设前后堆叠的类别分布图

<img src="https://github.com/Adelante8617/Al-Ahram-Large-Scale-Text-Analysis/blob/main/docs/stacked_bar_chart.png" alt="Stacked Types Comparison" width="800" />

## 扩展本工作至其余课题

我们编写了一个可扩展至任意课题的异步调用大模型案例，参见本仓库下的[demo](https://github.com/Adelante8617/Al-Ahram-Large-Scale-Text-Analysis/blob/main/Demo_for_future_use.ipynb)。

我们相信这样的结果有助于人文学科的学者、学生能轻松高效地批量调用大语言模型，充分发挥数字人文的技术潜力。

## 致谢

感谢苏祺老师对本项目的支持和指导！
