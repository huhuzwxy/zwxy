# semantic segmentation of Medical Images

- - -
## 发展流程
- edge detection filters and mathematical methods
- machine learning approaches extracting hand-crafted features
- deep learning techniques
- - -

## network structure

1. CNN
    - patch-wise prediction

2. Fully Convolutional Network（FCN）
    - pixel-wise prediction from the full-sized image
    - up-sampling the output feature map
    - 保护纹理信息，混合粗粒度层和细粒度层
    - Cascaded FCN（以肝部问题为例，先分割肝，然后在肝上分割病灶）

3. Encoder-decoder Network

    ### U-Net
    - a contracting path to capture context
    - a symmetric expanding path that enables precise localization
    - skip connections

    ### DCAN

    ### V-Net
    - Residual connections
    - dice loss

    ### DenseNet

4. Attention-based

5. Adversarial-based

6. Recurrent Neural Network-based

## Transfer Learning

## loss function

## challenges and limitations




