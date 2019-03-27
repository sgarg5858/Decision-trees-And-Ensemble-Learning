# Decision-trees-And-Ensemble-Learning


Decision Trees are white Box models and are easy to interpret and also gives comparable results to other classification algorithms when ensembling methods are used.

Feature Selection can be performed using Random Forest Classifier based upon the distance of feature from the root in forest of trees.

colormap = plt.cm.RdBu
plt.figure(figsize=(8,8))
plt.title('Pearson Correlation of Features', y=1.05, size=15)
sns.heatmap(risk_df1.astype(float).corr(),linewidths=0.1,vmax=1.0, 
            square=True, cmap=colormap, linecolor='white', annot=True)


