## Takeaways
1) It is hard to incorporate more specific data preprocessing steps (i.e. discretization, impute specific values...) all in a single pipeline line without writing custom transformers based on dataframe operations
2) Developed a methodology to deal with lots of features:
> - create new features
> - specify the features to delete
> - specify the numeric features that should belong to categorical features
> - prepare for numeric and categorical columns names and store them into csv files
3) Can use MSLE for regression when looking for relative error metrics and to punish underestimation more
4) Randomozed search cv: use reciporal[min, max] for positive float, uniform[mean, width] for floats bounded by 0 and 1, randint[min, max] for integers
5) Make sure ensembles are diverse (check model correlations, should choose uncorrelated models for ensemble)

## Future Plans
1) Debug custom transformers 
2) Practise classification more
3) include anamoly / outlier detection 
4) Do more insight based project (focus on interpretation and actionable managerial insights)
5) Try XGBoost and mlxtend
6) Practise more with Stacking
7) Include discretixation
8) Focus more on assumptions checking (normal qq plot, linearity plot...)
9) Use GitPython to commit and push
10) Use Datatable instead of pandas
11) Do feature selection manually instead of selectKbest (easier to include all preprocessing steps in one pipe)
