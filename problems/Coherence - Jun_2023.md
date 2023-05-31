# Familiar projects
- [DeepDive Project](http://deepdive.stanford.edu/showcase/apps)  
> (NELL) Never-Ending Language Learning [[Slides](https://www.cs.cmu.edu/~ninamf/courses/601sp15/slides/23_nell_4-13-2015.pdf)][[Paper](https://www.cs.cmu.edu/~tom/pubs/NELL_aaai15.pdf)]  
- AutoKnow: Self-Driving Knowledge Collection for Products of Thousands of Types (KDD 2020, Applied Data Science Track). [Paper](https://arxiv.org/pdf/2006.13473.pdf)    
- ？Towards the Completion of a Domain-Specific Knowledge Base with Emerging Query Terms https://ieeexplore.ieee.org/abstract/document/8731487
    
|   |   |   
|---|---|   
| **Rotational knowledge across a variety of technology areas**[technical notes]  |  [Towards Knowledge-Based Personalized Product Description Generation in E-commerce](https://arxiv.org/pdf/1903.12457.pdf)
                                                              Personalized Description Generation
                                                              电商平台生成竞争力的产品描述最终诉诸自动化工具
                                                              现存方法主要来自模板和统计工具
                                                              本文通过neural net转动知识融合和及时建立适应知识库生成个性化产品描述
                                                              --------------------------------
                                                              摘要理解
                                                              文章功能理解
                                                              [https://arxiv.org/pdf/1903.12457.pdf
                                                              , applied science track] (KDD 2019) 
                                                              ----------------------------     |  
|   |   |  
|---|---|  
| AliCoCo: Alibaba E-commerce Cognitive Concept Net. [GitHub](https://github.com/alicogintel/AliCoCo)  | 电商平台基础建设 1. 昨天提及永动机paper以增长情况时的Variational Graph { }□ 为它建系, *软件革命工业化*从一个简单的地理知识系统说起  2. Taxonomy-extraction构建是系统另一个重要组成部分。有个性化推荐🍥算法下, 平台轴承庞大社会需求。  |  
| Product Match~   | 底层劳动力下的relation classification~  |

### - Findings on Knowledge Base Embeddings
> - Knowledge disambiguation (Ref. [(NCEL) Neural Collective Entity Linking](https://arxiv.org/pdf/1811.08603.pdf))
> - SHINE+: A General Framework for Domain-Specific Entity Linking with Heterogeneous Information Networks (TKDE 2018)
> - [Dynamo: Amazon’s highly available key-value store](https://www.amazon.science/publications/dynamo-amazons-highly-available-key-value-store) (Serverless)

## Relation Manager 🌟
1. CoType: Joint Extraction of Typed Entities and Relations with Knowledge Bases (CoType, WWW2017)  
    
| Relation Type  | Forms  |  
|---|---|  
|   Overlapping Relations   | CEO-of(Rob Iger, Disney) CEO-of(Steve Jobs, Apple)    |
                              Acquired(Google, Youtube)
                              Acquired(Msft, Skype)
                              Acquired(Citigroup, EMI)  
  
关系抽取方式：① distant supervision远程关系监督 ② smart（seed）③ [弱監督](https://zhuanlan.zhihu.com/p/81404885)  
2. Neural Relation Extraction with Selective Attention over Instances (ACL 2016)  
3. Multi-instance Multi-label Learning for Relation Extraction  
4. NERO: A Neural Rule Grounding Framework for Label-Efficient Relation Extraction  

# Assignments
[rules for KB](https://github.com/WillaFan/Systems/blob/main/rule.json)  
A sample solution for e-commerce (based on paper reading)[🌟]  
![alt 属性文本](https://github.com/WillaFan/Systems/blob/main/pics/WeChat%20Image_20230601035732.jpg)  
A real solution for C++ software code collections [day1, day2, day3, day4, rules]  
> day1: [1](https://www.cnblogs.com/Simulation-Campus/p/8809999.html)initiate, [2](https://blog.csdn.net/weixin_44690935/article/details/106062025)  
> day2: [1](https://philippegroarke.com/games/), [2](https://blog.csdn.net/zq9955/article/details/111150222), [3](https://iq.opengenus.org/login-and-registration-system-in-cpp/), [4](https://learn.microsoft.com/zh-cn/cpp/cpp/classes-and-structs-cpp?view=msvc-170)prototype  
> day3: [1](https://blog.csdn.net/weixin_43716907/article/details/121743370), [2](https://blog.csdn.net/qq_21743659/article/details/114312564)  
> day4: [1](https://blog.csdn.net/wasaiheihei/article/details/114319613), [2](https://blog.csdn.net/weixin_43350361/article/details/106455331), [Apache Ant](https://ant.apache.org/faq.html#passing-cli-args), [3](https://blog.csdn.net/zhizhengguan/article/details/119824294), [4](https://blog.csdn.net/chenlycly/article/details/125529931?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522168553805816800184118421%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=168553805816800184118421&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~rank_v31_ecpm-2-125529931-null-null.142^v88^control_2,239^v2^insert_chatgpt&utm_term=C%2B%2B%20%E8%BB%9F%E4%BB%B6%E9%96%8B%E7%99%BC%E8%BB%9F%E4%BB%B6%E5%88%86%E6%9E%90&spm=1018.2226.3001.4187), [5](https://blog.csdn.net/chenlycly/article/details/128703097)  
- [CMakefile](https://www.gnu.org/software/make/), [干货：构建C/C++良好的工程结构](https://zhuanlan.zhihu.com/p/59450618?utm_source=wechat_timeline&utm_medium=social&utm_oi=569174121569763328&utm_campaign=shareopn&utm_id=0)  
- > 不合理的UI界面卡顿问题，解决办法是新开启一个UI线程，定时检测缓存队列大小，在缓存达到上限之前就将新队列日志写入文件  
  > 在软件开发过程中会使用多项策略，如锁死字体大小是一项，却未能逃过分辨率一关。另一种排查方式拆分解决需求为多条商业需求business requirements，是正在执行的task。 
