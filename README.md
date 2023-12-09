# AIsystem

CNN을 이용하여 33개의 클래스를 분류하는 task입니다.

더불어 ImageNet을 pre-training한 ResNet모델을 활용하여 transfer learning도 하여, 
base 모델 (transfer learning을 안 한 것)과 transfer learning(fine tuning)을 한 모델의 정확도를 비교해보았습니다.

base모델은 약 92%, transfer learning을 한 모델은 약 98%의 성능을 보였습니다. 
