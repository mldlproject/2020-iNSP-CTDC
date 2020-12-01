# iNSP-CTDC: In silico Identification of Non-classical Secreted Proteins

#### H. T. Pham, T-H Nguyen-Vo, Q. H. Trinh, T. T. T. Do*, and [B. P. Nguyen](https://homepages.ecs.vuw.ac.nz/~nguyenb5/about.html)∗


![alt text](https://github.com/mldlproject/2020-iNSP-CTDC/blob/main/iNSP-CDTC-abs.svg)

*Motivation*: 
Non-classical secreted proteins refer to a group of proteins released into the extracellular 
environment under the facilitation of different biological transporting pathways, excepting the Sec/Tat system. Since the 
experimental determination of non-classical secreted proteins requires skilled handling techniques and sufficient budgets, 
many computational approaches have been introduced to promote working efficiency. In this study, we propose iNSP-CTDC, 
a prediction framework, to in silico recognize non-classical secreted proteins from the classical ones. Our proposed method 
was constructed using random forest and specific features, including composition, transition, and distribution (CTD) of 
amino acids and global composition (C) of CTD features. The used feature is termed CTDC indicating distribution patterns 
and physicochemical properties of amino acids built up a protein/peptide sequence.

**Results**: Despite the simplified design, iNSP-CTDC’s performance is significantly better than contemporary state-ofthe-art 
methods which have been developed with more complicated learning algorithms and numerous types of protein-encoded schemes. The 
area under the ROC curve (ROC-AUC) and area under the precision-recall curve (PR-AUC) were used to evaluate the model performance. 
The experimental results show that our proposed method obtains a ROC-AUC value of 0.88 and PR-AUC value of 0.92 on an independent 
test set with 32 samples. Based on the recorded evaluation metrics, iNSP-CTDC is demonstrated to be a stable and robust computational 
framework to address this biological issue.

**Availability and implementation** Source code and data are available on [GitHub](https://github.com/mldlproject/2020-iNSP-CTDC)

**Contact** [Go to contact information](https://homepages.ecs.vuw.ac.nz/~nguyenb5/contact.html)
