# Dacon-4DBlock
## 대회 소개
주제는 2D 이미지 기반 블록 구조 추출 AI 모델 개발이며, 
2D 이미지 내 포디블록의 10가지의 블록 패턴들의 존재 여부를 분류하는 Multi-Label Classification을 수행하는 것입니다.
또한 실험 환경에서 촬영된 이미지가 학습 데이터로 주어지며, 평가(테스트 데이터)는 실제 환경에서 촬영된 이미지입니다. 

대회 링크 : https://dacon.io/competitions/official/236046/overview/description

본 경진 대회에서 사용했던 코드이며, 리더보드 결과 Accuracy: Public 0.941 Private 0.937입니다.   

## 파일 구조
1. Data Generation.ipynb : 새로운 배경을 가져와 합성하는 코드
2. Modeling.ipynb :  Data load부터 Train, Inference까지의 코드
3. Ensemble.ipynb : 최종 모델들을 불러와 Ensemble을 적용하는 코드입니다.
