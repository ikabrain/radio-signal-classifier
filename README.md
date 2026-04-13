# Classifying Radio Signals with PyTorch

This project involves loading a pre-trained state-of-the-art CNN to classify radio signals (with inputs as spectogram images) into Squiggle, Noises, Narrowband, etc. Furthermore, we apply spectogram augmentation using time & frequency masking. This could practically be used in contexts involving military, security, telecommunications, and space technology.

## Dataset Description
<img src="Untitled-design.png" alt="Radio Signal Classes - Noise, Squiggle, Narrowband, Narrowbanddrd" height=300/>

## Model Architecture: EfficientNet-B0
EfficientNet-B0 consists of seven blocks which are shown in different colours. The basic building block of EfficientNet-B0 is a mobile inverted bottleneck convolution (MBConv), while each MBConv block is shown with the corresponding kernel filter size.
<img src="https://www.researchgate.net/publication/361521546/figure/fig2/AS:11431281122798843@1677553158796/The-detailed-architecture-of-EfficientNet-B0-EfficientNet-B0-consists-of-seven-blocks.png" alt="Detailed architecture of EfficientNet-B0" height=200/>

## References

Dhameliya, P. (n.d). Classify Radio Signals with PyTorch [MOOC]. Coursera. https://www.coursera.org/learn/classify-radio-signals-with-pytorch

Zhou, Aihua & Ma, Yujun & Ji, Wanting & Zong, Ming & Yang, Pei & Wu, Min & Liu, Mingzhe. (2022). Multi-head attention-based two-stream EfficientNet for action recognition. Multimedia Systems. 29. 1-12. 10.1007/s00530-022-00961-3.

PyTorch. (n.d). PyTorch documentation. https://docs.pytorch.org/docs

torchvision. (n.d). PyTorch's torchvision library documentation. https://docs.pytorch.org/vision/

Prefix.dev. (n.d.). Pixi documentation. https://pixi.prefix.dev/latest/
