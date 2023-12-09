# AIsystem 실습1) 식물별 질병 분류하기

CNN을 이용하여 33개의 클래스를 분류하는 task입니다.
(여러 종류의 식물들이 있고, 각 식물별로 healthy + 다양한 종류의 질병명 폴더가 들어있습니다. 그래서 분류할 수 있는 클래스가 총 33개입니다.)

더불어 ImageNet을 pre-training한 ResNet모델을 활용하여 transfer learning도 하여, 
base 모델 (transfer learning을 안 한 것)과 transfer learning(fine tuning)을 한 모델의 정확도를 비교해보았습니다.

base모델은 약 92%, transfer learning을 한 모델은 약 98%의 성능을 보였습니다. 
