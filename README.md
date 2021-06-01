# 2018KaggleUnet ft.weightmap

Cell image segmentation weight map construction for UNet. This is part of my undergraduate research project in Sgro Lab at Boston University. Thanks to Dr. Sgro and Chuqiao for generous help and mentorship!

Combining ideas from https://www.youtube.com/watch?v=cUHPL_dk17E&list=PLZsOBAyNTZwYuFfht61R0b-N1TNIX5_Vy&index=7 and 
https://jaidevd.github.io/posts/weighted-loss-functions-for-instance-segmentation/

Successfully made the weightmap for the 2018 Kaggle training set, which will become useful for punishing the boundary during cell segmentation.

Training data can be found here: https://www.kaggle.com/c/data-science-bowl-2018. Make sure to put them in the same directory as the python file. 

Future considerations:
apply the weightmap to the cross entropy loss function 
