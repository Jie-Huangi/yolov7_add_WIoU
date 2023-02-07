
# yolov7 add wiou

# 1. modification

- general.py
- loss.py

# 2. how to use 

``` shell
# my practice is train_aux
python train_aux.py --workers 8 --device 0 --batch-size 16 --data data/coco.yaml --img 1280 1280 --cfg cfg/training/yolov7-w6.yaml --weights '' --name yolov7-w6 --hyp data/hyp.scratch.p6.yaml
```

# 3. Reference

- https://github.com/Instinct323/wiou
- https://blog.csdn.net/qq_55745968/article/details/128888122
- https://blog.csdn.net/athrunsunny/article/details/128872025

