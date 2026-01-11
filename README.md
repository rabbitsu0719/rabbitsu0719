<!-- =======================
  rabbitsu0719 Profile README
  vibe: 밝고 깔끔 + 카드형 섹션
======================= -->

<h2 align="center">안녕하세요 👋 김수현입니다</h2>

<p align="center">
  🌿 <b>클라우드 환경에서 안정성과 확장성을 설계하는 백엔드·클라우드 엔지니어 지망생</b><br/>
  Backend / API Engineer · FastAPI · Security-oriented
</p>

<p align="center">
  <a href="mailto:rabbit-su@naver.com">📧 Email</a> ·
  <a href="https://chivalrous-case-1ba.notion.site/2e17891c1f5c807b974ffd45201170dd">📘 Portfolio</a> ·
  <a href="https://github.com/t-curity">🛡️ T:CURITY</a>
</p>

<br/>

---
## 🎓 Education
| 기간 | 소속 | 내용 |
|---|---|---|
| 2018.03&nbsp;~&nbsp;2023.02 | 전남대학교 | 전자통신공학부 수료 |
| 2025.08&nbsp;~&nbsp;2026.02 | 스나이퍼팩토리 × 카카오클라우드 | 카카오클라우드로 배우는 AIaaS 마스터 클래스 2기 수료 |
---
## 💼 Experience

### 스나이퍼팩토리 × 카카오클라우드 AIaaS 마스터 클래스 2기  
**교육생** (2025.08&nbsp;~&nbsp;2026.02)

- 카카오클라우드 기반 AI·클라우드 서비스 개발 실습
- FastAPI 기반 백엔드 API 및 클라우드 아키텍처 설계
- AI 모델 연동, 보안·인증(CAPTCHA) 서비스 팀 프로젝트 수행
- GPU 서버 활용 ML 추론 및 서비스 배포 경험
---
## 📁 Past Projects

### 🏗️ 교육 프로젝트

#### 🔐 T-CURITY : 2-Phase 행동·인지 기반 CAPTCHA 시스템 (2025)
> 고트래픽 환경에서 매크로·자동화 공격을 차단하기 위한 행동 + 인지 결합형 인증 시스템

**주요 기능**
- **Phase A (행동 기반 검증)**
  - OpenCV 기반 절취선(Ticket Slice) 문제를 요청마다 동적 생성
  - 드래그 좌표 시계열 데이터를 수집하여 속도·가속도·떨림 등 30+ 행동 특징 추출
  - Isolation Forest 기반 이상 탐지로 기계적 매크로 입력 1차 차단

- **Phase B (인지 기반 검증)**
  - 3×3 이미지 그리드에서 정답 이미지를 순서대로 선택하는 인지 과제 제공
  - EfficientNet 기반 이미지 분류 + Random Forest 행동 분석 앙상블 검증
  - 반복 실패 시 이미지 노이즈를 점진적으로 강화하는 동적 난이도 조절

- **보안·아키텍처 설계**
  - Server-Driven Flow 기반 세션 상태(FSM) 관리로 단계 우회 방지
  - Blind Error Policy 적용으로 실패 원인 노출 차단
  - Base64 인라인 이미지 전송으로 크롤링·정답 DB 구축 공격 방어
  - In-Memory 세션 관리(TTL)로 고트래픽 환경에서도 저지연 처리

**Tech Stack**  
`Python` `FastAPI` `OpenCV` `Isolation Forest` `EfficientNet` `Random Forest` `ONNX Runtime` `Kakao Cloud` `Docker`

---

### 🎓 학부 프로젝트

#### 🔥 스마트 화재 경보기 (2022.03&nbsp;~&nbsp;2022.07)
> 실시간 센서 데이터 기반 화재 감지 및 스마트폰 알림 연동 IoT 화재 대응 시스템

**주요 기능**
- 열화상 카메라와 일산화탄소(CO) 센서를 활용한 화재 감지 시스템 구축
- 화재 발생 시 부저·LED를 통한 즉각적인 현장 경고 제공
- 스마트폰 앱 연동으로 실시간 화재 알림 전송
- 센서 데이터 통합 처리 및 안정적인 하드웨어–소프트웨어 연동 구현

**Tech Stack**  
`Raspberry Pi` `Python` `IoT Sensors` `OpenCV` `REST API`

---

#### 😷 스마트 마스크 보관함 (2021.09&nbsp;~&nbsp;2021.12)
> 비접촉 방식의 얼굴 인식 기반 마스크 제공 및 IoT 연동 스마트 보관 시스템

**주요 기능**
- 딥러닝(ResNet50, MobileNetV2) 기반 얼굴 인식을 통한 사용자 접근 제어
- 마스크 미착용 시 보관함 자동 개방으로 비접촉 마스크 제공
- 스마트폰 앱과 연동하여 마스크 재고 및 날씨 정보 확인 기능 구현
- 보관함 문 개방 시 내부 램프 자동 제어 등 시스템 안정성 개선

**Tech Stack**  
`Raspberry Pi` `Python` `OpenCV` `TensorFlow` `Deep Learning` `IoT`

---

#### 🚗 자율주행 자동차 제작 (2021.09&nbsp;~&nbsp;2021.12)
> 카메라 영상과 조이스틱 입력값을 학습하여 자율주행하는 RC카 개발

**주요 기능**
- TensorFlow 기반 이미지-조향값 학습 모델 구현
- Autodesk Fusion 360을 활용한 차체 외관 직접 설계 및 3D 프린팅 제작
- 카메라 영상 실시간 처리 및 모터 제어

**Tech Stack**  
`Raspberry Pi` `Python` `TensorFlow` `OpenCV` `Fusion 360` `3D Printing`

---
