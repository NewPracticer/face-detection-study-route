# Fac-Mask-In-Different-Solution

### 四种解决方案 
1. 使用现成的第三方，https://github.com/AIZOOTech/FaceMaskDetection，准确率为90%
2. 使用yolov5，配合767张训练图片，61张验证图片，准确率在92%左右
3. 使用cnn，配合使用3725张戴口罩图片，3828未带口罩图片，准确率在98%
4. 使用MobileNetV2，配合4095图片，2165戴口罩，1930未带口罩，准确率在98%

### 下一步迭代
1. 从速度上，使用yolov6-2.0或yolov7(从美团公开的数据显示v6比v7更有优势)
2. 从准确率上，使用使用MobileNetV3
