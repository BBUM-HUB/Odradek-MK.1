# ODRADEK-MK.1 [Q.E.D][MacGuffin]

> **기계의 탈을 쓴 의지**, 인류가 만든 최초의 미래  

---

## 📌 작품 개요
ODRADEK-MK.1은 주변 사람을 인식하고, 조명과 기계적 동작을 통해 경고 신호를 보내는 장치입니다.  
게임 속 주인공의 어깨 위 장비에서 영감을 받아 설계되었으며, 사람의 움직임에 반응하는 인터랙티브 기계예술 작품입니다.

---

## 🎯 Motive
- 게임 속 **주인공의 어깨 위 로봇팔**에서 착안  
- **주변 생명체를 탐색**하고, 조명으로 경고하는 기능 구현  
- 착용형 기기를 목표로 했으나, 초기에는 기능 구현에 집중

---

## ⚙️ Explain
- 카메라로 얼굴을 감지하면, 네 개의 서보모터가 연결된 팔이 자동으로 펼쳐집니다.  
- 사람과의 거리가 가까워질수록 팔이 점차 전방으로 90도까지 움직이며, LED 조명의 밝기도 함께 증가합니다.  
- 단순한 반응형 장비를 넘어, 사람과 상호작용하며 환경을 시각적으로 변환하는 장치입니다.

---

## 🧩 Hardware
- **MCU**: Raspberry Pi, Arduino Nano  
- **Servo Motor**: SG90 × 4  
- **Stepper Motor**: NEMA 17 (17HS4023)  
- **Driver**: TMC2209  
- **LED**: WS2812B Strip  
- **Camera**: 다이소 웹캠  
- **3D Modeling**: Autodesk Fusion 360  
- **필라멘트 사용량**: 약 500g

---

## 🔍 Algorithm
1. OpenCV를 통해 얼굴 인식  
2. 얼굴 크기를 기반으로 거리 계산  
3. 거리에 따라 **팔의 각도 제어** 및 **LED 밝기 조절**

---


## 📅 제작 일정
- **8월 중순**: 필라멘트, LED, 스텝모터 등 부품 구매  
- **9월 초**: 스텝모터 감속기(Cycloidal drive) 출력  
- **9월 중순**: Raspberry Pi 및 Arduino 코딩  
- **9월 말**: 최종 전시회 준비 완료  

---

## 📐 제작 정보
- **총 제작 기간**: 약 1개월  
- **제작 방식**: 3D 프린팅 및 모듈 조립  

---

## 🚀 Vision
ODRADEK은 단순한 장치가 아닌 **동반자이자 미래**입니다.  
우리는 이 장치를 통해 단순한 생존을 넘어, **우주의 주체로 거듭나는 인류**를 상상합니다.

---

## 🙏 Thanks to

- KITEL 선배님들 ( specially 47기 윤태영, 46기 김지훈, 46기 이동윤 ) 
- 포기하지 않은 나 자신
- 3D 프린터, 라즈베리 파이, 아두이노 나노
- Gpt

---

## 📚 References
이 프로젝트에서 참고하거나 활용한 자료들입니다.  

- **3D 모델링**  
  - Autodesk Fusion 360 (자체 설계)  
  - Cycloidal drive : V2 cycloidal reducer for NEMA 17 by Joshua_A on (Thingiverse: https://www.thingiverse.com/thing:6676361)
  - SG90 Mount : (https://makerworld.com/ko/models/810184-servo-mount-sg90?from=search#profileId-751385)

- **후원**
  -SMPS (46기 김지훈 )
