## Takeaways
1) It is hard to incorporate more specific data preprocessing steps (i.e. discretization, impute specific values...) all in a single pipeline line without writing custom transformers based on dataframe operations
2) Developed a methodology to deal with lots of features
3) Can use MSLE for regression when looking for relative error metrics and to punish underestimation more
4) Randomozed search cv: use reciporal[min, max] for positive float, uniform[mean, width] for floats bounded by 0 and 1, randint[min, max] for integers
5) 
