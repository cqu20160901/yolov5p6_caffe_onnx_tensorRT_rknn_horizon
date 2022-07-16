# yolov5_nano的caffe、onnx和tensorRT部署版本

将pytorch版本的yolov5_nano转成caffe、onnx、tensorRT，用python语言对后处理进行了C++形式的重写，便于移植不同平台。

# 文件结构说明
caffe_yolov5p6：去除维度变换层的prototxt、caffeModel、测试图像、测试结果、测试demo脚本

onnx_yolov5p6：onnx模型、测试图像、测试结果、测试demo脚本

tensorRT_yolov5p6：TensorRT版本模型、测试图像、测试结果、测试demo脚本、onnx模型、onnx2tensorRT脚本(tensorRT-7.2.3.4)


# 测试结果

![image](https://github.com/cqu20160901/yolov5p6_caffe_onnx/blob/master/caffe_yolov5p6/result.jpg)
