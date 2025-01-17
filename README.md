# 2021-1-CECD3-KimLeeHongCho-6



## 1. 프로젝트 명
비대면 환경에서의 효과적인 교육 및 비즈니스를 위한 개인 맞춤형 융합 콘텐츠 생성 기반 기술



## 2. 프로젝트 개요
비대면 환경에서의 소통의 핵심은 영상이고, 영상을 중심으로 협업/교육/비즈니스/채팅 분야와 결합이 이루어지고 있다. 영상과 결합될 수 있는 다양한 정보를 시간, 즉 러닝타임으로 매칭시키려고 하며, 그때 가장 적절한 기반 기술이 자막이라고 생각된다. 그 중에서 교육 분야에 중점을 두고, 사용자가 비대면 환경에서 효과적으로 학습을 수행할 수 있는 교육 환경 조성을 위해 개인 맞춤형 자막 에디터, HTML 플레이어에서의 오버레이 자막 뷰어를 개발하고자 한다.



## 3. 프로젝트 목표
1. 사용자가 자막을 관리할 수 있는 통합적인 기능
   - 자막 생성, 수정, 삭제, 저장
2. 실시간 및 로컬 영상의 자동 자막 생성
   - 음성인식 엔진 사용
3. 영상에 참고할 수 있는 파일의 자막화
   - ODF 형식의 파일 사용
4. 생성된/저장된 자막에서 원하는 키워드 검색
5. 자막 클릭 시 매칭 되는 영상 부분을 재생



## 4. 시스템 구성도
![시스템구성도](https://user-images.githubusercontent.com/43579755/122647084-703ad680-d15d-11eb-94bb-a93360878478.PNG)



## 5. 실행방법
로컬 서버를 구동하여 실행이 가능함
   1) npm 설치
      - https://nodejs.org/en/
```
git clone https://github.com/CSID-DGU/2021-1-CECD3-KimLeeHongCho-6.git

cd 2021-1-CECD3-KimLeeHongCho-6

npm install

npm start
```



## 6. 진행상황

- 웹 구현
1) 실행 시 첫 화면
![1](https://user-images.githubusercontent.com/43579755/122676098-62498c00-d217-11eb-8605-8b367ac19337.PNG)


2) 사용자가 로컬 저장소에서 동영상 파일과 자막 파일 불러오기 가능
![2](https://user-images.githubusercontent.com/43579755/122676111-6ecde480-d217-11eb-8565-7f5fe3c1b052.PNG)


3) 동영상이 재생됨에 따라 해당되는 부분의 자막이 녹색으로 표시됨
![3](https://user-images.githubusercontent.com/43579755/122676135-8b6a1c80-d217-11eb-8806-98a84ff41e3c.gif)


4) 선택한 자막(문장)에 해당하는 부분부터 동영상 재생 가능
![4](https://user-images.githubusercontent.com/43579755/122699747-f56cdb00-d284-11eb-9e88-51d31827e968.gif)


- 음성 인식 자막 파일 생성

1) 웹 표준 자막 파일 형식 vtt 자막 생성

![image](https://user-images.githubusercontent.com/62579567/122773103-02201c00-d2e3-11eb-99d8-6d47d1e8b0d7.png)

순서, 타임 라인, 화자 인식 및 자막 텍스트까지 출력 (vtt 자막 형식)

2) 자막 파일 실행 결과

![image](https://user-images.githubusercontent.com/62579567/122773441-53301000-d2e3-11eb-81a0-d92cc5ae873a.png)

## 7. 팀원
김윤호

이유경

조민지 (팀장)

홍은주
