# AutoEmbed-AI 🚀  
> AI-Powered Co-Design Framework for Fully Autonomous Embedded Systems  

![System Architecture](A_flowchart_in_a_digital_vector_graphic_illustrate.png)

---

## 📌 소개

**AutoEmbed-AI**는 사용자의 요구사항만 입력하면,
AI가 자동으로 하드웨어(MCU)와 소프트웨어(드라이버, 제어 로직, RTOS 등)를 선택하여  
완전한 임베디드 시스템 설계를 **자동 생성**해주는 시스템입니다.

더 이상 직접 C코드 짜고, RTOS 세팅하고, 센서 드라이버 연결하지 않아도 됩니다.

---

## ⚙️ 주요 기능

- 자연어 요구사항 → 자동 분석
- AI 기반 하드웨어 선택 (예: ESP32, DHT22 등)
- C++ 코드 자동 생성 (센서 제어, 제어 로직)
- PlatformIO 프로젝트 자동 구성
- 실시간 운영 가능한 펌웨어 생성

---

## 🧠 사용 예시

### 🗣️ 사용자 입력  
> "온도 센서를 이용해서 특정 온도 이상일 때 팬을 켜는 시스템"

### 🔧 생성 결과  
- MCU: ESP32  
- 센서: DHT22  
- 출력: 팬 제어  
- 온도 기준: 30°C  
- 자동 생성된 코드 → `src/main.cpp`

---

## 🧪 시스템 구조도

![Architecture](A_flowchart_in_a_digital_vector_graphic_illustrate.png)

---

## 📁 포함된 파일

| 파일 | 설명 |
|------|------|
| `autoembed_ai_builder.py` | 시스템 자동 설계기 (Python) |
| `AutoEmbedAI_Full_Summary_Paper.docx` | 논문 문서 |
| `A_flowchart_in_a_digital_vector_graphic_illustrate.png` | 시스템 구조도 |

---

## 🛠️ 향후 계획

- 다양한 센서/출력 장치 지원 확대
- GPT 연동한 자연어 코드 생성
- 웹 UI 개발 (Flask 기반)
- TinyML 자동 학습 및 삽입

---

## 🙌 만든 사람

**Gyeongjin0123**  
> 프로젝트에 공감하셨다면 ⭐️ Star 부탁드립니다!

---
