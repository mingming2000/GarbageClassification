# GarbageClassification
KUCC x YCC AI 부트캠프


### 재활용 쓰레기 분류 AI 개발
<img src="https://user-images.githubusercontent.com/102716945/221347763-ce265e29-fc48-41b3-8aa4-888f7e6a8ce2.jpg" width="748" height="529"/>



<img src="https://user-images.githubusercontent.com/102716945/221347984-54ea2875-baa3-40e6-8682-eccc6d6b361f.jpg" width="748" height="529"/>



### 문제 인식
<img src="https://user-images.githubusercontent.com/102716945/221348061-46db8bae-beec-4dd7-8964-95d96da1fb36.JPG" width="748" height="529"/>
분리 수거의 효율을 높이기 위해, 사진을 찍으면 쓰레기를 분류해주는 AI 제작



### Dataset
<img src="https://user-images.githubusercontent.com/102716945/221348063-275e5c3e-244b-4e84-960b-e856c1b77051.JPG" width="748" height="529"/>
Kaggle 대회 'Garbage Classification (12 classes)'의 약 15,000개 이미지

https://www.kaggle.com/datasets/mostafaabla/garbage-classification


### 프로젝트 목표
<img src="https://user-images.githubusercontent.com/102716945/221348057-3d529c31-e764-4791-b026-d50f1c09e74a.JPG" width="748" height="529"/>



### 프로젝트 세부 목표
<img src="https://user-images.githubusercontent.com/102716945/221348482-70fb7831-823b-4481-a7b0-8ddeb0589b85.JPG" width="748" height="529"/>
1. 직접 로더 및 모델 구현 
2. 전이학습, 파인튜닝으로 모델 성능 향상
3. 여러 튜닝 기법 활용: WandB를 이용한 AutoML, optimization, regularization

### 튜닝 과정
![슬라이드13](https://user-images.githubusercontent.com/102716945/221348670-6969ad6b-dc3e-4786-af4c-9ed30761d4a1.JPG)
![슬라이드14](https://user-images.githubusercontent.com/102716945/221348672-88eb43bf-d117-461b-85ba-e730e825a38a.JPG)
![슬라이드15](https://user-images.githubusercontent.com/102716945/221348673-454b5f81-3b2c-4bae-a046-309d71027f4a.JPG)
![슬라이드16](https://user-images.githubusercontent.com/102716945/221348674-8e886fd9-1da5-4897-8448-cfffa8d4a4c3.JPG)
![슬라이드17](https://user-images.githubusercontent.com/102716945/221348675-1d3a284d-ef10-4754-8025-d2e9297cbbf5.JPG)
![슬라이드18](https://user-images.githubusercontent.com/102716945/221348678-92c64f3c-52b0-4ae1-8540-3ce57d45f9cc.JPG)

### 최종 모델
Accuracy: 95.0999%
![슬라이드19](https://user-images.githubusercontent.com/102716945/221348742-5d891ce7-8f8b-466b-96d8-77c93ed68a46.JPG)

### Custom Dataset으로 Test
![슬라이드21](https://user-images.githubusercontent.com/102716945/221348754-6e12efc1-b651-4005-9c0a-cb97267a9942.JPG)
white glass, carboard, plastic, white glass로 분류
마지막 사진은 plastic이지만, 사람의 눈으로도 white glass인지 plastic인지 구분이 어려울 수 있는 사진이므로 (Accuracy를 평가하는 기준: Human Level Performance)
예측이 틀렸을 것. 데이터셋을 늘리면 해결이 될 여지가 있긴 함.

### 아쉬운 점 및 보충할 부분
![슬라이드20](https://user-images.githubusercontent.com/102716945/221348836-d8256286-4d28-46b8-bd0f-8f0999a60c09.JPG)




