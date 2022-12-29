# face-mask-detection-dataset
YOLOv5 image dataset
python train.py --batch 2 --data ../mask-detection-dataset/data/data.yaml --cfg models/yolov5x.yaml --weights "runs\train\exp\weights\best.pt" --device 0

python train.py --batch 4 --data ../mask-detection-dataset/data/data.yaml --cfg models/yolov5x.yaml --weights "" --device 0