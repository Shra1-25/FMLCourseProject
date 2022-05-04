# Making Every Model Robust.

## Foundations of Machine Learning Course Project (NYU Spring 2022).

selfSup_AA.ipynb contains the final notebook implementation of quantized WideResNet32 with natural supervision. 

CIFAR folder contains the code to train/test quantized WideResNet32 Network.

Please find all the models [here](https://drive.google.com/drive/folders/1lR3muFSTTbSLKquhG9uEcHJJY8zHr9r_?usp=sharing). 

i) model_wide_cifar_10.pth is the model containing quantized WideResNet32 implementation from Fu et al. (2021). 

ii) ckpt folder contains the base models trained using PGD-7 adversarial training method.  

iii) ssl_model_130.pth is the SSL model from Mao et al. (2021). 


##### Make sure the paths to all the files in the args is correct. TestAdaAccuracy is the robust accuracy which can be seen in the notebook to be 61.17%. You may ignore other variables which are printed as 0 in the output of second last cell (since they weren't reinitialized after reading from the stored perturbed images and are not used in the code except for presenting clean accuracies/robust accuracy which can be seen in the other previous cells where the perturbed images are stored.). 
