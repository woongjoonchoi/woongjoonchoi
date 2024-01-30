## Hi there 👋

I'm ML(machine learning) Engineer who specialize in DeepLearning.
## TechStack
+ Languages:	Python([링크](https://woongjoonchoi.github.io/categories/Python)  , Java, C++([링크](https://github.com/woongjoonchoi/Algorithm))
+ Tool : 		Slack , Zoom, Git([링크](https://woongjoonchoi.github.io/categories/CICD)) ,VsCode ,Jupyter Notebook, drawio
+ CS:		Data structures and algorithms([링크](https://github.com/woongjoonchoi/CodingTest/tree/main/geeksforgeeks)), Networking  , Operating   System ,Programming Language ,           Theory and Compiler , Database , cryptology
+ AI:		Pytorch([링크](https://woongjoonchoi.github.io/categories/Pytorch)),Deep Learning([링크](https://woongjoonchoi.github.io/categories/DLArchitecture)),NLP,Computer Vision , Machine Learning ,Linear Algebra, Statistics & Probability
+ Cloud:		GCP

## Carrer
<details>
    <summary>자세히 보기</summary>  
    
### Naver boostcamp AI Tech
2021.Aug - 2022.Jan  
+ 3개의 Team을 적극적으로 이끌며 , 문서 관리 및 GIt을 사용한 프로젝트 관리. 이를 통해 주도적으로 원격협업을 이끌었음.
+ 내부 Competetion에서 Team을 리드하여 , 각각 3등 , 6등의 성과를 달성함
+ 기초 Coruse에서 Math,Python,Data Visualization , DeepLearning Architecture 관련 지식을 습득함.
+ NLP Course Track을 선택하여 LLM,ODQA,Relation Extraction 등의 task를 학습하였음.
+ 내부 커뮤니티에서 매일 글쓰기 활동 및 Q&A 활동을 적극적으로 임하여 노력왕에 선정됨
### Google MachineLearning Bootcamp
2021.Aug - 2021.DEC  
+ Coursera의 DeepLearning Specialization Course를 수강하여 딥러닝 task에 대해 이론적인 지식을 강화함
+ Google Cloud의 Professional Data Engineer 자격증을 취득함.

</details>  

## Personal Project

<details>
    <summary>자세히 보기</summary>  
  
### DeepLearning Paper Reproducing  (2023.11~)
+ DeepLearning Paper의 모든 configuration을 복제하여 논문의 성능을 재현하고자 함.
+ 현재 진행중
### AI Paperboy (2021.10~2021.12)
+ 4명의 팀을 리드하고 , 슬랙을 사용하여 개인 업무 관리, 줌을 사용하여 미팅을 진행 , 구글 드라이브를 사용하여 문서 관리 및 GIt을 사용한 프로젝트 관리. 이를 통해 주도적으로 원격협업을 이끌었음.
 유저가 뉴스 검색후 관련 뉴스를 검색하는 과정을 줄이기 위해서 관련 뉴스 스니펫을 저장하는 LLM Aplication을 개발해서  관련 뉴스 검색의 4단계 과정을 1단계로 줄여서  검색시간을 40% 감소.
+ 84만개의 뉴스 데이터를 수집하여 개인정보,저작권,특수문자 등을 정규표현식을 사용하여 제거 하고  맞춤법을 교정하는 전처리 진행
+ Huggingface에서 제공하는 klue/roberta-large model을 Pytorch에서 수집한 뉴스 데이터로  fine-tuning 해서 ODQA model을 구현 .Weight & Bias 플랫폼에서 Bayesian Search를 사용하여 Hyperparameter search를 수행. baseline 대비 30%의 성능 향상
+ User flow와 Data Flow를 작성하여  specification을 만들고 , fastapi를 통해서 모델을 웹API로 만든후  GCP의 server에 배포함
+ Github 링크 :[링크](https://github.com/woongjoonchoi/final-project-level3-nlp-19)  Youtube 링크:[링크](https://www.youtube.com/watch?v=rSTLV5TtJIY&t=16s)
### Relation Extraction (2021.09~2021.10)
+ 5명의 팀을 리드하고 , 줌을 통해 원격으로 회의 진행 및 weight&bias 에서 팀의  hyperparameter search 및 model evaluation 결과를 관리하여 주도적으로 원격협업을 이끌엇음.
+ Competition에서 ,문장에서 2개의 entity간의 관계를 분류하는  Model을 Pytorch에서 klue/Roberta-large-Model을 Fine-tuning하여 개발함. Weight & Bias 플랫폼에서 Bayesian Search를 사용하여 + Hyperparameter search를 수행.  19개의 참가조 중 최종 6등을함.  baseline-model의 error를 50% 임 .
+ Github [링크](https://github.com/woongjoonchoi/klue-level2-nlp-19) ppt [링크](https://docs.google.com/presentation/d/1_wO1XZXMfkSBaMuadQUW1wzWi2RhHFOYSWyHP9hSqds/edit#slide=id.p)

### Mask Classification (2021.08~2021.08)
+ 7명을 리드하고 , 팀 전체의 코드 리뷰를 담당하고 GIt을 통하여 프로젝트 관리  및 줌을 통하여 원격회의 진행을 함. 주도적으로 팀 전체의 코드 아키텍쳐를 통일하고 원격협업을 이끌었음.
+ Competetion에서 나이,성별,마스크 착용을 확인하는Image Classification 모델을  Pytorch에서 구현하여 , 39개의 조중 8등이라는 성과를 얻었습니다.  Python의 sequence type이 사용된 코드를 generator type로 수정하여 기존 코드의 Memory 사용량을 1/3으로 줄여서 최적화를 했습니다.
+ Github [링크](https://github.com/woongjoonchoi/BoostUP/tree/Image-Classification)

### 악플탐지 시스템 (2020.03~2020.11)
+ 무분별한 악성 댓글에 고통받는 사람들을 도와주는 LLM application을 개발. 100만개의 댓글 데이터를 크롤링하여 정규식으로 전처리하고 Bert model을 Tensorflow에서 large scale training하여 Sentiment Classifier 모델을 개발. Pretrained Huggingface model 대비 성능이 30% 증가. 담당교수님이 담당하는 3개의 팀중에서 1등을 해서 학과 최종발표회에서 발표.
+ [졸업논문링크](https://drive.google.com/file/d/1t2KwVOTKWxUdURGkJxYYvXUkF1RIUPQW/view?usp=sharing)
 
### Face Recognition & Verfication(2020.03~2020.07)
+ Tensorflow의 API를 사용하여 Object Detection Application 을 작성하여 정확도 90 %를 달성
+ Binary Classifiaction으로 Face Verification Model을 scratch부터 작성하였으나 실패. 여기서, Pretrained model의 중요성을 깨달음
+ Github링크:(https://github.com/woongjoonchoi/final-project-level3-nlp-19) ,블로그링크:(https://woongjun-warehouse.tistory.com/25)

</details>

## OCW and Mooc
개인적으로 공부한 OCW,Mooc and STEM books.

<details>
    <summary>자세히 보기</summary>  
    
## DeepLearning Specialization : 

certificate([link](https://www.coursera.org/account/accomplishments/specialization/certificate/GPNF3DE2AFAX) ) 
  
<details>
    <summary> Assignment(버튼클릭) </summary>  


1. [Optimization Assignment from scratch - Korean](https://woongjoonchoi.github.io/dls_c2/Optimization-scratch/)

   [Optimization Assignment from scratch - English](https://oongjoon.github.io/dls_c2/Optimization-scratch/)

2. [Convolution Assignment from scratch - Korean](https://woongjoonchoi.github.io/dls_c2/conv-scratch/)

   [Convolution Assignment from scratch - English](https://oongjoon.github.io/dls_c2/conv-scratch/)
   
3. [FeedForward Math derivation - korean](https://woongjoonchoi.github.io/dlarchitecture/Feed-Forward-Network/)
   
   [FeedForward Math derivation - english](https://oongjoon.github.io/dlarchitecture/FeedForward/)

 </details> 

## MIt 6.006(Introduction to Algorithm):

## Berkely CS 162 : 

## Khan Academy Statistics:

## 3b1b  Linear Algebra

## 3b1b Calculus 


</details>

## Education

<details>
    <summary>자세히 보기</summary>  

* Google ML bootcamp 2021 Aug - 2021 Dec
* Naver Boostcamp AI tech 2021 AUg - 2022 Jan
* Computer Science(B.S.) ,KoreaAeroSpace univ   2015-2021


<!--
**woongjoonchoi/woongjoonchoi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
