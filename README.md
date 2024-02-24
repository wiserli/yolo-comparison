# yolo-comparison

# notebooks
[YOLOv8 Starter Guide](https://github.com/wiserli/notebooks/blob/main/notebooks/YOLOV8starterGuide.ipynb) | <a target="_blank" href="">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

```bash
git clone https://github.com/wiserli/yolo-comparison.git
cd yolo-comparison/
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
