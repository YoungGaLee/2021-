# 2021 학부생 하계 프로젝트

학부생 논문스터디 이후 진행하는 개인 프로젝트로 직접 Dataset을 임의의 모델에 돌려 원하는 task를 수행한다.

<br>



## YOLOR - Object Detection
**YOLOR** 모델을 통해 Classification 없이 **Detection**만 하는 task를 수행한다.   
pretrain된 YOLOR 모델을 **CARPK dataset** 로 fine tuning 시키고 **COCO dataset**으로 평가한다.


<br>

<img src = "https://user-images.githubusercontent.com/43063980/128506549-5ffd6b42-a1bd-4845-bc44-5d6a13fbcf97.png" width="80%">


> Paper  https://arxiv.org/pdf/2105.04206.pdf  
Github  https://github.com/WongKinYiu/yolor

<br>


- **Dataset** : [CARPK](https://paperswithcode.com/dataset/carpk) / [COCO](https://paperswithcode.com/dataset/coco)   
- **평가방식** : COCO mAP

<br>



### 목표
- git을 통해 프로젝트 관리하기
- COCO mAP 평가방식 공부하고 cocoeval.py 코드 확인하기
- 학습결과와 weight 저장하기

