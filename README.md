# Humpback-Whale-Identification-Challenge
#### link: https://www.kaggle.com/competitions/whale-categorization-playground/overview
- 2023 영상처리와딥러닝 기말프로젝트
- Metric Learning
- 최종: 1위/29명

## Dataset Description
이 데이터셋은 혹등고래 꼬리의 이미지를 포함하고 있습니다. 각 개별 고래는 연구자들에 의해 식별되었고, 고유한 Id가 부여되었습니다. 목표는 테스트 세트의 이미지에 대한 고래 Id를 예측하는 것입니다.
3,000개 이상의 고래 Id 중에서 **각 Id에 대한 예제가 몇 개 안 되는 것이 큰 도전 과제**입니다.

## File Descriptions
- train.zip: Train 이미지 포함
- train.csv: 각 훈련 이미지를 해당 고래 Id에 매핑하며, train 데이터에서 식별되지 않은 고래는 new_whale로 표시되어야 함.
- test.zip: 고래 Id를 예측해야 하는 test 이미지 포함
- sample_submission.csv: 예측 제출 시 올바른 형식을 제공하는 샘플 제출 파일
