# compare-efficientnet-and-resnet
Compare performance of efficientnet against resnet in pytorch

# Enviroment
- AWS p3.2xlarge (V100 GPU)
- CUDA 10.1
- VOC2007 Images

Resnet models are from torchvision.

# Results
|    *Name*         |*# Params*|*Top-1 Acc.*|*GPU time?*  |*CPU time?*|
|:-----------------:|:--------:|:----------:|:-----------:|:----------|
| `efficientnet-b0` |   5.3M   |    76.3    |16.3ms       |75ms       |
| `efficientnet-b1` |   7.8M   |    78.8    |23.2ms       |111ms      |
| `efficientnet-b2` |   9.2M   |    79.8    |23.3ms       |123ms|
| `efficientnet-b3` |    12M   |    81.1    |26.4ms       |173ms|
| `efficientnet-b4` |    19M   |    82.6    |32.1ms       |295ms|
| `efficientnet-b5` |    30M   |    83.3    |40.3ms       |542ms|
| `efficientnet-b6` |    43M   |    84.0    |45.3ms       |918ms|
| `efficientnet-b7` |    66M   |    84.4    |57.3ms       |1970ms|
| `Res18`           |    ?     |    69.4    |3.8ms        |48ms|
| `Res34`           |    ?     |    73.3    |6.5ms       |85ms|
| `Res50`           |    ?     |    76.1    |9.6ms       |115ms|
| `Res101`          |    ?     |    77.3    |18.2ms      |200ms|
| `Res152`          |    ?     |    78.3    |26.9ms      |288ms|
