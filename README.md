# seaborn
Main EDA steps:
1) First find the missing values and fill them. 2) Find outliers and choose to either replace them or ignore them(continouous variable).Check for quantiles to check the distribution of the data.Use box plot and histogram plot.

Univariate analysis

1) bargraph(countplot)/kdeplot for categorical or continuous variables(value counts for catvar and describe for contvar)

Bivariate analysis

1) Pairplot for all the categorical variable(use hue="catvar" to see plot) 2) use heatmap for corr(){correlation between contvar) 3) use sns.countplot for catvar(1 or var can be seen) 4) use catplot to see 1,2,3 catvar in one plot. 5) Split the data with respect to the target(if categorical) and then check all the barplots(count),boxplot for both the datasets
