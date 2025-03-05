# AI 딥러닝 폐초음파 영상 분류 LSTM 2D 모델
preprocessin(1)~(4)는 폐초음파 영상을 전처리하는 과정입니다.
Labeling, 테스트 데이터 분류, Vidoe to Image(Capturing), Noise Masking, Data Augmentation 등의 작업을 포함합니다,

main_model은 convlstm2d 모델의 입력층과 출력층을 파인-튜닝 후 추가학습하고 Weight Prunning을 통해 경량화 후 F1 scroe로 평과하는 과정입니다.
