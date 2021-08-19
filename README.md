# kaggle_house-prices-advanced-regression-techniques

https://www.kaggle.com/c/house-prices-advanced-regression-techniques/


*** References ***

* https://www.kaggle.com/jesucristo/1-house-prices-solution-top-1?scriptVersionId=20214677

	* It is apparent that SalePrice doesn't follow normal distribution, so before performing regression it has to be transformed. While log transformation does pretty good job, best fit is unbounded Johnson distribution.
	* Also none of quantitative variables has normal distribution so these should be transformed as well.
	* Qualitative variable encoding --> https://www.kaggle.com/jesucristo/1-house-prices-solution-top-1?scriptVersionId=20214677&cellId=21 
	* Spearman correlation takes into account the rankings of values, rather than the real values as in linear correlation. Hence, it is in accordance with the encoding scheme proposed.
