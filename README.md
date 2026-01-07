# README.md 생성
cat > README.md << 'EOF'
# 🚦 YOLOv8 도로 표지판 탐지 프로젝트

## 프로젝트 개요
YOLOv8을 활용한 도로 표지판 객체 탐지 프로젝트

## 데이터셋
- Kaggle Road Sign Detection Dataset
- 클래스: crosswalk, speedlimit, stop, trafficlight

## 프로젝트 구조
- training_results/: 학습 결과
- detection_results/: 탐지 결과  
- data.yaml: 데이터셋 설정

## 실행 환경
- Google Colab (T4 GPU)
- YOLOv8n
EOF
