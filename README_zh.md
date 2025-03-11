# Kohya 图形界面中文文档

本仓库主要为 [Kohya的Stable Diffusion训练脚本](https://github.com/kohya-ss/sd-scripts) 提供基于Gradio的图形界面。通过社区贡献也支持Linux系统，macOS目前支持有限但可能在兼容环境下运行。

## 目录
- [Kohya 图形界面](#kohya-图形界面)
  - [Colab在线版](#colab在线版)
  - [安装指南](#安装指南)
    - [Windows系统](#windows系统)
      - [Windows前置要求](#windows前置要求)
      - [Windows安装步骤](#windows安装步骤)
      - [可选：CUDNN 8.9.6.50](#可选cudnn-89650)
    - [Linux/macOS系统](#linuxmacos系统)
      - [Linux前置要求](#linux前置要求)
      - [Linux安装步骤](#linux安装步骤)
  - [常见问题排查](#常见问题排查)
    - [页面文件限制](#页面文件限制)
    - [TensorFlow GPU支持](#tensorflow-gpu支持)

## Windows安装步骤
1. 安装[Python 3.10.11](https://www.python.org/ftp/python/3.10.11/python-3.10.11-amd64.exe)
   ▶️ 注意勾选"Add Python to PATH"

2. 安装[CUDA 11.8工具包](https://developer.nvidia.com/cuda-11-8-0-download-archive)

```bat
:: 克隆仓库
git clone --recursive https://github.com/bmaltais/kohya_ss.git
cd kohya_ss
:: 运行安装脚本
setup.bat
```

## 中文用户专属提示
🔧 若遇CUDA安装问题，可尝试：
1. 检查NVIDIA驱动版本
2. 使用管理员权限运行安装程序
3. 安装完成后重启系统

## 技术术语对照表
| 英文术语 | 中文翻译 |
|---------|--------|
|Gradio GUI|图形界面|
|CUDA Toolkit|CUDA工具包|
|venv|虚拟环境|