# 2018KaggleUnet_ft.weightmap

Combining ideas from https://www.youtube.com/watch?v=cUHPL_dk17E&list=PLZsOBAyNTZwYuFfht61R0b-N1TNIX5_Vy&index=7 and 
https://jaidevd.github.io/posts/weighted-loss-functions-for-instance-segmentation/

Successfully make the weightmap for the 2018 Kaggle training set, which will become useful for punishing the boundary during cell segmentation.

Future considerations:
apply the weightmap to the cross entropy loss function 
