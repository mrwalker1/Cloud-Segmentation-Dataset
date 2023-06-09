# CloudSegmentaion
## How to download 
```
git clone https://github.com/mrwalker1/Cloud-Segmentation-Dataset.git
```

## To Run
Run main.py

A menu in the console will appear given you the option to train the ADAU, evaluate models or train the training models. 
```
1 Train ADAU, 2 Evaluate models, 3 Train testing models:
```
## Resetting models
To reset a model, go into the main directory and delete the checkpoint file for the model you want to reset. 
```
[model name].ckpt.data-00000-of-00001
[model name].ckpt.index
```
## Example output 
![alt text](https://github.com/mrwalker1/Cloud-Segmentation-Dataset/blob/main/Picture21.png)

(A) original image, (B) ADAU, (C) DeepLabV3+, (D) AMEL Attention U-Net, (E) U-Net, (F) AMEL U-Net, (G) Attention U-Net, (H) CloudU-Net, (I) Ground Truth
## Dataset 
```
.
├── training
│   ├── img
        ├── 10010.png
│       └── ...
│   └── mask
│       ├── 10010.png
│       └── ...
└── test
   ├── img
        ├── 10010.png
        └── ...
   └── mask
       ├── 10010.png
       └── ...
```
## Requirements
Minium system requirments are:

Processor: i7 or Ryzen 2700x

RAM: 16GB

GPU: Nvidia 1060 6GB


## Liberies required:

Tensorflow/ Tensorflow GPU

Python 3.8.9

Numpy 

Sklearn 

Matplotlib

glob

os

keras

PIL

gc

## References
Aleena_Suhail, 2021. Model is not learning. [Online] 
Available at: https://discuss.tensorflow.org/t/model-is-not-learning/5585
[Accessed 24 03 2023].

Bhattiprolu, D. S., 2021. python_for_microscopists. [Online] 
Available at: https://github.com/bnsreenu/python_for_microscopists/blob/072ef815f325f56a59a0e88369c6b2d6e7ef25cc/224_225_226_models.py
[Accessed 28 Nov 2022].

Mohajerani, S., 2019. Cloud-Net-A-semantic-segmentation-CNN-for-cloud-detection. [Online] 
Available at: https://github.com/SorourMo/Cloud-Net-A-semantic-segmentation-CNN-for-cloud-detection/blob/master/Cloud-Net/main_train.py
[Accessed 11 March 2023].

Sarkar, A., 2021. Retinal-Vessel-Segmentation-using-variants-of-UNET/model.py. [Online] 
Available at: https://github.com/arkanivasarkar/Retinal-Vessel-Segmentation-using-variants-of-UNET/blob/main/model.py
[Accessed 16 Nov 2022].

Tomar, N., 2021. Human-Image-Segmentation-with-DeepLabV3Plus-in-TensorFlow. [Online] 
Available at: https://github.com/nikhilroxtomar/Human-Image-Segmentation-with-DeepLabV3Plus-in-TensorFlow/blob/main/model.py
[Accessed 20 Jan 2023].

Tomar, N., 2021. Human-Image-Segmentation-with-DeepLabV3Plus-in-TensorFlow. [Online] 
Available at: https://github.com/nikhilroxtomar/Human-Image-Segmentation-with-DeepLabV3Plus-in-TensorFlow/blob/main/metrics.py
[Accessed 25 Jan 2022].


