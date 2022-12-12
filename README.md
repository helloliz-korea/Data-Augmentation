# Data-Augmentation
1. G3-augmentation-ex : data augmentation, Image augmentation
   - flip, center crop, random crop, random brightness
   - imgaug library
2. G4-stanford-dog-ex : 개의 사진을 보고 120 종의 품종을 구별
   - Dataset : https://www.kaggle.com/datasets/jessicali9530/stanford-dogs-dataset
   - (또는) http://vision.stanford.edu/aditya86/ImageNetDogs/
   - 캐글 평가방법 : multi class logarithmic loss를 이용하여 품종을 맞췄는지 정확도 측정
   - 데이터 구성 : 각기 다른 사이즈의 이미지와 품종
3. Cutmix, Mixup 
