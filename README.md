# TensorRT for a simple segmention model

使用VOC Person Part 训练LW Refinenet ——resnet50 作为神经网络，生成onnx模型并导入c++中实现实时语义分割。

## Todo

1.实现int8推理

2.实现upsample插件层（目前使用反卷积层代替）