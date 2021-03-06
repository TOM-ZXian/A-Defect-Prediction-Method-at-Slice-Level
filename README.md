# A-Defect-Prediction-Method-at-Slice-Level
A Code Naturalness Based Defect Prediction Method at Slice Level（NASAC 2020）

Abstract:  Software defect prediction is an active research topic in the domain of software quality assurance. It can help developers find potential defects and make better use of resources. How to design more discriminative metrics for the prediction system, taking into account performance and interpretability, has always been a research direction that people devote to. Aiming at this challenge, a code naturalness feature based defect predictor method (CNDePor) is proposed. This method improves the language model by taking advantage of the bidirectional code-sequence measurement and weighting the samples by using the quality information, so as to increase the defect discrimination of the cross-entropy (CE) type metrics obtained from the model. Aiming at the shortcomings of coarse-grained defect prediction (e.g. difficulties in focusing on defect areas and high cost of code reviews), a new fine-grained defect prediction problem, statement-oriented slice level defect prediction, is studied. Four metrics are designed for this problem, and the effectiveness of these metrics and CNDePor are verified on two types of security defect datasets. The experimental results show that: CE-type metrics are learnable, which contain the relevant knowledge learned from the corpus by language model; the improved CE metrics are significantly better than the original metrics and traditional size metrics; the CNDePor method has significant advantages over the traditional defect prediction methods and an existing method based on code naturalness, and own comparable performance and stronger interpretability than a state-of-the-art mothed based on deep learning.

Key words:  software quality assurance; defect prediction; code naturalness; slice granularity; language model; cross-entropy; deep learning

基于代码自然性的切片粒度缺陷预测方法

摘  要:	软件缺陷预测是软件质量保障领域的一个活跃话题,它可以帮助开发人员发现潜在的缺陷并更好地利用资源.如何为预测系统设计更具判别力的度量元,并兼顾性能与可解释性,一直是人们致力于的研究方向.针对这一挑战,提出了一种基于代码自然性特征的缺陷预测方法——CNDePor.该方法通过正逆双向度量代码和利用质量信息对样本加权的方式改进语言模型,提高了模型所得交叉熵(CE)类度量元的缺陷判别力.针对粗粒度缺陷预测存在难以聚焦缺陷区域、代码审查成本高的不足,研究了一种新的细粒度缺陷预测问题——面向语句的切片级缺陷预测.在此问题上,设计了4种度量元,并在两类安全缺陷数据集上验证了度量元和CNDePor方法的有效性.实验结果表明:CE类度量元具有可学习性,它们蕴涵了语言模型从语料库中学习到的相关知识;改进的CE类度量元的判别力明显优于原始度量元和传统规模度量元;CNDePor方法较传统缺陷预测方法和已有的基于代码自然性的方法有显著优势,较先进的基于深度学习的方法具有可比性性能和更强的可解释性.

关键词:	软件质量保障;缺陷预测;代码自然性;切片粒度;语言模型;交叉熵;深度学习

英文引用格式: Zhang X, Ben KR, Zeng J. A code naturalness based defect prediction method at slice level. Ruan Jian Xue Bao/Journal of Software, 2021(in Chinese). http://www.jos.org.cn/1000-9825/0000.htm

