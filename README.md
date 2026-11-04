# DM0016 · Camera Movement Video Samples / 运镜视频样例

**Dataset card / 数据集卡片** · Zovda sample dataset. This repository is the GitHub mirror of the card; the data files are hosted on Hugging Face — **[download the dataset / 下载数据集](https://huggingface.co/datasets/Zovda/dm0016-camera-movement-video-samples)**.

本仓库是数据集卡片的 GitHub 镜像，数据文件托管在 Hugging Face，**[点击下载 / download](https://huggingface.co/datasets/Zovda/dm0016-camera-movement-video-samples)**。

| Item / 项目 | Value / 值 |
|---|---|
| Dataset ID / 数据集编号 | DM0016 |
| Files / 数据文件 | 3 |
| Size / 数据体积 | 206.97 MB |
| Language / 语言 | en |
| Tasks / 任务类别 | video-classification |
| Hugging Face / 数据地址 | [dm0016-camera-movement-video-samples](https://huggingface.co/datasets/Zovda/dm0016-camera-movement-video-samples) |
| Provided by / 提供方 | Zovda |
| Contact / 联系邮箱 | lucas@zovda.com |

## Overview / 简介

4K live-action samples grouped by camera motion — FPV drone and aerial top-down/orbit — all 3840×2160 at 50–60 fps, for camera-control training of video generation models.

按穿越机（FPV）、航拍俯视/环绕两类摄影机运动方式组织的 4K 实拍样例，全部 3840×2160、50–60fps，面向视频生成的运镜控制训练。

## What's inside / 数据内容

- FPV: `d23175664_FPV街道穿越.mp4`.
- 穿越机：`d23175664_FPV街道穿越.mp4`。
- Aerial top-down / orbit: `d23164222_港口航拍.mp4` and `d21493132_城市河流航拍.mp4`.
- 航拍俯视 / 环绕：`d23164222_港口航拍.mp4`、`d21493132_城市河流航拍.mp4`。

## Specifications / 规格

- Resolution: 3840×2160 (4K), H.264
- 分辨率：3840×2160（4K），H.264
- Frame rate: 50 / 59.94 fps; 6.8–10.0 s per clip
- 帧率：50 / 59.94 fps；单条时长 6.8–10.0 秒
- All 3 clips are silent
- 3 条均为无音轨素材

## Suitable tasks / 适用任务

- Camera-motion control training (large displacement, parallax, orbit radius, pitch)
- 运镜控制训练（大位移、视差、环绕半径、俯仰角）
- Spatial-relation understanding and motion-blur modelling
- 空间关系理解与运动模糊建模
- Controllability evaluation for video generation
- 视频生成可控性评测

## Files / 文件清单

Paths below are relative to the Hugging Face repository root. 下表路径相对于 Hugging Face 仓库根目录。

| # | File | Size |
|---|---|---|
| 1 | `stock-video-samples/d21493132_城市河流航拍.mp4` | 81.46 MB |
| 2 | `stock-video-samples/d23164222_港口航拍.mp4` | 64.90 MB |
| 3 | `stock-video-samples/d23175664_FPV街道穿越.mp4` | 60.60 MB |

## Download / 下载

The files are not stored in this repository. 数据文件不在本仓库内，请从 Hugging Face 获取。

- Dataset page / 数据集页面: https://huggingface.co/datasets/Zovda/dm0016-camera-movement-video-samples
- Direct file URL / 单文件直链: `https://huggingface.co/datasets/Zovda/dm0016-camera-movement-video-samples/resolve/main/<path from MANIFEST.csv>`

```python
from huggingface_hub import snapshot_download

snapshot_download(
    repo_id="Zovda/dm0016-camera-movement-video-samples",
    repo_type="dataset",
    local_dir="./dm0016-camera-movement-video-samples",
)
```

```python
from huggingface_hub import hf_hub_download

hf_hub_download(
    repo_id="Zovda/dm0016-camera-movement-video-samples",
    repo_type="dataset",
    filename="<path from MANIFEST.csv>",
    local_dir="./dm0016-camera-movement-video-samples",
)
```

## Rights and disclaimer / 授权与声明

Supplied by Zovda; samples demonstrate camera-motion taxonomy and specification. Contact us for commercial licensing.

素材由 Zovda 供应，样例用于展示运镜分类与规格。商用授权请联系我们。

This dataset is shared to demonstrate data organisation, technical specifications and delivery structure. For formal licensing, large-scale access or custom production, contact lucas@zovda.com.

本数据集仅用于展示数据组织方式、技术规格与交付结构。正式授权、规模化取数与定制生产请联系 lucas@zovda.com。

## About Zovda / 关于 Zovda

Zovda builds, cleans, annotates and packages training data across video, audio, images, e-commerce image-text pairs, exam question banks, embodied AI and coding-agent corpora.

Zovda 提供多模态与文本训练语料的数据采集、清洗、标注与结构化交付服务，覆盖视频、音频、图像、电商图文、K12 与职业题库、具身智能、代码智能体等方向。

**Contact / 联系方式:** lucas@zovda.com
