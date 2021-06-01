# iNSP-GCAAP: Identifying Non-classical Secreted Proteins using Global Composition of Amino Acid Properties

#### H. T. Pham, T-H Nguyen-Vo, Q. H. Trinh, T. T. T. Do*, and [B. P. Nguyen](https://homepages.ecs.vuw.ac.nz/~nguyenb5/about.html)∗


![alt text](https://github.com/mldlproject/2020-iNSP-CTDC/blob/main/iNSP-CDTC-abs.svg)

## Motivation
Non-classical secreted proteins refer to a group of proteins released into the extracellular environment 
under the facilitation of different biological transporting pathways apart from the Sec/Tat system. As experimental 
determination of non-classical secreted proteins is often costly and requires
skilled handling techniques, computational approaches are necessary. In this study, we introduce iNSP-GCAAP, 
a computational prediction framework, to identify non-classical secreted proteins. We propose using global composition
of a customized set of amino acid properties to encode sequence data and use the random forest algorithm for 
classification. We used the training dataset introduced by Zhang et al. (Bioinformatics, 36(3), 704–712, 2020) to develop
our model and test it with the independent test set in the same study. 

## Results
The area under the receiver operating characteristic curve (AUC) on that test set was 0.9256 
which outperformed other state-of-the-art methods using the same
datasets. Our framework is also deployed as a user-friendly
web-based application to support the research community
to predict non-classical secreted proteins.

## Availability and Implementation
Source code and data are available upon request.

## Web-based Application
[Click here](https://insp.vnpay.mana.vn/)

## Contact 
[Go to contact information](https://homepages.ecs.vuw.ac.nz/~nguyenb5/contact.html)
