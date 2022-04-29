# CKNs versus ConvNets
Convolutional Kernel Networks (CKNs), first introduced by Mairal et al. (2014) and further developed by Mairal (2016) and Paulin et al. (2017), 
allow one to learn feature representations for images or signals in an unsupervised or in a supervised manner. 
In our [paper](https://arxiv.org/pdf/1903.08131.pdf), we describe a systematic way to transform a Convolutional Neural Network (ConvNet) into a CKN. 
Moreover, we develop an end-to-end training algorithm for CKNs and demonstrate that CKNs can often achieve comparable performance 
to their ConvNet counterparts. 

The code presented in https://github.com/cjones6/yesweckn implements CKNs for images and other 
data observed on a grid and trains them using a stochastic gradient optimization method with an accurate gradient. 

The present repository presents an interactive visualization of the filters computed by a CKN
against those computed by a ConvNet on landmark architectures for different layers 
and at different iterations of the training procedure. 


### Further Reading
The filters have been computed from https://github.com/cjones6/yesweckn which is the code supporting the following paper.
```
@article{JRH2019,
  title={Kernel-based Translations of Convolutional Networks},
  author={Jones, Corinne and Roulet, Vincent and Harchaoui, Zaid},
  journal={arXiv preprint arXiv:1903.08131},
  year={2019}
}
```
We invite the interested user to read the documentation and take a look at the example given in the repository https://github.com/cjones6/yesweckn.
