# 음성 인식 프로젝트 
 
## 1, 프로젝트 수행 기간  

기획	  9/13(금) ~ 9/27(금)	 아이디어 선정 및 프로젝트 계획	

데이터 수집	9/19(목) ~ 9/2O(금)	데이터 수집 및 선별	

데이터 전처리	9/28(토) ~ 10/3(목)	음성 및 텍스트 데이터 전처리	

모델 선정	9/30(월) ~ 10/2(수)	모델 리서치 및 선정	팀별 중간보고 실시

모델 구축	10/4(금) ~ 10/6(일)	모델 구축 및 개선	최적화, 오류 수정

총 개발기간	9/13(월) ~ 1O/7(월)	

## 2, 웹 

웹 부분은 플라스크를 사용했다. 

## 3, 모델 

딥러닝은 CNN을 사용하였다 

 ※모델설계 
![architecture](https://github.com/user-attachments/assets/db4b3445-9c6a-4a47-9592-759c56efe976)


## 4, 데이터

데이터는 는 0~9의 숫자 이미지로 이루어진 MNIST train 6만장 test 3만장으로 사용하였다. 

## 5, 결과 

결과는  output.jpg처럼 나왔고, 전체 설계도는 architecture.jpg로 만들었다. 

![output](https://github.com/user-attachments/assets/1b99198e-7867-45a8-b8a9-73ff65e16413)

## 6, 참고

Krizhevsky, Alex, Ilya Sutskever, and Geoffrey E. Hinton. "Imagenet classification with deep convolutional neural networks.

" Advances in neural information processing systems 25 (2012). 을 하였고, 

느낌점은, CNN으로는 0~9 이미지의 학습 성능이 잘 나왔지만 

transform을 어떻게 주냐에 따라서 성능을 감소시키는 기법들이 뭐인지 리포트하고 싶었다.


