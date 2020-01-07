# Feature Selection

## Feature Selection with Null Importances

Original link : https://www.kaggle.com/ogrellier/feature-selection-with-null-importances

基本思想：有的时候模型其实很蠢，很多根本就和目标没有关联的东西，它也可以瞎扯一通和目标关联上，这种虚假的关联到测试集上当然就扑街了，
这就是我们常说的过拟合。那么回到我们一开始的问题，如何在feature importance中画出一条线，来区分这个特征是否有用呢？
思想很简单，就是将特征分数与随机假特征的分数（即Null Importance）进行对比，假如特征的分数并不能明显超过null importance，那么证明这个特征是一个无用的特征。
（https://jonuknownothingsnow.github.io/2018/10/21/%E8%B0%90%E9%97%A8%E6%AD%A6%E5%AD%A6%EF%BC%9A%E7%89%B9%E5%BE%81%E9%80%89%E6%8B%A9%E4%B8%8ENull%20Importance/）

## ASHRAE: Automatic FE: Featuretools & Selection FE with SelectFromModel

https://www.kaggle.com/vbmokin/ashrae-automatic-fe-featuretools-selection-fe

## Titanic - Featuretools (automatic FE&FS)

https://www.kaggle.com/vbmokin/titanic-featuretools-automatic-fe-fs
