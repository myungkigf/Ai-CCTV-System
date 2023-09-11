# Ai-CCTV-System

인공지능을 이용한 CCTV 시스템의 소개이다.

# 🛠 개발 도구
* **Jupyter Notebook**
# 📚 라이브러리 및 버전
* **Keras**: 2.13.0
* **TensorFlow**: 2.13.0
* **OpenCV**: 4.8.0
* **NumPy**: 1.24.3
* **h5py**: 3.9.0

# 💻 사용 언어
* **Python**

# 기능 및 특징
1. 초음파 센서를 이용하여 거리가 15cm이상이면 직진을 15cm미만이면 좌회전을 하도록 모터 제어를 설정하였다.
2. 딥러닝을 이용하여 이미지 인식결과:

2-1. 초기 상태

![초기 이미지](https://i.postimg.cc/XNck8Wg4/3.png) <img src="https://github.githubassets.com/images/icons/emoji/unicode/27a1.png?v8" width="50" height="50">
![초기 LED 이미지](https://i.postimg.cc/63SqVy1Y/7.jpg)
* 카메라에 인식된 이미지가 불이면 웹캠에 fire및 백분율 표시,빨간색 LED가 출력
  
![화재 이미지](https://i.postimg.cc/ZRMtsQ3L/0.png) <img src="https://github.githubassets.com/images/icons/emoji/unicode/27a1.png?v8" width="50" height="50">
![화재 LED 이미지](https://i.postimg.cc/fRDz96v3/4.jpg)
