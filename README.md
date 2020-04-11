# Colab

## Mnist

老Mnist了

1.[基础教学](/mnist_tf2_test.ipynb)

2.[加载模型并继续训练](/reuse_net.ipynb)

## Yolo-v3

经典

主体由[tf2.0版yolov3](https://github.com/zzh8829/yolov3-tf2)给出。

1.[作者提供的colab版本---修改版](/yolov3_colab_gpu.ipynb)
* 包含由voc数据集的raw格式转换为tfrecord格式数据集的方法  

2.[单张图像识别---yolo官方权重](yolov3_detector.ipynb)
* 包含权重的转换方法  

3.[训练流程分解](/yolov3_train.ipynb)
* 包含数据集的处理  

## Msk_RCNN

[项目地址](
https://github.com/matterport/Mask_RCNN)， [tf2.0兼容版地址](https://github.com/matterport/Mask_RCNN/pull/1896)， [tf2.1兼容补丁](https://blog.csdn.net/qq_22520587/article/details/104823338)  

### shapes

圆形、矩形、三角形三种形状的实例分割。
[colab兼容版训练脚本](/train_shapes_colab.ipynb)

### balloon

气球数据集上的训练脚本[colab_balloon_train](/train_balloon_colab.ipynb)

### balloon


