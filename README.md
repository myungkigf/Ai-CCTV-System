# PORTFOLIO

# 📗 목차
* 📝 개요
* ✏️ 사용기술
* 👨🏻‍💻프로젝트 기능 및 구현

# 📝 개요
![프로젝트 세트장 이미지](https://i.postimg.cc/Dy87n2G1/8.jpg)

프로젝트 : AI를 활용한 순찰형 CCTV 시스템

제작기간 : 2023.05 ~ 023. 09

분류 : 팀 프로젝트

참여인원 : 6명

# ✏️ 사용기술

개발도구 : jupyter notebook

사용언어 : python

사용라이브러리 : tensorflow, keras, open cv, numpy, h5py

# 👨🏻‍💻프로젝트 기능 및 구현
1. 초음파 센서를 이용하여 거리가 15cm이상이면 직진을 15cm미만이면 좌회전을 하도록 모터 제어를 설정하였다.
2. 카메라가 이미지를 인식하여 정확도가 95% 이상이면 결과를 출력하고 10초뒤 다시 움직이게 설정하였다.
3. 딥러닝을 이용하여 이미지 인식에 따른 웹캠 및 LED 결과를 표시:
* 카메라에 인식된 이미지가 정확하지 않으면 웹캠에 Low probability표시, 흰색 LED가 출력

![초기 이미지](https://i.postimg.cc/CLJ2mtx5/3.png) <img src="https://github.githubassets.com/images/icons/emoji/unicode/27a1.png?v8" width="150" height="150">
![흰색 LED 이미지](https://i.postimg.cc/YSFbKyM1/7.jpg)
* 카메라에 인식된 이미지가 불이면 웹캠에 fire및 백분율 표시, 빨간색 LED가 출력
  
![화재 이미지](https://i.postimg.cc/W1JB98Fk/0.png) <img src="https://github.githubassets.com/images/icons/emoji/unicode/27a1.png?v8" width="150" height="150">
![빨간색 LED 이미지](https://i.postimg.cc/Qx5LmSWW/4.jpg)

* 카메라에 인식된 이미지가 사람이면 웹캠에 human및 백분율 표시, 초록색 LED가 출력
  
![사람 이미지](https://i.postimg.cc/MGz0frqb/1.png) <img src="https://github.githubassets.com/images/icons/emoji/unicode/27a1.png?v8" width="150" height="150">
![초록색 LED 이미지](https://i.postimg.cc/mgvywNCh/5.jpg)


* 카메라에 인식된 이미지가 누수이면 웹캠에 water및 백분율 표시, 파란색 LED가 출력
  
![누수 이미지](https://i.postimg.cc/DfxQDKL9/2.png) <img src="https://github.githubassets.com/images/icons/emoji/unicode/27a1.png?v8" width="150" height="150">
![파란색 LED 이미지](https://i.postimg.cc/J4t3CdQG/6.jpg)

