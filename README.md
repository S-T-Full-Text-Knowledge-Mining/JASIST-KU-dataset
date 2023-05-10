# JASIST-KU-dataset

The datasets of the knowledge unit for the Journal of the Association for Information Science and Technology (JASIST)



# Data annotation system：

The fine-grained level of knowledge units includes sentence level and entity level .

## Sentence hierarchy

### **（1）Research questions**

Research problem refers to the problem that the article aims to solve. The research question here refers to the sentence indicating the literature research question in the academic full-text.

```
Example1：

10.1002/asi.22617-2-24 Now , we come to the main point of our article , namely , the relation between the h-index h and the impact factor IF ( average number of citations per publication ) in the shifted Lotka model .

Example2：

10.1002/asi.22618-1-8 The purpose of this article is to report the development and the evaluation of an automated semantic annotation system ( called CharaParser ) that is designed to overcome the scalability problem in manual annotation and to promote adaptability of the system across various taxon groups .

Example3：

10.1002/asi.22622-1-12 This article focuses on these ill-defined information contexts <cit> , where it aims at presenting a method and tool for information slaves to become emancipated from masters ' attempts to dictate a truth .
```



### **（2）Research methods**

Research methods refer to **methods, tools, means, technologies, and solutions** for solving problems in the application field. The research method here refers to the sentence indicating the literature research method in the academic full-text.

```
Example1：

10.1002/asi.22638-2-9 Another approach is to focus on a small subset of websites to build a linking subgraph based on the small websites subset as vertices , and specifying the edges between these websites

Example2：

10.1002/asi.22620-2-37 The visibility of the articles was analysed through a normalization of the citation per paper .

Example3：

10.1002/asi.22620-2-6 Topic searches are a common technique used to analyse growth and trends in the scientific literature of specific subject areas .
```



### **（3）Research results**

The research results refer to the results and conclusions drawn from the experiment in the article. The research results here refer to the sentences that indicate the literature research results in the academic full-text.

```
Example1：

10.1002/asi.22617-4-2 In this article , we presented , based on a shifted power model , an implicit relation between the h-index and the total number of sources , and between the h-index and the impact factor ( average number of items per source ) .

Example2：

10.1002/asi.22617-4-3 In this way , we extended earlier work to the case that the impact factor can have a value lower than one .

Example3：

10.1002/asi.22617-4-4 Although the relation between the h-index and the impact factor looks roughly linear , their relation ( in the shifted power model ) is not linear at all .
```



### **（4）Research prospects**

Research outlook refers to the lack of in-depth research on certain aspects of the article, and there are still issues that need to be further addressed. The research outlook here refers to the sentence indicating the literature research outlook in the academic full-text.

```
Example1：

10.1002/asi.22617-4-5 We hope that the shifted model may help in explaining observed phenomena .

Example2：

10.1002/asi.22617-4-6 In this context , we refer to our own work where , indeed , inclusion of a zero class would probably have improved the presentation .

Example3：

10.1002/asi.22617-4-7 We hope to be able to do this in the near future .
```



## Entity level

### **（1）Research subjects**

The research object refers to the problems explored by the research institute, the purpose of the research method, etc. Generally, it is a group of noun structured phrases.

```
Example1：

Experiments on three datasets in the biomedical domain suggest the performance of different weighting methods depends on whether it is an abstract or full text environment.

Example2：

Understanding search behavior is important and leads to	more effective interfaces that support searchers throughout	the	search process.	
```



### **（2）Research methods/techniques**

Research methods/technologies refer to the names of the methods and technologies used in the research, and those involving specific algorithm models and theoretical models are not included in this entity type.

```
Example1：

10.1002/asi.22638-2-9 Another approach is to focus on a small subset of websites to build a linking subgraph based on the small websites subset as vertices , and specifying the edges between these websites

Example2：

10.1002/asi.22620-2-37 The visibility of the articles was analysed through a normalization of the citation per paper .

Example3：

10.1002/asi.22620-2-6 Topic searches are a common technique used to analyse growth and trends in the scientific literature of specific subject areas .
```




### **（3）Tools**

Tools in general, namely, existing software toolkits that can be used directly, including statistical analysis software, information metrology, scientific metrology and visualization software tools, natural language processing tools, programming languages, etc.

```
Example1：

10.1002/asi.22618-6-43 This set of results seems to suggest that CharaParser may do away with the HR3 and HR4 adjustments , making the program more efficient .

Example2：

10.1002/asi.22618-6-44 In other words , POS-tagged domain terms alone may be sufficient in adapting Stanford Parser for the biosystematics domain .

Example3：

10.1002/asi.22618-1-43 SDD is used by key generation software such as Lucid to generate organism identification keys .
```



### **（4）Model**

Various algorithms and models, including theoretical models, algorithm models, etc.

```
Example1：

10.1002/asi.22618-3-8 The classification algorithm used was semisupervised co-expectation maximization ( EM ) with supervised Naïve Bayesian classifier .

Example2：

10.1002/asi.22621-1-10 Methods relying on supervised machine learning train classifiers ( support vector machines , random forests , etc. ) on a hand-labeled training set containing pairs of articles where similarly named authors are identified as being the same or different persons .

Example3：

10.1002/asi.22621-1-14 Unsupervised algorithms , by contrast , require no hand-labeled training data , instead defining a metric of similarity between pairs of articles and applying an unsupervised clustering algorithm such as k-means or spectral clustering.
```



### **（5）Evaluation indicators**

Evaluation indicators refer to the appropriate evaluation criteria and indicators for the research results of a study or experiment, including statistical indicators, metrology indicators and model performance evaluation indicators.

```
Example1：

This model will facilitate better search and retrieval of the information contained within these vast story universes for all users interested in them . 

Example2：

The	partially known and exploratory	task types showed similar distributions for rating and accuracy .	
```



### **（6）Data Resources and Platforms**

The data resources and platforms here include two categories: the common dataset or public dataset names used in the research, and the sources of data collected by the researchers, namely "data sources" and "datasets".

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



# Data Release

The dataset consists of four parts:

1. Knowledge Graph：

   "Entity-relationship" knowledge graph based on Linked Data.

2. Research sentence dataset: 

   Contains full-text data from 2010 to June 2020.

3. Knowledge entity dataset:

   Contains partial abstract data, manually processed and proofread.

4. Abstract dataset (sentences + entities): 

   All abstract data dataset.




### Data citation

The related paper has not been published yet, so if you use this dataset, you can temporarily use the link to the GitHub project page of this project as the citation object.



### Disclaimer

The dataset may be used for academic research purposes only and should not be used for commercial purposes without the permission of the authors.

The author team is not responsible for any analysis results or civil disputes resulting from the use of this dataset.



## How to request data

If you want to obtain data, you can send an email to contact us.

Email: jisuanyuyan@163.com
