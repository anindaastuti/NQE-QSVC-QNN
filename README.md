Quantum machine learning (QML) combines quantum computing with machine learning, offering potential for solving intricate problems. Our research delves into QML's application in identifying gene expression biomarkers for clear cell renal cell carcinoma (ccRCC) metastasis. ccRCC, the primary renal cancer subtype, poses significant challenges due to its high lethality and complex metastasis process. Despite extensive research, understanding the mechanisms of cancer cell dissemination and establishment in distant sites remains elusive. Identifying metastasis biomarkers is a daunting task in machine learning.  Our study addresses the need for improved execution time and accuracy in QSVC and QNN algorithms compared to SVC and NN for binary classification. Drawing inspiration from the Neural Quantum Embedding (NQE) method, we propose a two-stage approach for the binary classification problem. We aim to assess if integrating NQE with QSVC/QNN enhances performance compared to NQE with SVC/NN across diverse biomedical datasets, demonstrating the effectiveness and generalizability of the approach. 
The workflow diagram for the gene expression biomarker study is depicted in Figure 1. 
![image](https://github.com/user-attachments/assets/27757c81-576a-4f98-bffb-1f616059b17f)
Figure.1.  The workflow diagram for the gene expression biomarker study which involve using principal component analysis (PCA) to reduce the number of features (principal components), thus requiring fewer qubits. We utilize the SMOTE package for data balancing and optimize SVC and QSVC models through the NQE approach. This hybrid method combines quantum data encoding with neural network training to separate the classes of data into orthogonal subspaces,  followed by performance comparison.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/062abf56-6fea-4b69-9266-1b7a4b2163fe" />
Figure 2 Data embedding by using Neural Quantum Embedding (NQE)

Figure 3 illustrates the workflow of integrating NQE with QSVC and QNN classification.

<img width="273" alt="image" src="https://github.com/user-attachments/assets/39a6d811-0ffd-4a61-a12c-2e58fda85ca8" />
Figure 3. The workflow of integrating NQE with QSVC and QNN classifiers.

Supplementary file 1 – The results of the 48 differentially expressed genes obtained by analysing gene expression profiles using the DEseq2 package. 

Supplementary file 2 – The results of the 4 differentially expressed miRNAs obtained by analysing miRNAs expression profiles using the R ‘limma’ package.

Supplementary file 3 – The results of the 10 performance metrics of the miRNA biomarker study (NT vs M0) for the four case studies are as follows: SVC, QSVC, NQE+SVC, and NQE+QSVC.




