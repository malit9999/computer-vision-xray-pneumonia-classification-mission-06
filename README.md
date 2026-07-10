# Bootcamp Mission 06 - X-Ray 폐렴 이미지 분류

## 1. 개요
흉부 X-Ray 이미지를 기반으로 폐렴 여부를 분류하는 CNN/전이학습 미션입니다.

## 2. 목표
이미지 분류 모델을 학습하고 Feature Extraction, Fine-Tuning, XAI 기법을 비교하는 것을 목표로 했습니다.

## 3. 사용 기술
- Python
- numpy
- matplotlib
- scikit-learn
- opencv-python
- Pillow
- torch
- torchvision
- kagglehub
- grad-cam

## 4. 주요 기능
- X-Ray 이미지 데이터 준비
- CNN 모델 학습
- 전이학습 및 Fine-Tuning
- Grad-CAM 기반 설명 가능성 확인

## 5. 실행 방법
```bash
pip install -r requirements.txt
jupyter notebook notebooks/mission06.ipynb
```

## 6. 주요 파일
- `notebooks/mission06.ipynb`

## 7. 폴더 구조
```text
bootcamp-mission-06
  .gitignore
  notebooks/
    mission06.ipynb
  README.md
  requirements.txt
```

## 8. 학습 내용
의료 이미지 분류에서 전처리, 모델 학습 전략, 설명 가능한 AI 기법의 활용을 학습했습니다.

## 9. 트러블슈팅
미션을 진행하며 발생한 오류와 해결 과정은 노트북 또는 보고서에 정리했습니다.

## 10. 결과 화면
결과 이미지는 노트북 출력, 보고서 또는 `images/` 폴더에서 확인할 수 있습니다.

## 11. 공개 전 확인 사항
- 제출 노트북만 포함했으며, 원본 데이터와 모델 파일은 공개 범위 확인 전 포함하지 않았습니다.
