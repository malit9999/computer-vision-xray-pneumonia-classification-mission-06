# Chest X-Ray Pneumonia Classification

> **Bootcamp Mission 06** | Computer Vision

## 미션 소개
흉부 X-Ray 이미지를 바탕으로 폐렴 여부를 분류하는 컴퓨터 비전 미션입니다. 의료 영상 분류의 기본 파이프라인을 따라 데이터 준비, 모델 학습, 예측 결과 확인을 수행합니다.

## 구현 목표
- 이미지 분류 데이터의 구조를 이해한다.
- X-Ray 이미지 분류 모델의 학습 흐름을 구현한다.
- 분류 결과를 통해 모델의 한계와 주의점을 인식한다.

## 주요 구현 내용
- X-Ray 이미지 전처리
- 폐렴 여부 이진 분류
- 학습 및 예측 결과 확인

## 사용 기술
- Python
- Deep Learning
- Computer Vision
- Jupyter Notebook

## 실행 방법
```bash
pip install -r requirements.txt
jupyter notebook notebooks/mission06.ipynb
```

> 데이터셋 또는 사전학습 모델이 외부에서 제공되는 경우, 실행 전에 노트북 또는 코드의 데이터 로드 설정을 확인해야 합니다.

## 폴더 구조
```text
notebooks/
  mission06.ipynb
README.md
requirements.txt
.gitignore
```

## 학습 내용
- 의료 이미지 결과는 학습용 실습 결과이며 실제 진단 도구로 사용할 수 없다는 점
- 클래스 불균형과 데이터 품질이 모델 해석에 중요하다는 점

## 트러블슈팅 및 재현 시 참고 사항
이미지 경로와 실행 출력에 남은 로컬 환경 정보는 배포 환경에 맞춰 별도로 정리할 수 있습니다.

## 결과 확인
학습 과정과 분류 결과는 노트북에서 확인할 수 있습니다.

## 포트폴리오 관점
이 저장소는 **Computer Vision** 역량을 학습·실험한 결과물입니다. 구현 범위와 실행 조건은 코드 및 노트북을 기준으로 확인할 수 있습니다.