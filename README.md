# Deep Learning from Scratch - 环境配置指南 (Environment Setup)

本项目基于 Python 3 和 Jupyter Notebook 进行《深度学习入门：基于 Python 的理论与实现》的学习。
以下是在 **VS Code + Windows Subsystem for Linux (Ubuntu)** 环境下的标准配置步骤。

## 1. 初始化虚拟环境 (Virtual Environment)

为了防止依赖冲突，建议为本项目单独创建一个虚拟环境。请在项目根目录下打开终端 (Terminal) 执行以下步骤：

### 第一步：创建环境
```bash
python3 -m venv venv
```

### 第二步：激活环境
```bash
source venv/bin/activate
```

### 第三步：安装依赖库

#### 1. 升级 pip
```bash
pip install --upgrade pip
```
#### 2. 安装核心库
##### numpy: 用于矩阵运算
##### matplotlib: 用于绘制图表和显示图像
##### ipykernel: 用于 VS Code 运行 Jupyter Notebook
```bash
pip install numpy matplotlib ipykernel
```