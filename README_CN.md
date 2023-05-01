# JASIST-KU-dataset
The datasets of the knowledge unit for the Journal of the Association for Information Science and Technology (JASIST)



# 数据标注体系：

知识单元的细粒度层级上包括**句子层级**和**实体层级**。

## 句子层级

### **（1）研究问题**

研究问题指文章想要解决的问题。此处的研究问题指在学术全文本中指明文献研究问题的句子。

```
Example1：

10.1002/asi.22617-2-24 Now , we come to the main point of our article , namely , the relation between the h-index h and the impact factor IF ( average number of citations per publication ) in the shifted Lotka model .

Example2：

10.1002/asi.22618-1-8 The purpose of this article is to report the development and the evaluation of an automated semantic annotation system ( called CharaParser ) that is designed to overcome the scalability problem in manual annotation and to promote adaptability of the system across various taxon groups .

Example3：

10.1002/asi.22622-1-12 This article focuses on these ill-defined information contexts, where it aims at presenting a method and tool for information slaves to become emancipated from masters ' attempts to dictate a truth .
```



### **（2）研究方法**

研究方法指关于解决应用领域问题的**方法、工具、手段、技术和方案**。此处的研究方法指在学术全文本中指明文献研究方法的句子。

```
Example1：

10.1002/asi.22638-2-9 Another approach is to focus on a small subset of websites to build a linking subgraph based on the small websites subset as vertices , and specifying the edges between these websites

Example2：

10.1002/asi.22620-2-37 The visibility of the articles was analysed through a normalization of the citation per paper .

Example3：

10.1002/asi.22620-2-6 Topic searches are a common technique used to analyse growth and trends in the scientific literature of specific subject areas .
```



### **（3）研究结果**

研究结果指文章实验得出的结果和结论。此处的研究结果指在学术全文本中指明文献研究结果的句子。

```
Example1：

10.1002/asi.22617-4-2 In this article , we presented , based on a shifted power model , an implicit relation between the h-index and the total number of sources , and between the h-index and the impact factor ( average number of items per source ) .

Example2：

10.1002/asi.22617-4-3 In this way , we extended earlier work to the case that the impact factor can have a value lower than one .

Example3：

10.1002/asi.22617-4-4 Although the relation between the h-index and the impact factor looks roughly linear , their relation ( in the shifted power model ) is not linear at all .
```



### **（4）研究展望**

研究展望指文章某些方面的研究还不够深入，还存在问题有待进一步解决等。此处的研究展望指在学术全文本中指明文献研究展望的句子。

```
Example1：

10.1002/asi.22617-4-5 We hope that the shifted model may help in explaining observed phenomena .

Example2：

10.1002/asi.22617-4-6 In this context , we refer to our own work where , indeed , inclusion of a zero class would probably have improved the presentation .

Example3：

10.1002/asi.22617-4-7 We hope to be able to do this in the near future .
```



## 实体层级

### **（1）研究对象**

研究对象指研究所探讨的问题，研究方法的作用目标等。一般是一组名词性结构短语。

```
标注范例1：

Experiments on three datasets in the biomedical domain suggest the performance of different weighting methods depends on whether it is an abstract or full text environment.

标注范例2：

Understanding search behavior is important and leads to	more effective interfaces that support searchers throughout	the	search process.	
```



### **（2）研究方法/技术**

研究方法/技术是指研究所采用的方法技术的名称，涉及具体算法模型、理论模型的不纳入此项实体类型。

```
标注范例1：

10.1002/asi.22638-2-9 Another approach is to focus on a small subset of websites to build a linking subgraph based on the small websites subset as vertices , and specifying the edges between these websites

标注范例2：

10.1002/asi.22620-2-37 The visibility of the articles was analysed through a normalization of the citation per paper .

标注范例3：

10.1002/asi.22620-2-6 Topic searches are a common technique used to analyse growth and trends in the scientific literature of specific subject areas .
```




### **（3）工具**

一般意义上的工具，即现有的可直接使用的各类软件工具包，包括统计分析软件、信息计量、科学计量与可视化软件工具、自然语言处理工具、编程语言等。

```
标注范例1：

10.1002/asi.22618-6-43 This set of results seems to suggest that CharaParser may do away with the HR3 and HR4 adjustments , making the program more efficient .

标注范例2：

10.1002/asi.22618-6-44 In other words , POS-tagged domain terms alone may be sufficient in adapting Stanford Parser for the biosystematics domain .

标注范例3：

10.1002/asi.22618-1-43 SDD is used by key generation software such as Lucid to generate organism identification keys .
```



### **（4）模型**

各类算法与模型，包括理论模型、算法模型等。

```
标注范例1：

10.1002/asi.22618-3-8 The classification algorithm used was semisupervised co-expectation maximization ( EM ) with supervised Naïve Bayesian classifier .

标注范例2：

10.1002/asi.22621-1-10 Methods relying on supervised machine learning train classifiers ( support vector machines , random forests , etc. ) on a hand-labeled training set containing pairs of articles where similarly named authors are identified as being the same or different persons .

标注范例3：

10.1002/asi.22621-1-14 Unsupervised algorithms , by contrast , require no hand-labeled training data , instead defining a metric of similarity between pairs of articles and applying an unsupervised clustering algorithm such as k-means or spectral clustering.
```




### **（5）评价指标**

评价指标是指一项研究或实验对于研究结果的合适评价标准、指标，包括统计学指标、计量学指标和模型性能评估指标等。

```
Example1：

This model will facilitate better search and retrieval of the information contained within these vast story universes for all users interested in them . 

Example2：

The	partially known and exploratory	task types showed similar distributions for rating and accuracy .	
```



### **（6）数据资源与平台**

此处的数据资源与平台，包括研究采用的通用数据集或公开数据集名和研究人员所采集数据的来源两类，即“数据源”和“数据集”。

```
Example1：

10.1002/asi.22620-2-42 The adapted version is relatively easy to calculate using the online version of the Science Citation Index (SCI ) .

Example2：

10.1002/asi.22623-5-7 Three standard news corpora, Reuters 21587, TDT1 and TDT2, are used.

Example3：

10.1002/asi.22609-2-63 As suggested in previous studies, we used names and affiliations in combination to identify the right person in the DBLP.

Example4：

10.1002/asi.22626-3-53 A subset of the data gathered from Aug City was used for this article .
```



# 数据发布

数据集包含四部分：

1.知识图谱：基于关联数据的“实体-关系”知识图谱。

2.研究句子数据集：包含2010-2020.6月的全文数据。

3.知识实体数据集：包含部分摘要数据、人工加工校对过。

4.摘要数据集（句子+实体）：全部摘要数据的标注数据集。



### 数据引用

相关论文尚未发表，若使用本数据集，可暂时使用该项目的github项目网页链接作为引用对象。



### 声明

数据集仅可用于学术研究使用，未经作者允许不可用于商业用途。

作者团队不就使用该数据集造成的任何分析结果、民事纠纷负责。

