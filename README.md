# Siemens NX 西门子产线模型库 (Production Line - NX)

本项目包含完整的产线 3D 模型文件（.prt / .stp），主要用于打那个狗屎比赛
# 模型预览

![产线模型整体预览图](./images/preview_main.png)

文件说明

仓库内的 `产线-NX` 文件夹包含以下格式的文件：
- **.prt**: Siemens NX 原生零件文件
- **.stp**: 通用 STEP 格式，兼容 SolidWorks, CATIA 等软件

## 如何获取文件

### 方式一：直接下载（推荐非开发者使用）
如果你不需要 Git 版本控制，只想下载模型文件：
1. 点击页面右侧的 **Releases** 区域。
2. 下载最新的 `.zip` 压缩包（例如 `Siemens-NX-Models-v1.0.zip`）。
3. 解压后即可直接使用。

👉 **[点击这里跳转到下载页]([https://github.com/chexling/Siemens-/releases](https://github.com/checling/Siemens-/releases/tag/v1.0))**

### 方式二：使用 Git 克隆（推荐开发者/协作者）
如果你需要跟随版本更新，请使用 Git LFS 克隆：

```bash
# 1. 确保已安装 Git LFS
git lfs install

# 2. 克隆仓库
git clone https://github.com/chexling/Siemens-.git
