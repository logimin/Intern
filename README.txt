1. 학습
Movon/dataset/
폴더에 학습시킬 YOLO 데이터셋 zip 업로드
YOLOv8_Train.ipynb 실행
결과는 Movon/runs/yolov8_seatbelt/weights 
폴더에 best.pt, last.pt로 저장되어 이후 재학습, 추론에 사용가능.

2. 추론
Movon/dataset/unlabeled_seatbelt
폴더에 추론할 YOLO 데이터셋 zip 업로드
YOLOv8_infer_post-processing 실행
다운로드 후 로컬 압축해제 폴더의 obj_train_data 비운 후 덮어씌우기
CVAT에 업로드, 이 때 convert 지정 x 

unlabeled_seatbelt, inference_result 비운 후 다음 추론 데이터셋 업로드 후 재실행