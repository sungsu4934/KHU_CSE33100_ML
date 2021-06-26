## Image Classification competition
최신 CNN 모델(Densenet, PyramidNet 등)과 최신 Computer vision 기술을 활용한 Competition (파라미터 200만개 이하 제한)
 - Tool: python (pytorch)
 - Metric: Accuracy
 - Rank: (5/23)
 - Data: 2D Image data (10 class)
  > https://www.kaggle.com/c/khu-machine-learning-competition

### 시행착오로 활용된 모델
1. VGGNet
2. ResNet
3. Wide-ResNet
4. DenseNet
5. PyramidNet

### 시행착오로 활용된 기술
1. Scheduler (CosineAnnealing, Exponential LR, Loss Plateau Decay 등)
2. LabelSmoothing
3. SAM Optimizer
4. Shakedrop
5. Data Augmenation
6. Gaussian Noise
7. Activation Function (LeakyReLU, swish, mish ,,, 등)

### 최종 Competition에서 활용한 모델 및 기술
 - Model: PyramidNet (Layer: 196, Alpha: 48)
 - Technique: LeakyReLU, SAM Optimizer, CosineAnnealing Scheduler, Shakedrop, LabelSmoothing
