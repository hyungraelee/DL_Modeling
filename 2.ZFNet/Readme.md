# PyTorch Implementation of ZFNet

## ENV
- NVIDIA DGX A100
- Python 3.8.5
- PyTorch 1.8.0
- cuda 11.1.1

## Dataset
- CIFAR10 (train-40000, validation-10000, test-10000)

아래의 이미지는 특정 이미지의 4번째 Convolutional Layer의 출력 feature map을 각 1, 2, 5, 10, 20, 30, 40, 64 epoch 시점에서 시각화 한 결과입니다.
![conv4](https://user-images.githubusercontent.com/70879607/172789878-9655a435-66e1-4669-99bf-d21be255c045.png)

아래의 이미지는 한 이미지의 각 1, 2, 3, 4, 5번째 Convolutional Layer 에서의 출력 feature map을 시각화 한 결과입니다.
![eachlayer](https://user-images.githubusercontent.com/70879607/172789912-cfce2854-1979-4560-9f72-8f5e68a5d4cb.png)


## Papers
https://arxiv.org/abs/1311.2901

## Blog
https://velog.io/@hyungraelee/Visualizing-and-understanding-convolutional-networks-논문-학습-정리
