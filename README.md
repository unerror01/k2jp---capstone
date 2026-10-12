# 🐙 360° Omnidirectional Tendon-Driven Soft/Continuum Robot

> **와이어 구동 및 마찰 클램프를 이용한 360° 전방향 문어다리형 로봇**  
> *Embedded Systems Engineering Capstone Design Project*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino_IDE-00979D?style=flat-square&logo=arduino&logoColor=white)
![Fusion 360](https://img.shields.io/badge/Fusion_360-0696D7?style=flat-square&logo=autodesk&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 📌 Project Overview
기존의 다관절 로봇팔과 달리 유연한 연속체(Continuum) 구조를 구현하여, 좁거나 복잡한 환경에서도 전방향 유연 곡선 동작이 가능한 **문어다리형 로봇**입니다. 외부 모터 및 와이어 장력 조절을 통해 경량화된 다관절 굽힘 동작을 수행하며, 모터 과부하 및 전력 소모를 방지하기 위한 **마찰 클램프(Friction Clamp)** 메커니즘을 결합했습니다.

- **팀명:** 김이주박
- **팀원:** 박민재, 김예림, 김이경, 주상희
- **지도교수:** 황광일 교수님 (인천대학교 임베디드시스템공학과)

---

## 💡 Key Features
- **360° Omnidirectional Bending:** 다방향 와이어 장력 조합을 통한 상·하·좌·우 및 중간 방향 연속 굽힘
- **Tendon-Driven Mechanism:** 관절부 모터 배치를 배제하고 기저부 와이어 구동을 통한 초경량화
- **Friction Clamp Locking:** 목표 자세 도달 후 와이어를 물리적으로 고정하여 모터 부하 및 전력 소모 최소화
- **Embedded Control:** MCU 기반 다중 모터 드라이버 제어 및 키보드/방향 입력 연동

---

## 🛠 System Architecture
