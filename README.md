# 안유빈 | Yoobin An
경북대학교 전자공학부 · 임베디드 시스템 / 차량 SW / 비전에 관심이 있습니다.

---

## 🚗 블랙박스 영상 기반 주행상황 분석 시스템
**ACE Lab 하계 코딩캠프 해커톤 · 2026.08 · 2인 팀**
블랙박스 영상만으로 차선 이탈 위험을 판단하고 실시간 주행 상태를 안내하는 시스템
- **담당:** 차량 주행 분석 (구현·발표)
- Bird's-Eye View 변환 → YOLOv8 Segmentation 차선 검출 → 차선·차량 중심 오프셋으로 Heading 계산
- Farneback Optical Flow로 상대 움직임 추정 → 규칙 기반 3단계 위험도(HIGH / CAUTION / NORMAL) 판단
- `Python` `OpenCV` `YOLOv8-seg` `Optical Flow`

## 📖 Eye Am Reader — 시선 추적형 자동 책장 넘김 장치
**2025 한이음 드림업 · 2025.03–11 · 3인 팀**
시선만으로 종이책 페이지를 넘기는 독서대 부착형 보조기기
- **담당:** 3D 모델링, 서보모터 제어
- 서보모터·카메라 거치대 3D 모델링 및 반복 프린팅·수정
- 넘김 팔(MG90S)·고정 팔(MG946R) PWM 각도 설계, 책 너비 선형 보간·넘김 횟수 기반 두께 보정
- `Raspberry Pi 5` `ESP32` `PWM` `Wi-Fi` `3D Printing`

[![Eye Am Reader 시연 영상](https://img.youtube.com/vi/Gnrcc8VltUA/0.jpg)](https://www.youtube.com/watch?v=Gnrcc8VltUA)
🔗 [Repository](https://github.com/Yunseo-Cho/Eye-Am-Reader)

## 🅿️ 스마트 볼라드 — 번호판 인식 기반 불법주차 방지 시스템
**2024 임베디드SW경진대회 자유공모 · 2024.07–08 · 4인 팀**
등록 차량만 특수 주차구역(장애인·전기차 충전)에 진입하도록 볼라드를 자동 제어
- **담당:** 데이터베이스 구축 및 연동
- MySQL 등록 차량 테이블 설계, Python 연동(`mysql-connector-python`)
- 인식된 번호판의 등록 여부를 판정하는 비교 로직 구현 → 볼라드 하강/경고 분기 결정
- `Python` `MySQL` `OpenCV` `EasyOCR` `ESP32-CAM` `ESP8266`

[![스마트 볼라드 시연 영상](https://img.youtube.com/vi/_QFrg2LsPvQ/0.jpg)](https://youtu.be/_QFrg2LsPvQ)
🔗 [Repository](https://github.com/Yunseo-Cho/Smart-Bollard-License-Plate-Recognition)

---

## 🛠 Skills
`Python` `C/C++` `OpenCV` `YOLOv8` `MediaPipe` `MySQL` `Raspberry Pi` `ESP32` `CAN · UDS · DoIP` `AUTOSAR(기초)` `Git`
