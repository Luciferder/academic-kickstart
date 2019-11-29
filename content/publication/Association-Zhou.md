---
title: Association Study of Alzheimer's Disease with Tree-guided Sparse Canonical Correlation Analysis
date: 2018-05-08 14:04:58
#tags: Association Study
#top: 101
---





#### Shangchen Zhou, **<u>Shuai Yuan</u>**,  Zhizhou Zhang, Zenglin Xu 

{{< figure library="true" src="tree-based_CCA.png" title="" lightbox="true" >}}

<abstract>We consider the problem of finding the sparse associations between two sources of data, for example the sparse association between genetic variations (e.g., single nucleotide polymorphisms, SNPs) and phenotypical features (e.g., magnetic resonance imaging, MRI) in the study of Alzheimer’s disease (AD). Despite the success of Canonical Correlation Analysis (CCA) based its sparse variants in a number of applications, they usually neglect the underlying natural tree structures SNPs and MRI data. Specifically, the whole candidate set, genes, SNPs of gene form a path of tree structure in SNPs data, and the whole image, regions of image, features of region form a path of tree structure in the MRI data. In order to model the tree structure of features in both sources of data, in this paper, we propose a Tree-guided Sparse Canonical Correlation Analysis (TSCCA). The proposed model equips CCA with special mixed-norm regularization terms in order to model the underlying multilevel tree structures among both the inputs and outputs. To solve the resulted complicated optimization problem, we introduce an efficient iterative algorithm for TSCCA by rewriting tree-structured regularization into the common form of overlapping group lasso. To evaluate the proposed model, we have designed the simulation study and real world study respectively on Alzheimer’s disease. Experimental results on the simulation study have shown that the proposed method outperforms CCA with Lasso and group Lasso. The real world study on Alzheimer’s disease has shown that our model can find biologically meaningful associations between SNPs and MRI features.  </abstract>

<div><inf>Accepted by **ICONIP'18**. </inf></div>