# 线控转向失效下的容错差动转向控制

## 资源文件描述

本资源文件以四轮轮毂电机驱动的智能电动汽车为研究对象，针对线控转向系统执行机构失效时的轨迹跟踪和横摆稳定性协同控制问题，提出了一种基于差动转向与直接横摆力矩协同的容错控制方法。该方法采用分层控制架构，具体内容如下：

1. **上层控制器**：
   - 基于模型预测控制方法求解期望前轮转角和附加横摆力矩。
   - 设计基于滑模变结构控制的前轮转角跟踪控制策略。

2. **下层控制器**：
   - 以轮胎负荷率最小化为目标，利用有效集法实现四轮转矩优化分配。

本资源文件包含模型运行后的实际效果图片，模型参考了优质论文制作，内容包括Carsim数据cpar文件、Simulink模型及MATLAB代码。

## 资源内容

- **Carsim数据cpar文件**：包含模型仿真所需的数据参数。
- **Simulink模型**：用于仿真和验证控制策略的模型。
- **MATLAB代码**：实现控制算法的代码文件。

## 使用说明

1. 下载并解压资源文件。
2. 打开Carsim软件，导入cpar文件进行数据配置。
3. 在Simulink中打开模型文件，运行仿真以验证控制策略。
4. 参考MATLAB代码，进一步理解和实现控制算法。

## 注意事项

- 确保Carsim和Simulink软件版本兼容。
- 运行仿真前，请检查模型参数设置是否正确。

通过本资源文件，您可以深入了解线控转向失效下的容错差动转向控制方法，并应用于实际的智能电动汽车控制中。

## 下载链接
[线控转向失效下的容错差动转向控制](https://pan.quark.cn/s/64d5fa5d268b) 

(备用: [备用下载](https://pan.baidu.com/s/1HwrJcWTdTMwybrL1qNDikw?pwd=1234))

## 说明

该仓库仅用于学习交流，请勿用于商业用途。
