## Optimizing Parameters of SVM

## Steps:
1. Download the dataset
2. Pre-process the dataset
3. Create ten samples 
4. Split the samples in  70 : 30 for training and testing
5. Optimise SVM using random sampling.
6. Plot the convergence graph for the accuracies.

- Due to significant class imbalance, SMOTE(Synthetic Minority Oversampling Technique) has been used to solve the problem.


### Performance of SVM with different samples
|Sample|	Accuracy |	Kernel |	C 	 |     Gamma |
|------|-----------|--------|---------|-----------|
|S1	|0.76   |sigmoid |0.90 |0.122|
S2	|0.78	|rbf	|0.125	|0.247|
S3	|0.79	|rbf	|0.747	|0.033|
S4	|0.79	|rbf	|0.671	|0.627|
S5	|0.79	|rbf	|0.671	|0.627|
S6	|0.79	|rbf	|0.671	|0.627|
S7	|0.81	|sigmoid |0.607	|0.059|
S8	|0.81	|sigmoid |0.607	|0.059|
S9	|0.81	|sigmoid |0.607	|0.059|
S10	|0.81	|sigmoid |0.607	|0.059|


