# Bread_Detection_YOLOv8_DeepSort_By_PyTorch

Run steps:

go to directory: \ultralytics\yolo\v8\detect\detection-1 

1-) python train.py model=yolov8s.pt data='detection-1/custom-data.yaml' epochs=50 imgsz=640

2-) python val.py model='\runs\detect\train8\weights\best.pt' data='\ultralytics\yolo\v8\detect\detection-1\custom-data.yaml'

3-) python predict_1.py model='\runs\detect\train8\weights\best.pt' source='cold-hot_bread.mp4'
python train.py model=yolov8s.pt data=detection-1/custom-data.yaml epochs=50 imgsz=640 
