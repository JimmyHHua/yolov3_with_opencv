1.下载或者clone文件，进入命令行运行getModels.sh 获取模型参数。
```bash
git cloen https://github.com/JimmyHHua/yolov3-with-opencv.git
cd yolov3-with-opencv
./getModels.sh
```
2.针对图片识别或者视频检测，运行相关命令如下：
```bash
# Python:
# 1. for a single image:
  python object_detection_yolo.py --image=bird.jpg

# 2. for a video file:
  python3 object_detection_yolo.py --video=wall.mp4
```
3.结果如下：
- 检测单个图片：

	![wall](demo/dog_yolo_out_py.jpg)
