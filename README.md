# yolo-comparison

```bash
git clone https://github.com/wiserli/yolo-comparision.git
cd yolo-comparision/
```

## YOLOv9

### Install Packages

```bash
cd v9/
pip install -r requirements.txt -q
```

### Download Models

```bash
wget -q https://github.com/WongKinYiu/yolov9/releases/download/v0.1/yolov9-e.pt
```

### Inference with Pre-trained Models using YOLOv9

```bash
python detect.py --weights yolov9-e.pt --source {HOME}/data/video.mp4
```

## YOLOv8

### Install Packages

```bash
cd v8/
pip install e .
```

### Inference with Pre-trained Models using YOLOv8

```bash
yolo predict source={HOME}/data/video.mp4 model=yolov8x.pt
```
