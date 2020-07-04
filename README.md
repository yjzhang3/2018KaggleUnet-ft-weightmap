# 2018KaggleUnet_ft.weightmap

Cell image segmentation weight map construction for UNet. 

Combining ideas from https://www.youtube.com/watch?v=cUHPL_dk17E&list=PLZsOBAyNTZwYuFfht61R0b-N1TNIX5_Vy&index=7 and 
https://jaidevd.github.io/posts/weighted-loss-functions-for-instance-segmentation/

Successfully make the weightmap for the 2018 Kaggle training set, which will become useful for punishing the boundary during cell segmentation.

Training data can be found here: https://www.kaggle.com/c/data-science-bowl-2018. Make sure to put them in the same directory as the python file. 

Future considerations:
apply the weightmap to the cross entropy loss function 
