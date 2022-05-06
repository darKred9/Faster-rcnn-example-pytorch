# Faster-rcnn-example-pytorch
Coco数据集+pytorch预训练模型

### 运行方法

1. 直接运行```detection.py```文件即可
2. 如果报错：RUNTIMEERROR: CUDA OUT OF MEMORY，最简单的解决方式是直接关掉Jupyter后重新启动
3. 如果报错：UserWarning: torch.meshgrid: in an upcoming release ... ，参考[这篇博客](https://ask.csdn.net/questions/7585870)：直接更改functional.py即可。
4. 原[Github](https://github.com/XiaoYuhao/detection)，原[CSDN](https://blog.csdn.net/qq_38600065/article/details/120629382)
