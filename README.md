# lightgbm_predict4j
java implementation of LightGBM predicting part

This project is a java translation of [LightGBM](https://github.com/Microsoft/LightGBM) predicting part at version 57d552726f19ba9b29843cbaa50f23a3ba4e79e6 in master. 

LightGBM is an excellent tool for training model in offline way. However, when a model is saved by LightGBM, it is difficult to be used efficiently for online predicting in production environment. 

I translate the predicting part of LightGBM into java so that the model can be used for online predicting in java applications. After training a model with LightGBM, you can use the model to do predicting job for every realtime query data, just like the unit test code shows.