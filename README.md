# 環境安裝指引

本專案使用 Conda 建立 Python 環境，並安裝必要的套件與 Gymnasium 環境。

## 安裝步驟

建立 Conda 環境（Python 3.10）
```bash
conda create -n your_env_name python==3.10 --yes
```
啟動環境
```bash
conda activate your_env_name
```
安裝 Numpy
```bash
pip install numpy==1.24.4
```
#安裝 Gymnasium 及所需環境
例如安裝 mujoco 環境
```bash
pip install gymnasium[mujoco]
```
或者安裝 classic-control 環境
```bash
pip install gymnasium[classic-control]
```
執行範例程式碼
```bash
python example_code.py
```
