# DACON 음향 데이터 COVID-19 검출 AI 경진대회
<!--이미지 들어갈 자리임-->
---

## 일정 
### 2022.05.31 ~ 2022.07.08 16:59

---
## 프로젝트 목표

데이콘 입상

---
## 팀

### 팀장 : 손기훈
### 팀원 : 정현우

## 역할

### 손기훈 : 엔지니어링, 모델링
### 정현우 : 모델링

## 엔지니어링 목표

1 .도커를 활용하여 amd 지피유와 윈도우라는 환경을 극복
  - ubuntu 와 ROCm 이미지 사용 예정

2. I/O 작업 시간 단축
  - 총 데이터량은 대략 12GB, 따라서 훈련과 별개로 I/O 작업 시에 많은 시간이 소요될 것으로 판단하여 원격 접속(ssh) 가능한 디비 생성 및 데이터 업로드. 
  - 데이터를 불러올 시 시간 단축을 위하여, 멀티 프로세싱 혹은 디비 내부의 병렬 처리 기능을 사용하여 업로드.  

### 사용 기술 스택
docker, mongoDB, python

## 모델링 목표

macro f1-score 의 값이 90 이상을 넘는 것을 목표로 한다.

- 사용할 방법론
  1. 음성 -> 이미지 -> cnn
  2. 음성 -> rnn
  3. 음성 -> 트랜스포머 
  4. 음성 -> DBN


### 사용 기술 스택
pytorch, opencv, scikit-learn, scipy, matplotlib, pandas, numpy etc
  

위의 네가지 방법론을 모두 적용할 수 있길 기대하고 네 모델 중 가장 성능이 좋은 모델 하나를 선택할 예정.

## 세부 일정



