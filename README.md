# README.md
# 🚦 YOLOv8 Road Sign Detection Project

![Python](https://img.shields.io/badge/Python-3.10-blue)
![YOLOv8](https://img.shields.io/badge/Model-YOLOv8n-green)
![GPU](https://img.shields.io/badge/Environment-T4_GPU-orange)

## 📝 프로젝트 개요
Google Colab 환경에서 **YOLOv8**을 이용하여 도로 위의 주요 표지판을 실시간으로 탐지하는 모델을 학습시킨 프로젝트입니다. 딥러닝을 활용한 객체 탐지(Object Detection)의 전 과정을 포함합니다.
<img src="<img width="981" height="751" alt="스크린샷 2026-01-08 오전 12 18 58" src="https://github.com/user-attachments/assets/b7871c68-8c2b-4ae6-a74e-11c334231631" />

---

## 📊 데이터셋 정보
* **Source:** [Kaggle Road Sign Detection Dataset](https://www.kaggle.com/datasets/andrewmvd/road-sign-detection)
* **Target Classes (4):**
    * 🚶 **Crosswalk** (횡단보도)
    * 🛑 **Stop** (정지)
    * 🔢 **Speed Limit** (속도 제한)
    * 🚥 **Traffic Light** (신호등)

---

## 🛠️ 기술 스택 및 환경
* **Language:** Python
* **Framework:** Ultralytics (YOLOv8)
* **Hardware:** Google Colab T4 GPU
* **Dataset Format:** YOLO v8 format (YAML)

---

## 📂 프로젝트 구조
```text
.
├── YOLOv8_RoadSign.ipynb  # 메인 학습 및 추론 코드
├── data.yaml              # 데이터셋 경로 및 클래스 설정
├── runs/                  # 학습 결과 (Weight, Matrix 등)
└── README.md              # 프로젝트 설명
