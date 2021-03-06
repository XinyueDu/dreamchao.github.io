---
layout: post
title: 机器学习算法总结
categories: Machine-learning
description: 机器学习算法简介
keywords: machine learning 
comments: false
---  

### 1. 监督学习
- #### 定义
 &nbsp; &nbsp; 机器将已标注有标签的数据作为老师，学习并训练得出模型，然后输出预测数据的结果。
- #### 解决问题
    ①回归问题  
	②分类问题
- #### 算法模型
	① 线性回归模型  
	② K-近邻算法  
	③ 决策树  
	④ 朴素贝叶斯  
	⑤ 逻辑回归  

---

### 2. 半监督学习
- #### 定义  
   &nbsp; &nbsp; 通识使用未标注和标注的数据训练模型来进行模式识别工作
- #### 解决问题
    ① 垃圾信息过滤    
	② 视频网站分析
- #### 算法模型
	① 半监督SVM（支持向量机）   
	② 高斯模型   
	③ KNN模型   
	④ Self-trainning   
	⑤ Co-trainning    
- #### 优点
	① 相比监督学习，节约人力成本，提高投入产出比    
	② 相比无监督学习，可以得到分配更高精度的模型   

---
### 3. 无监督学习
- #### 定义   
    &nbsp; &nbsp; 不给机器提供已标注的数据，让机器自己对数据进行处理并输出结果。
- ####  解决问题
	① 关联  
	② 聚类   
	③ 降维   
- #### 算法模型
	① K均值算法   
	② 自编码   
	③ 主成分分析   
	④ 随机森林   

---

### 4. 强化学习
- ####  定义  
    &nbsp; &nbsp; 机器感知环境的正状态转移时会反馈给机器的一个奖赏，使机器学习朝着正信号趋势学习，从而使累积奖赏值最大。
- ####  解决问题
	① 自动直升机   
	② 机器人控制   
	③ 手机网络路由   
	④ 市场决策   
	⑤ 工业控制   
	⑥ 高效网页索引   
- ####  算法模型  
	① K-摇臂赌博机（单步强化学习任务）   
	   ● ε-贪心算法   
	   ● Softmax算法
	② 有模型学习（多步强化学习任务）  
	     ● 基于T步累积奖赏的策略评估算法  
	     ● 基于T步累积奖赏的策略迭代算法   
	③ 免模型学习   
	     ● 蒙特卡罗强化学习  
	         a) 同策略  
	         b) 异策略   
	     ● 时序查分学习   
	         a) Q-学习算法   
	         b) Sarsa算法   
	  ④ 模仿学习   

---

### 5. 迁移学习
- #### 定义  
   &nbsp; &nbsp;  指从一个领域的学习结果迁移到另一个学习领域   

- #### 解决问题  
   ① 终身学习    
   ② 知识转移   
   ③ 归纳迁移   
   ④ 多任务学习   
   ⑤ 知识的巩固   
   ⑥ 上下文相关学习   
   ⑦ 元学习   
   ⑧ 增量学习   
- ####  算法模型  
    TrAdBoost算法

---

### 6. 深度学习
- ####  定义   
&nbsp; &nbsp; 多层神经网络   
- ####  解决问题   
	① 预测学习   
	② 语音识别   
	③ 图像识别   
- ####  算法模型 
   RNN（Recurrent Neural Network）一类用于处理序列数据的神经网络   
   DNN（Deep Neural Networks）深度神经网络     
   CNN (Convolutional Neural Network) 卷积神经网络，是一种深度前馈人工神经网络。
- #### 优点   
	① 从特征中检测复杂的相互作用   
	② 从几乎没有处理的原始数据中学习低层次的特征    
	③ 处理高基数类成员   
	④ 处理未标记的数据    

---


## 版权与免责声明   
   本文来自[如何自学人工智能](https://www.zhihu.com/question/21277368)放飞人夜的回答 ，经本人修改后发布，如有侵权，请联系我删除
