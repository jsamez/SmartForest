# Smart Forest - All-in-One Pet & Plant Management Platform

## 📖 Introduction
Smart Forest는 현대인들의 바쁜 일상 속에서 애완동물과 식물의 관리에 대한 어려움을 해결하기 위해 설계된 올인원 플랫폼입니다.
이 시스템은 사용자의 편의성을 극대화하고, 관리의 용이성을 제공하며, 사용자 간 정보 교환과 전문가의 조언을 통해 올바른 관리 방법을 제공합니다.

## 🎯 Project Goals
- 애완동물 및 식물의 관리 자동화
- 사용자 친화적인 GUI 및 관리 시스템 제공
- 정보 교환 및 커뮤니티 플랫폼 구축

## 🛠️ Technologies
- **OS:** Windows 11 23H2
- **Programming Language:** Python 3.12.5
- **Frameworks & Libraries:**
  - OpenCV 4.10.0
  - YOLOv5 (Object Detection)
  - PySide6 (GUI Development)
  - Qt 6.7

## 🏗️ System Architecture
### 1. **Input**
   - 비디오 또는 이미지 데이터를 GUI를 통해 입력받음
### 2. **Processing**
   - Object Detection: YOLO 모델을 사용하여 객체 인식 및 위치 추출
   - Velocity & Distance Calculation: 객체 이동 속도 및 거리 계산
   - Behavior Analysis: 사용자 행동 분석 및 처리
### 3. **Output**
   - 결과 데이터를 GUI에 표시
   - 영상 및 이미지를 처리 후 저장

## 🖥️ GUI Layout
- **Video Controls:**
  - `Start Video`: 영상 재생
  - `Pause Video`: 영상 일시정지
  - `Stop Video`: 영상 정지
- **File Selection:**
  - QFileDialog를 사용하여 로컬 파일 선택
- **Output Display:**
  - QLabel 및 QPixmap을 이용하여 결과 영상 및 정보를 시각적으로 출력

## 🔍 Features
- Signal-Slot 구조를 통한 이벤트 기반 GUI 구현
- OpenCV와 PySide6를 활용한 비디오 처리 및 이미지 출력
- Qt Layout 관리로 사용자 친화적인 인터페이스 제공
- 객체 탐지 및 행동 분석 결과를 실시간으로 표시

## 🚀 Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repository/SmartForest.git
   cd SmartForest
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python main.py
   ```

## 🤔 Challenges
- PyQt Signal-Slot의 개념 이해 및 적용
- 다양한 라이브러리 모듈 및 메서드 탐색 시간 소요
- PC UI와 모바일 UI 간의 통합 방안 연구

## 📈 Future Improvements
- UI 버튼을 사용자의 입력 데이터(영상/카메라 수)에 따라 동적으로 변경
- 모바일 UI 연동 방안 개발
- 객체 탐지 및 분석 모델의 성능 최적화

## 🙏 Acknowledgements
- **Team Members:** 김은찬, 박인혁, 윤태준, 장성민
- Date: 04 September, 2024

