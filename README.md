# CoreML-Models
Converted CoreML Model Zoo.

<img width="1280" src="https://user-images.githubusercontent.com/23278992/147420041-fdeb1fbb-7e93-41c6-84d6-80d7c1c45200.jpeg">

CoreML is a machine learning framework by Apple.
If you are iOS developer, you can easly use machine learning models in your Xcode project. 

# How to use

Take a look this model zoo, and if you found the CoreML model you want,
download the model from google drive link and bundle it in your project.
Or if the model have sample project link, try it and see how to use the model in the project.
You are free to do or not.

# Section Link

- [**Image Classifier**](#image-classifier)
  - [Efficientnetb0](#efficientnetb0)
  - [Efficientnetv2](#efficientnetv2)
  - [VisionTransformer](#visiontransformer)
  - [Conformer](#conformer)
  - [DeiT](#deit)
  - [RepVGG](#repvgg)
  
- [**Object Detection**](#object-detection)
  - [YOLOv5s](#yolov5s)
  
- [**Segmentation**](#segmentation)
  - [U2Net](#u2net)
  - [face-parsing](#face-parsing)
  - [Segformer](#segformer)
  - [BiseNetv2](#bisenetv2)
  
- [**Super Resolution**](#super-resolution)
  - [Real ESRGAN](#realesrgan)
  - [BSRGAN](#realesrgan)

- [**Low Light Enhancement**](#low-light-enhancement)
  - [StableLLVE](#stablellve)

- [**Image Restoration**](#image-restroration)
  - [MPRNet](#mprnet)
  - 
- [**Image Generation**](#image-generation)
  - [MobileStyleGAN](#mobilestylegan)
  - [DCGAN](#dcgan)

- [**Image2Image**](#image2image)
  - [Anime2Sketch](#anime2sketch)
  - [AnimeGAN2Face_Paint_512_v2](#animegan2face_paint_512_v2)
  - [Photo2Cartoon](#photo2cartoon)
  - [AnimeGANv2_Hayao](#animeGANv2_hayao)
  - [AnimeGANv2_Paprika](#animeGANv2_paprika)
  - [WarpGAN Caricature](#warpgancaricature)
  - [UGATIT_selfie2anime](#ugatit_selfie2anime)
  
# How to get the model
You can get the model converted to CoreML format from the link of Google drive.
See the section below for how to use it in Xcode.
The license for each model conforms to the license for the original project.


# Image Classifier

### Efficientnet

<img width="400" alt="スクリーンショット 2021-12-27 6 34 43" src="https://user-images.githubusercontent.com/23278992/147420587-108b87f8-7996-4288-905a-ad53f9142221.png">

| Google Drive Link | Size | Dataset |Original Project | License |
| ------------- | ------------- | ------------- |------------- |------------- |
| [Efficientnetb0](https://drive.google.com/file/d/1mJq8SMuDaCQHW77ui3fAfe5o3Qu2GKMi/view?usp=sharing) | 22.7 MB | ImageNet | [TensorFlowHub](https://tfhub.dev/tensorflow/efficientnet/b0/classification/1)  |[Apache2.0](https://opensource.org/licenses/Apache-2.0)|


### Efficientnetv2

<img width="400" alt="スクリーンショット 2021-12-31 4 30 22" src="https://user-images.githubusercontent.com/23278992/147782567-bbf26186-8c84-4073-8df4-b08e06d4e791.png">

| Google Drive Link | Size | Dataset |Original Project | License | Year|
| ------------- | ------------- | ------------- |------------- |------------- |------------- |
| [Efficientnetv2](https://drive.google.com/file/d/12JiGwXh8pX3yjoG_GsJOKAnPd3lbVrrn/view?usp=sharing) | 85.8 MB | ImageNet | [Google/autoML](https://github.com/google/automl/tree/master/efficientnetv2)  | [Apache2.0](https://github.com/google/automl/blob/master/LICENSE)|2021|

### VisionTransformer

An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale.

<img width="400" alt="スクリーンショット 2022-01-07 10 37 05" src="https://user-images.githubusercontent.com/23278992/148482246-64269fb4-fda4-4bd5-b219-5bf860fd77e7.png">

| Google Drive Link | Size | Dataset |Original Project | License |Year|
| ------------- | ------------- | ------------- |------------- |------------- |------------- |
| [VisionTransformer-B16](https://drive.google.com/file/d/1VPo8Cjv7dyicM4lcJ6TgxnD4AN3ldMQp/view?usp=sharing) | 347.5 MB | ImageNet | [google-research/vision_transformer](https://github.com/google-research/vision_transformer)  | [Apache2.0](https://github.com/google-research/vision_transformer/blob/main/LICENSE)|2021|

### Conformer

Local Features Coupling Global Representations for Visual Recognition.

<img width="400" alt="スクリーンショット 2022-01-07 11 34 33" src="https://user-images.githubusercontent.com/23278992/148482144-2d5bb7e8-ed67-4146-9f9d-c95fe94735d3.png">

| Google Drive Link | Size | Dataset |Original Project | License |Year|
| ------------- | ------------- | ------------- |------------- |------------- |------------- |
| [Conformer-tiny-p16](https://drive.google.com/file/d/1-4qVbuTYr4r4o08656iGtV8KKblAVVyr/view?usp=sharing) | 94.1 MB | ImageNet | [pengzhiliang/Conformer](https://github.com/pengzhiliang/Conformer)  | [Apache2.0](https://github.com/google-research/vision_transformer/blob/main/LICENSE)|2021|

### DeiT

Data-efficient Image Transformers

<img width="400" alt="スクリーンショット 2022-01-07 11 50 25" src="https://user-images.githubusercontent.com/23278992/148484220-38494287-49b4-4992-9ceb-9dc7b75a250e.png">

| Google Drive Link | Size | Dataset |Original Project | License |Year|
| ------------- | ------------- | ------------- |------------- |------------- |------------- |
| [DeiT-base384](https://drive.google.com/file/d/1-7J-b0fTjmZi2VDPrDCWKBsCYGxYP5yW/view?usp=sharing) | 350.5 MB | ImageNet | [facebookresearch/deit](https://github.com/facebookresearch/deit)  | [Apache2.0](https://github.com/facebookresearch/deit/blob/main/LICENSE)|2021|

### RepVGG

Making VGG-style ConvNets Great Again

<img width="400" alt="スクリーンショット 2022-01-08 5 00 53" src="https://user-images.githubusercontent.com/23278992/148600326-69dd9666-2709-4318-914b-30db8c294fd3.png">

| Google Drive Link | Size | Dataset |Original Project | License |Year|
| ------------- | ------------- | ------------- |------------- |------------- |------------- |
| [RepVGG-A0](https://drive.google.com/file/d/1i8mDvRGn2_OjzIG9ioVJyQrefVliKsh_/view?usp=sharing) | 33.3 MB | ImageNet | [DingXiaoH/RepVGG](https://github.com/DingXiaoH/RepVGG)  | [MIT](https://github.com/DingXiaoH/RepVGG/blob/main/LICENSE)|2021|

# Object Detection

### YOLOv5s

<img width="400" alt="スクリーンショット 2021-12-29 6 17 08" src="https://user-images.githubusercontent.com/23278992/147608051-be2ff345-22e8-4f82-83ed-7cc41ce4084d.png">

| Google Drive Link | Size | Output | Original Project | License | Note | Sample Project |
| ------------- | ------------- | ------------- | ------------- |------------- |------------- |------------- |
|[YOLOv5s](https://drive.google.com/file/d/1KT-9eKO4F-LYIJVYJg7dy2LEW_hVUq0M/view?usp=sharing)|29.3MB| Confidence(MultiArray (Double 0 × 80)), Coordinates (MultiArray (Double 0 × 4)) |[ultralytics/yolov5](https://github.com/ultralytics/yolov5)|[GNU](https://github.com/ultralytics/yolov5/blob/master/LICENSE)|Non Maximum Suppression has been added.| [CoreML-YOLOv5](https://github.com/john-rocky/CoreML-YOLOv5) |

# Segmentation

### [U2Net](https://drive.google.com/file/d/1cpm-x12Ih7Cqd_kOjfTvtt4ipGS3BpCx/view?usp=sharing)
<img width="400" src="https://camo.qiitausercontent.com/a8e89c72c0950db66d63415b9010d203aae22617/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e61702d6e6f727468656173742d312e616d617a6f6e6177732e636f6d2f302f3233353235392f36303037393162322d633534332d613537652d303639622d3863663130373932643662392e6a706567"> <img width="400" src="https://camo.qiitausercontent.com/4f502487cd9e9e02d150ad63b33683a1446e7516/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e61702d6e6f727468656173742d312e616d617a6f6e6177732e636f6d2f302f3233353235392f39636532633237612d643134322d663136352d343365662d6532373966646337386333382e706e67">

| Google Drive Link | Size | Output |Original Project | License |
| ------------- | ------------- | ------------- | ------------- |------------- |
| [U2Net](https://drive.google.com/file/d/1cpm-x12Ih7Cqd_kOjfTvtt4ipGS3BpCx/view?usp=sharing) | 175.9 MB | Image(GRAYSCALE 320 × 320)| [xuebinqin/U-2-Net](https://github.com/xuebinqin)  | [Apache](https://github.com/john-rocky/CoreML-Models/blob/master/Apache-LICENSE)|
| [U2Netp](https://drive.google.com/file/d/1D-quPGy33PzSEC6A7EBNv7mCyuiBlO08/view?usp=sharing) | 4.6 MB | Image(GRAYSCALE 320 × 320) | [xuebinqin/U-2-Net](https://github.com/xuebinqin)  |  [Apache](https://github.com/john-rocky/CoreML-Models/blob/master/Apache-LICENSE)|


### face-Parsing

<img src="https://user-images.githubusercontent.com/23278992/147860040-14a7e022-5490-4e51-98cd-cd421066dd8c.png" width=400> <img src="https://user-images.githubusercontent.com/23278992/147860042-d27f37b0-227b-45ab-8d76-f6c6f2f5b3a4.png" width=400>

| Google Drive Link | Size | Output |Original Project | License | Sample Project |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| [face-Parsing](https://drive.google.com/file/d/1I_cu8x0k6d1AEV_VPLyMu3Pqg3hwmo7g/view?usp=sharing) | 53.2 MB | MultiArray(1 x 512 × 512)| [zllrunning/face-parsing.PyTorch](https://github.com/zllrunning/face-parsing.PyTorch)  | [MIT](https://github.com/zllrunning/face-parsing.PyTorch/blob/master/LICENSE)|[CoreML-face-parsing](https://github.com/john-rocky/CoreML-Face-Parsing) |

### Segformer

Simple and Efficient Design for Semantic Segmentation with Transformers

<img src="https://user-images.githubusercontent.com/23278992/148621010-5ecf6b90-c501-4cf8-91e1-446850030265.png" width=400> <img src="https://user-images.githubusercontent.com/23278992/148621013-44d9cd29-ef3c-4250-bbd9-4e4093385a54.JPG" width=400>

| Google Drive Link | Size | Output |Original Project | License | year |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| [SegFormer_mit-b0_1024x1024_cityscapes](https://drive.google.com/file/d/1-lcNjJM85DZh5-xQv4jlKL6I1ZMBk2uu/view?usp=sharing) | 14.9 MB | MultiArray(512 × 1024)| [NVlabs/SegFormer](https://github.com/NVlabs/SegFormer)  | [NVIDIA](https://github.com/NVlabs/SegFormer/blob/master/LICENSE)|2021|

### BiSeNetV2	

Bilateral Network with Guided Aggregation for Real-time Semantic Segmentation

<img src="https://user-images.githubusercontent.com/23278992/148663182-c1f3b9dd-8db4-49be-bf92-97a898a8b477.jpg" width=400> <img src="https://user-images.githubusercontent.com/23278992/148663183-327dc684-342d-43f1-a8d8-ebf817c91bdd.JPG" width=400>

| Google Drive Link | Size | Output |Original Project | License | year |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| [BiSeNetV2_1024x1024_cityscapes](https://drive.google.com/file/d/1-20x0-TP8zqXCzDhH06TyL03SJRFYY9n/view?usp=sharing) | 12.8 MB | MultiArray | [ycszen/BiSeNet](https://github.com/ycszen/BiSeNet)  | Apache2.0 |2021|

### DNL

Disentangled Non-Local Neural Networks

<img src="https://user-images.githubusercontent.com/23278992/150061280-23a1de7c-2e12-41d2-9056-7c4b375193a6.jpg" width=400> <img src="https://user-images.githubusercontent.com/23278992/150061290-eed50b79-f5c0-4fa4-b5bf-728b9029f34c.png" width=400>

| Google Drive Link | Size | Output |Dataset|Original Project | License | year |
| ------------- | ------------- | ------------- |------------- | ------------- | ------------- | ------------- |
| [dnl_r50-d8_512x512_80k_ade20k](https://drive.google.com/file/d/1DOnPGocotsjXknBuNqikgpFVpmH6s_E3/view?usp=sharing) | 190.8 MB | MultiArray[512x512] |ADE20K| [yinmh17/DNL-Semantic-Segmentation](https://github.com/yinmh17/DNL-Semantic-Segmentation)  | [Apache2.0](https://github.com/yinmh17/DNL-Semantic-Segmentation/blob/master/LICENSE) |2020|

# Super Resolution

### [Real ESRGAN](https://drive.google.com/file/d/1cpm-x12Ih7Cqd_kOjfTvtt4ipGS3BpCx/view?usp=sharing)
<img width="400" src="https://user-images.githubusercontent.com/23278992/147418147-47f2089f-80ea-4688-ac06-7d9c4b46a08e.png"> <img width="400" src="https://user-images.githubusercontent.com/23278992/147418143-b8f89073-afa1-4c5c-95e9-2ee8a00a94b9.JPG"> 

| Google Drive Link | Size | Output |Original Project | License | year |
| ------------- | ------------- | ------------- | ------------- | ------------- |------------- |
| [Real ESRGAN](https://drive.google.com/file/d/1uK41SGHyQf_h6trI9bCb83VIBlfKFkag/view?usp=sharing) | 66.9 MB | Image(RGB 1280x1280)| [xinntao/Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)  | [BSD 3-Clause License](https://github.com/john-rocky/CoreML-Models/blob/master/Real-ESRGAN-License) |2021|

### [BSRGAN](https://drive.google.com/file/d/1-3K89vJZ5OUAh4xdSAifgnL52jbl2fVf/view?usp=sharing)
<img width="400" src="https://user-images.githubusercontent.com/23278992/148810656-4c5faa33-1be9-45f6-b31a-defd931cb1f8.jpg"> <img width="400" src="https://user-images.githubusercontent.com/23278992/148811822-56844bc7-b197-44d5-8454-757890c890b5.jpg"> 

| Google Drive Link | Size | Output |Original Project | License |year |
| ------------- | ------------- | ------------- | ------------- | ------------- |------------- |
| [BSRGAN](https://drive.google.com/file/d/1-3K89vJZ5OUAh4xdSAifgnL52jbl2fVf/view?usp=sharing) | 66.9 MB | Image(RGB 2048x2048)| [cszn/BSRGAN](https://github.com/cszn/BSRGAN)  |  |2021|


# Low Light Enhancement

### StableLLVE

Learning Temporal Consistency for Low Light Video Enhancement from Single Images.

<img width="400" src="https://user-images.githubusercontent.com/23278992/148664179-4d0cd417-d8f9-4d0e-bc05-cff3a4a30b5a.jpg"> <img width="400" src="https://user-images.githubusercontent.com/23278992/148664220-c756198f-e8c5-4ea8-8737-59c004d2f08c.jpg"> 

| Google Drive Link | Size | Output |Original Project | License |Year|
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| [StableLLVE](https://drive.google.com/file/d/1-9xry7XeCJYsZadxcfTscjGi_Sna5NhM/view?usp=sharing) | 17.3 MB | Image(RGB 512x512)| [zkawfanx/StableLLVE](https://github.com/zkawfanx/StableLLVE)  | [MIT](https://github.com/zkawfanx/StableLLVE/blob/main/LICENSE) |2021|

# Image Restoration

### MPRNet

Multi-Stage Progressive Image Restoration.

Debluring

<img width="400" src="https://user-images.githubusercontent.com/23278992/149243725-79c68d8e-db6c-4114-ac64-738cd6b5c37c.jpg"> <img width="400" src="https://user-images.githubusercontent.com/23278992/149243509-7eff6ae8-65c2-45ba-bfa2-d730657ab2bd.png"> 

Denoising

<img width="400" src="https://user-images.githubusercontent.com/23278992/149241165-534c54db-7e98-4356-8613-44acb93d4c6a.png"> <img width="400" src="https://user-images.githubusercontent.com/23278992/149242199-7cc3e456-7c8d-441c-b0aa-f1b6ca19a5c9.png"> 

Deraining

<img width="400" src="https://user-images.githubusercontent.com/23278992/149241095-91791593-416e-41b0-8a95-71819cb7fb06.jpg"> <img width="400" src="https://user-images.githubusercontent.com/23278992/149241720-afe94607-e9c2-45bb-988d-3c322d7dde1a.jpg"> 

| Google Drive Link | Size | Output |Original Project | License |Year|
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| [MPRNetDebluring](https://drive.google.com/file/d/1--5L6BxxbyYGY9ey5WCIrl7g1yYBN27U/view?usp=sharing) | 137.1 MB | Image(RGB 512x512)| [swz30/MPRNet](https://github.com/swz30/MPRNet)  | [MIT](https://github.com/swz30/MPRNet/blob/main/LICENSE.md) |2021|
| [MPRNetDeNoising](https://drive.google.com/file/d/1-04xou-UgoflZb7MqTBycCpuLWKUAj0i/view?usp=sharing) | 108 MB | Image(RGB 512x512)| [swz30/MPRNet](https://github.com/swz30/MPRNet)  | [MIT](https://github.com/swz30/MPRNet/blob/main/LICENSE.md) |2021|
| [MPRNetDeraining](https://drive.google.com/file/d/1tGvjj49yaDym24vGdGqr1VKOtGd7ALKB/view?usp=sharing) | 24.5 MB | Image(RGB 512x512)| [swz30/MPRNet](https://github.com/swz30/MPRNet)  | [MIT](https://github.com/swz30/MPRNet/blob/main/LICENSE.md) |2021|

# Image Generation

### [MobileStyleGAN](https://drive.google.com/drive/folders/1rUV6AXwp8JhPPmkog-0r0AUGzUvN9DmW?usp=sharing)
<img width="400" src="https://user-images.githubusercontent.com/23278992/147397892-773c55ca-55fc-422b-a95b-a729eda04077.JPG"> <img width="400" src="https://user-images.githubusercontent.com/23278992/147397894-e2d3a1ef-7afa-410a-9580-f09ef7157c50.JPG"> 

| Google Drive Link | Size | Output | Original Project | License | Sample Project |
| ------------- | ------------- | ------------- | ------------- |  ------------- |  ------------- | 
| [MobileStyleGAN](https://drive.google.com/drive/folders/1rUV6AXwp8JhPPmkog-0r0AUGzUvN9DmW?usp=sharing) | 38.6MB  | Image(Color 1024 × 1024)| [bes-dev/MobileStyleGAN.pytorch](https://github.com/bes-dev/MobileStyleGAN.pytorch)  | [Nvidia Source Code License-NC](https://github.com/bes-dev/MobileStyleGAN.pytorch/blob/develop/LICENSE-NVIDIA) | [CoreML-StyleGAN](https://github.com/john-rocky/CoreML-StyleGAN) |


### [DCGAN](https://drive.google.com/file/d/132GrmmuETSLTml1zWyLUnIksclP-8vGw/view?usp=sharing)
<img width="400" src="https://user-images.githubusercontent.com/23278992/144690829-3a4cebcf-ee73-4df0-b8db-1dfc2e616798.png">

| Google Drive Link | Size | Output | Original Project | 
| ------------- | ------------- | ------------- | ------------- | 
| [DCGAN](https://drive.google.com/file/d/132GrmmuETSLTml1zWyLUnIksclP-8vGw/view?usp=sharing)　| 9.2MB | MultiArray | [TensorFlowCore](https://www.tensorflow.org/tutorials/generative/dcgan)|


# Image2Image

### [Anime2Sketch](https://drive.google.com/file/d/1-52NnZ1kajZI5Rk0tn3DegpU38la_jYk/view?usp=sharing)
<img width="400" src="https://user-images.githubusercontent.com/23278992/147990751-9ac35e43-b9a6-4db2-af5c-37978322240d.jpeg"> <img width="400" src="https://user-images.githubusercontent.com/23278992/147990892-d676142c-62c4-433d-9835-337b1293bfc4.jpeg">

| Google Drive Link | Size | Output | Original Project | License | Usage |
| ------------- | ------------- | ------------- | ------------- | ------------- |  ------------- | 
| [Anime2Sketch](https://drive.google.com/file/d/1-52NnZ1kajZI5Rk0tn3DegpU38la_jYk/view?usp=sharing) | 217.7MB  | Image(Color 512 × 512)| [Mukosame/Anime2Sketch](https://github.com/Mukosame/Anime2Sketch)  | [MIT](https://github.com/Mukosame/Anime2Sketch/blob/master/LICENSE)| Drop an image to preview|


### [AnimeGAN2Face_Paint_512_v2](https://drive.google.com/file/d/1phSgcAz3LNbk2v2RoSESmr7PFxTAHcxb/view?usp=sharing)
<img width="400" src="https://camo.qiitausercontent.com/74a02b6e0b80e52c2ae3af798c93eea9aa3e394d/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e61702d6e6f727468656173742d312e616d617a6f6e6177732e636f6d2f302f3233353235392f30313764616563342d333933312d643664662d303339322d6162313039303237313963642e706e67"> <img width="400" src="https://camo.qiitausercontent.com/311349da47136ff9ce61701d09ce59dc663c95bf/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e61702d6e6f727468656173742d312e616d617a6f6e6177732e636f6d2f302f3233353235392f66633337653936332d383533302d333731312d643163662d3335366266646666316665322e706e67">

| Google Drive Link | Size | Output | Original Project | 
| ------------- | ------------- | ------------- | ------------- | 
| [AnimeGAN2Face_Paint_512_v2](https://drive.google.com/file/d/1phSgcAz3LNbk2v2RoSESmr7PFxTAHcxb/view?usp=sharing) | 8.6MB  | Image(Color 512 × 512)| [bryandlee/animegan2-pytorch](https://github.com/bryandlee/animegan2-pytorch#additional-model-weights)  |


### [Photo2Cartoon](https://drive.google.com/file/d/1xFWZ9Rf1o_LtwBpmSw2zSwPGk2FY6Wya/view?usp=sharing)
<img width="400" src="https://user-images.githubusercontent.com/23278992/147394190-01a2c6be-5056-4f83-b4af-3f494dad47f4.png"> <img width="400" src="https://user-images.githubusercontent.com/23278992/147394192-46de7634-c3ce-481f-afa5-8a7ab4603f2e.png">

| Google Drive Link | Size | Output | Original Project | License | Note |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| [Photo2Cartoon](https://drive.google.com/file/d/1xFWZ9Rf1o_LtwBpmSw2zSwPGk2FY6Wya/view?usp=sharing) | 15.2 MB  | Image(Color 256 × 256)| [minivision-ai/photo2cartoon](https://github.com/minivision-ai/photo2cartoon) | [MIT](https://github.com/minivision-ai/photo2cartoon/blob/master/LICENSE) | The output is little bit different from the original model. It cause some operations were converted replaced　manually. |

### [AnimeGANv2_Hayao](https://drive.google.com/file/d/1G53oZ1hiMcLJs1loN_fe_VmBVfegh9ha/view?usp=sharing)
<img width="400" src="https://user-images.githubusercontent.com/23278992/147421574-8f38367c-d5c5-442d-9742-7b2bb24d43e4.jpg"> <img width="400" src="https://user-images.githubusercontent.com/23278992/147421569-df8e2e59-fef8-4db4-9cb2-65ee960ef705.png">

| Google Drive Link | Size | Output | Original Project | 
| ------------- | ------------- | ------------- | ------------- | 
| [AnimeGANv2_Hayao](https://drive.google.com/file/d/1G53oZ1hiMcLJs1loN_fe_VmBVfegh9ha/view?usp=sharing)　| 8.7MB | Image(256 x 256) | [TachibanaYoshino/AnimeGANv2](https://github.com/TachibanaYoshino/AnimeGANv2)|


### [AnimeGANv2_Paprika](https://drive.google.com/file/d/10drMcmF67iREUK8NY8ekMHrsyVirs5XT/view?usp=sharing)
<img width="400" src="https://user-images.githubusercontent.com/23278992/144670978-1447ce28-db49-4cf9-b484-3142ef703ade.jpg"> <img width="400" src="https://user-images.githubusercontent.com/23278992/144671455-f7258cc9-1a3e-49df-8bbb-03285c619b17.png">

| Google Drive Link | Size | Output | Original Project | 
| ------------- | ------------- | ------------- | ------------- | 
| [AnimeGANv2_Paprika](https://drive.google.com/file/d/10drMcmF67iREUK8NY8ekMHrsyVirs5XT/view?usp=sharing)　| 8.7MB | Image(256 x 256) | [TachibanaYoshino/AnimeGANv2](https://github.com/TachibanaYoshino/AnimeGANv2)|


### [WarpGAN Caricature](https://drive.google.com/file/d/1HE3qvfjuXZMFelRcmmGsLzoO5dV8lnaQ/view?usp=sharing)
<img width="400" src="https://user-images.githubusercontent.com/23278992/147397894-e2d3a1ef-7afa-410a-9580-f09ef7157c50.JPG"> <img width="400" src="https://user-images.githubusercontent.com/23278992/147421276-574edb28-f909-4830-afd0-5cb41328bdba.JPG">

| Google Drive Link | Size | Output | Original Project | 
| ------------- | ------------- | ------------- | ------------- | 
| [WarpGAN Caricature](https://drive.google.com/file/d/1HE3qvfjuXZMFelRcmmGsLzoO5dV8lnaQ/view?usp=sharing)　| 35.5MB | Image(256 x 256) | [seasonSH/WarpGAN](https://github.com/seasonSH/WarpGAN)|

### [UGATIT_selfie2anime](https://drive.google.com/file/d/1o15OO0Kn0tq79fFkmBm3PES93IRQOxB-/view?usp=sharing)

<img width="400" alt="スクリーンショット 2021-12-27 8 18 33" src="https://user-images.githubusercontent.com/23278992/147422391-847b3c75-3e6e-419e-9a53-f6138b9ac813.png"> <img width="400" alt="スクリーンショット 2021-12-27 8 28 11" src="https://user-images.githubusercontent.com/23278992/147422387-2b71a135-cd9c-4f02-8223-65bf365cda4e.png">

| Google Drive Link | Size | Output | Original Project | 
| ------------- | ------------- | ------------- | ------------- | 
| [UGATIT_selfie2anime](https://drive.google.com/file/d/1o15OO0Kn0tq79fFkmBm3PES93IRQOxB-/view?usp=sharing) | 266.2MB(quantized) | Image(256x256) | [taki0112/UGATIT](https://github.com/taki0112/UGATIT)  |

### CartoonGAN

| Google Drive Link | Size | Output | Original Project | 
| ------------- | ------------- | ------------- | ------------- | 
| [CartoonGAN_Shinkai](https://drive.google.com/file/d/1j9bvHFBX5yctSeaE8FEvUv-r-hEVvXwi/view?usp=sharing)　| 44.6MB | MultiArray | [mnicnc404/CartoonGan-tensorflow](https://github.com/mnicnc404/CartoonGan-tensorflow)|
| [CartoonGAN_Hayao](https://drive.google.com/file/d/1-2dTGge4fza-TTBI9actkg_xp91zYT-F/view?usp=sharing)　| 44.6MB | MultiArray | [mnicnc404/CartoonGan-tensorflow](https://github.com/mnicnc404/CartoonGan-tensorflow)|
| [CartoonGAN_Hosoda](https://drive.google.com/file/d/1-5VB1g7kRt0KMe6u37fi_t18l-Zn_wr1/view?usp=sharing)　| 44.6MB | MultiArray | [mnicnc404/CartoonGan-tensorflow](https://github.com/mnicnc404/CartoonGan-tensorflow)|
| [CartoonGAN_Paprika](https://drive.google.com/file/d/1-5x3TYugodcnGYiEEDitFqMQPVHsCDs_/view?usp=sharing)　| 44.6MB | MultiArray | [mnicnc404/CartoonGan-tensorflow](https://github.com/mnicnc404/CartoonGan-tensorflow)|




## How to use in a xcode project.

### Option 1,implement Vision request.

```swift:

import Vision
lazy var coreMLRequest:VNCoreMLRequest = {
   let model = try! VNCoreMLModel(for: modelname().model)
   let request = VNCoreMLRequest(model: model, completionHandler: self.coreMLCompletionHandler)
   return request
   }()

let handler = VNImageRequestHandler(ciImage: ciimage,options: [:])
   DispatchQueue.global(qos: .userInitiated).async {
   try? handler.perform([coreMLRequest])
}
```

If the model has Image type output:

```swift
let result = request?.results?.first as! VNPixelBufferObservation
let uiimage = UIImage(ciImage: CIImage(cvPixelBuffer: result.pixelBuffer))
```

Else the model has Multiarray type output:

For visualizing multiArray as image, Mr. Hollance’s “CoreML Helpers” are very convenient.
[CoreML Helpers](https://github.com/hollance/CoreMLHelpers)

[Converting from MultiArray to Image with CoreML Helpers.](https://medium.com/@rockyshikoku/converting-from-multiarray-to-image-with-coreml-helpers-59fdc34d80d8)

```swift:
func coreMLCompletionHandler（request：VNRequest？、error：Error？）{
   let = coreMLRequest.results？.first as！VNCoreMLFeatureValueObservation
   let multiArray = result.featureValue.multiArrayValue
   let cgimage = multiArray？.cgImage（min：-1、max：1、channel：nil）
```

### Option 2,Use [CoreGANContainer](https://github.com/john-rocky/CoreGANContainer). You can use models with dragging&dropping into the container project. 

# Make the model lighter
You can make the model size lighter with Quantization if you want.
https://coremltools.readme.io/docs/quantization
>The lower the number of bits, more the chances of degrading the model accuracy. The loss in accuracy varies with the model.

```python
import coremltools as ct
from coremltools.models.neural_network import quantization_utils

# load full precision model
model_fp32 = ct.models.MLModel('model.mlmodel')

model_fp16 = quantization_utils.quantize_weights(model_fp32, nbits=16)
# nbits can be 16(half size model), 8(1/4), 4(1/8), 2, 1
```

##### quantized sample (U2Net)

##### InputImage / nbits=32(original) / nbits=16 / nbits=8 / nbits=4

<img src="https://user-images.githubusercontent.com/23278992/147712147-0959c0b9-9d4b-4049-9dd9-7a9d1ffa0eed.JPEG" width=200> <img src="https://user-images.githubusercontent.com/23278992/147712215-dd0c8788-75ad-4676-804a-fdd47233daa6.JPG" width=200> <img src="https://user-images.githubusercontent.com/23278992/147712220-d02ab436-9716-4cdc-91d3-8b6f3aa01fac.JPG" width=200> <img src="https://user-images.githubusercontent.com/23278992/147712259-aabf5ecf-db59-476d-8f36-e6027dfb91e2.JPG" width=200> <img src="https://user-images.githubusercontent.com/23278992/147712328-a44f538c-aa3e-431d-98ec-626239262e01.JPG" width=200>



# Thanks
Cover image was taken from Ghibli free images. 

On YOLOv5 convertion, [dbsystel/yolov5-coreml-tools](https://github.com/dbsystel/yolov5-coreml-tools) give me the super inteligent convert script. 

And all of original projects

# Auther

Daisuke Majima
Freelance engineer. iOS/MachineLearning/AR
I can work on mobile ML projects and AR project.
Feel free to contact: rockyshikoku@gmail.com

[GitHub](https://github.com/john-rocky)
[Twitter](https://twitter.com/JackdeS11)
[Medium](https://rockyshikoku.medium.com/)

