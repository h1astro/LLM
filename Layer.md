## 6.1 简介
在这个教程中，我们将探讨法律对大型语言模型的开发和部署有何规定。我们将会按照以下的步骤进行讨论：

1. **新技术与现有法律的关系**

    与我们之前的讲座一样，比如关于社会偏见的讲座，我们将要讨论的很多内容并不一定特指大型语言模型（并没有特别的大型语言模型法律条例）。然而，每当有新的强大的技术出现，它都会引发很多关于现有法律是否仍然适用或有意义的问题。例如，随着互联网的重要性日益提高，[互联网法律](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3191751)（或称为网络法）应运而生。它从现有的领域中汲取知识，如知识产权法，隐私法，和合同法等。

2. **互联网的独特挑战**

3. **法律与道德的区别**

4. **法律的管辖权问题**

5. **法律的类型**

6. **大型语言模型**
    我们将会把注意力转向大型语言模型。回忆一下大型语言模型的生命周期：收集训练数据，训练大型语言模型，将其适应到下游任务，向用户部署语言模型。

    在大型语言模型的生命周期中，有两个主要领域与法律交叉：数据和应用。

7. **数据**

    所有的机器学习都依赖于数据。语言模型依赖于大量的数据，尤其是为其他

8. **应用**
    语言模型可以被用于广泛的下游任务（例如，问答，聊天机器人）。技术可能被有意用于伤害（例如，垃圾邮件，网络钓鱼攻击，骚扰，假新闻）。现有的互联网欺诈和滥用法律可能覆盖其中的一部分。他们可以被部署在各种高风险的环境（例如，医疗，贷款，教育）。现有的在相关领域的规定（例如，医疗）可能覆盖其中的一部分。

## 6.2 版权法

大型语言模型或任何机器学习模型，都是基于数据进行训练的，而这些数据是人类劳动的结果（例如，作者，程序员，摄影师等）。除了创作者外，其他人可以对这些创作（例如，书籍，代码，照片等）进行何种使用，属于知识产权法的范畴。

### 6.2.1 知识产权法

其动机是鼓励创建各种类型的知识产品。如果任何人都可以利用你的辛勤劳动并从中获利，人们就会对创造或分享失去动力。知识产权包括：版权，专利，商标，商业秘密。

### 6.2.2 许可

