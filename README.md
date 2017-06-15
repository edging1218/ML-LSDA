# ML-LSDA
This repository contains course projects for Machine Learning-Large Scale Data Analysis (Spring 2017) using PySpark. 
1. a1
..*Analyze the lengths of State of the Union addresses
2. a2
--*Use vector space model from information retrieval to find similar State of the Union addresses
..*$$w_i(d) = n_i(d)log(\frac{|D|}{\sum_{d'\in D}\mathbb{1}(t_i \in d')})$$, where $n_i(d)$ is the number of times term $t_i$ appears in document $d$, $|D| = \sum_{d'\in D}\mathbb{1}$ is the total number of documents. $\sum_{d'\in D}\mathbb{1}(t_i \in d')$ is the number of documents which contain term $t_i$.
