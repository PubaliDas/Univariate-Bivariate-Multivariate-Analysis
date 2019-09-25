# Univariate-Bivariate-Multivariate-Analysis
This repository contains a lot of different types of interesting plots used for EDA.


![databythenumbersimages](https://user-images.githubusercontent.com/54616526/65588580-68103000-dfa5-11e9-9612-749925fcf837.jpg)


A very popular datset called 50 Startups is used to perform the exploratory data analysis.
The target variable is assumed to be PROFIT. Various types of plots are build to explore the insights of the data.
Mainly the following is performed for any type of EDA.


### Univariate analysis
sns.distplot(df.Profit) # numeric


sns.boxplot(df.Profit) # numeric


sns.distplot(df.Profit)


sns.countplot(df.State) # categorical


sns.countplot(df.Number)

### Bivariate analysis
sns.jointplot('Profit', 'RND', data = df, kind='scatter')


sns.lmplot(df.Profit, df.RND, data=df, hue='Number', fit_reg=False)


sns.countplot(State, hue = 'Number', data=df)

### Multivariate analysis

sns.pairplot(df.select_dtypes(include=[np.int, np.float]])







*Want to run codes on you own!*
*Click here ->* [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PubaliDas/Univariate-Bivariate-Multivariate-Analysis/master) 
