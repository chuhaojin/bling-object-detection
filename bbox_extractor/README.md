# Bottom Up Attention For Application

This object detection tool implements from [bottom-up-attention](https://github.com/peteanderson80/bottom-up-attention) project and [bottom-up-attention.pytorch](https://github.com/MILVLG/bottom-up-attention.pytorch) project. This tool has been used in the application *AI's Imaginary World* for  **BriVL**'s data preprocessing.



## Requirements

- [Python](https://www.python.org/downloads/) >= 3.6
- [PyTorch](http://pytorch.org/) >= 1.4
- [Cuda](https://developer.nvidia.com/cuda-toolkit) >= 9.2 and [cuDNN](https://developer.nvidia.com/cudnn)
- [Detectron2](https://github.com/facebookresearch/detectron2/releases/tag/v0.3) <= 0.3


**Important: The version of Detectron2 should be 0.3 or below.**

*Anaconda is recommended.*

## Download Model
Put the pre-trained model in ./weights. You can download the pre-trained object detection model from [here](https://drive.google.com/file/d/1oquCwDEvuJPeU7pyPg-Yudj5-8ZxtG0W/view?usp=sharing).
## Test BUA tool

Test image has been saved in ./test_data, Test BUA tool with following command:

```
python3 bbox_extractor.py --img_path test_data/test.png --out_path test_data/test.npz
```


## QR Code of AI's Imaginary World
*AI's Imaginary World* is developed based on the **BriVL** model, You can use the QR code below to experience [AI's Imaginary World](http://buling.wudaoai.cn/).

![bling](./img/bling_300x300.jpeg)

## More Resources

[Source Code of BriVL 1.0](https://github.com/BAAI-WuDao/BriVL)

[Model of BriVL 1.0\*](https://wudaoai.cn/model/detail/BriVL) 

[Online API of BriVL 1.0](https://github.com/chuhaojin/WenLan-api-document)

[Online API of BriVL 2.0](https://wudaoai.cn/model/detail/BriVL)

\* indicates an application is needed.


## Contact
This repo is maintained by Chuhao JIn([@jinchuhao](https://github.com/chuhaojin)).
