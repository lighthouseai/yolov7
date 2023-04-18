python train.py --workers 8 --device 0 --batch-size 8 --data data/knit.yaml --img 640 640 --cfg cfg/training/knit-tiny.yaml --weights ./weights/yolov7_training.pt --name knit --hyp data/hyp.scratch.custom.yaml

Inference Command:-
python detect_sort.py --weights ./runs/train/knit34/weights/best.pt --conf 0.1 --img-size 640 --source /media/countai/1d2ee9ae-62a6-48ad-9b54-37961c190083/2023-04-12/cam1/