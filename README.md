## 车牌检测和识别


**环境要求: python >=3.6  pytorch >=1.7**

#### **图片测试:**

直接运行detect_plate.py 或者运行如下命令行：

```
python detect_plate.py --detect_model weights/plate_detect.pt  --rec_model weights/plate_rec_color.pth --image_path images --output result
```

#### **视频测试:**
```
python detect_plate.py --detect_model weights/plate_detect.pt  --rec_model weights/plate_rec_color.pth --video test.mp4
```

视频文件为test.mp4  保存为result.mp4

## **车牌检测训练**

车牌检测训练链接如下：

[车牌检测训练](./readme/README.md)

## **车牌识别训练**

车牌识别训练链接如下：

[车牌识别训练](https://github.com/edgehook/license_plate_recognition.git)