许可（来自合同法）是由许可人授予许可使用者的。实际上，“许可就是承诺不起诉”。创作共享许可，允许免费分发版权作品。[例如](https://en.wikipedia.org/wiki/List_of_major_Creative_Commons_licensed_works)，维基百科、开放课程、可汗学院、免费音乐档案、来自Flickr的307百万图像、来自MusicBrainz的39百万图像、来自YouTube的1000万视频等。

### 6.2.3 公平使用（第107条）

自1840年代以来，公平使用一直是普通法。决定是否适用公平使用的四个因素是：
1. 使用的目的和性质（教育用途优于商业用途，转型用途优于复制）；
2. 版权作品的性质（虚构作品优于事实作品，创新性的程度）；
3. 使用的原作部分的数量和实质性；和
4. 使用对原作市场（或潜在市场）的影响。

## 6.3 案例研究
回顾一些已经裁定公平使用或反对公平使用的案件。

### 6.3.1 [作家协会诉Google](https://en.wikipedia.org/wiki/Authors_Guild,_Inc._v._Google,_Inc.)

### 6.3.2 [Google诉Oracle](https://en.wikipedia.org/wiki/Google_LLC_v._Oracle_America,_Inc.)

### 6.3.3 [Fox News诉TVEyes](https://www.lexisnexis.com/community/casebrief/p/casebrief-fox-news-network-llc-v-tveyes-inc)

### 6.3.4 [Kelly诉Arriba](https://en.wikipedia.org/wiki/Kelly_v._Arriba_Soft_Corp.)

### 6.3.5 [Sega诉Accolade](https://en.wikipedia.org/wiki/Sega_v._Accolade)

## 6.4 公平学习与机器学习
公平学习主张机器学习属于公平使用。机器学习系统的数据使用是变革性的，它不会改变作品，但会改变目的。机器学习系统对想法感兴趣，而不是具体的表达。

对于将机器学习视为公平使用的论据：训练数据的广泛访问会为社会创造更好的系统。如果不允许使用，那么大部分作品无法用来产生新的价值。使用版权数据可能更公平。

反对将机器学习视为公平使用的论据：认为机器学习系统不会产生创意的“最终产品”，而只是赚钱。生成模型（例如，语言模型）可以与创意专业人士竞争。机器学习系统的问题（传播假信息，实现监控等），因此不应该给予机器学习系统利益的怀疑。

在版权法下，很难分离可保护的（例如，表达）和不可保护的（例如，想法）。虽然构建机器学习系统可能有很多原因不妥，但版权是阻止它的正确工具吗？对于训练大型语言模型是否属于公平使用的问题正在迅速发展。

## 6.5 阶段性结论

查看信息技术的历史，我们可以看到三个阶段：
1. 第一阶段：文本数据挖掘（搜索引擎），基于简单的模式匹配。
2. 第二阶段：分类（例如，分类停止标志或情感分析），推荐系统。
3. 第三阶段：学习模仿表达的生成模型。

上次，我们看到从GPT-2中提取训练数据可能会出现隐私问题。如果语言模型直接复制哈利·波特，那么这对公平使用来说是有问题的。然而，即使语言模型不直接生成以前的作品，版权仍然相关，因为以前的受版权保护的作品被用来训练语言模型。

事实上，语言模型可以与作家竞争。例如，作家写了3本书，语言模型在这3本书上进行训练，并自动生成第4本。

因此，面对大型语言模型，版权和机器学习的未来还未知。

## 6.6 隐私法律教程

在本教程中，我们将简要讨论一些隐私法律的例子，包括Clearview AI、加利福尼亚消费者隐私法案（2018）、加利福尼亚隐私权法案（2020）以及欧盟的一般数据保护条例（GDPR）。

### 6.6.1 [Clearview AI](https://en.wikipedia.org/wiki/Clearview_AI)

### 6.6.2 [伊利诺伊州生物识别信息隐私法（2008）](https://en.wikipedia.org/wiki/California_Privacy_Rights_Act)

### 6.6.3 [加利福尼亚消费者隐私法案（2018）](https://en.wikipedia.org/wiki/California_Consumer_Privacy_Act)

### 6.6.4 [加利福尼亚隐私权法案（2020）](https://en.wikipedia.org/wiki/California_Privacy_Rights_Act)

#### 6.6.4.1 意图：

- 了解谁在收集他们及其孩子的个人信息，如何使用，以及向谁公开。
- 控制他们个人信息的使用，包括

限制他们敏感个人信息的使用。
- 访问他们的个人信息并有能力纠正、删除和转移他们的个人信息。
- 通过易于获取的自助工具行使他们的隐私权利。
- 行使他们的隐私权利而不受罚款。
- 将未采取合理信息安全预防措施的企业追究责任。
- 从企业使用他们的个人信息中受益。
- 作为员工和独立承包商也能保护他们的隐私利益。


## 6.7 [GDPR（欧盟一般数据保护条例）](https://en.wikipedia.org/wiki/General_Data_Protection_Regulation)

## 6.8 [其他法律](https://www.natlawreview.com/article/california-s-bot-disclosure-law-sb-1001-now-effect)

### 6.8.1 加利福尼亚的机器人披露法案：

如果使用机器人与人进行通信，而不披露它是一个机器人，这是违法的。限制：只适用于激励销售或影响选举投票的情况。限制：只适用于每月在美国有1000万访问者的公开网站。

## 6.9 总结

在我们训练大型语言模型时，我们必须面对版权和公平使用的问题。由于网络爬取的未筛选性质，你必须诉诸公平使用（从每个人那里获得许可证将非常困难）。模型的生成性可能会对争论公平使用提出挑战（可以与人类竞争）。在什么水平上进行调控（语言模型还是下游应用）是有意义的？这个领域正在迅速发展，需要深入的法律和人工智能专业知识才能做出明智的决定！

