# Youku Dense Caption Dataset 🎥

<div align="center">

![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-blue.svg)
![Videos](https://img.shields.io/badge/Videos-31.4K-green)
![Captions](https://img.shields.io/badge/Captions-311.9K-orange)
![Language](https://img.shields.io/badge/Language-Chinese-red)

</div>

## 📊 Dataset Overview

A comprehensive collection of Chinese video captions from Youku (优酷), featuring:

- **📹 Videos**: 31,466 complete short videos
- **✍️ Captions**: 311,921 Chinese captions
- **🈺 Language**: Chinese
- **📱 Source**: Youku Platform (优酷)

<div align="center">
   <img src="overview.png" width="80%">
</div>

## 🚀 Usage

The dataset is available for download from [ModelScope](https://modelscope.cn/datasets/os_ai/Youku_Dense_Caption/).

### 1. Dataset Download ⬇️
```bash
# Install Git LFS
git lfs install

# Clone the dataset
git lfs clone https://oauth2:your_git_token@www.modelscope.cn/datasets/os_ai/Youku_Dense_Caption.git
```
> 🔑 **Get Token**: Visit https://modelscope.cn/my/myaccesstoken

### 2. Dataset Structure 📁

```
📦 ROOT
├── 📁 benchmark_files/
│   ├── 📊 generation.json     # Test set for caption generation
│   └── 📊 grounding.json      # Test set for video moment retrieval
│
├── 📁 meta_files/
│   ├── 📋 Agriculture.csv     # Video file paths and Complete captions in the agriculture category
│   ├── 📋 Children.csv
|   └── 📋 [Other Categories].csv
│
└── 📁 data_files/
    ├── 📁 Agriculture/         # Agriculture videos
    │   ├── 📦 train/           # Training set (zipped)
    │   ├── 📦 val/             # Validation set (zipped)
    │   └── 📁 test/            # Test set (preview ready)
    │
    ├── 📁 Children/            # Children videos
    │   ├── 📦 train/
    │   ├── 📦 val/
    │   └── 📁 test/
    │
    └── 📁 [Other Categories]/  # Other categories
        ├── 📦 train/
        ├── 📦 val/
        └── 📁 test/
```

### 3. Usage Guide 📖

1. **After Download**:
   - Navigate to target category folder
   - Example: `cd data_files/Agriculture`

2. **Data Preparation**:
   - Unzip files in train/ and val/ directories
   - Files in test/ directory are ready to use

> ⚠️ **Important Notes**:
> - train and val data are stored in compressed format, requiring extraction
> - test data is directly accessible for preview and testing

---
💡 For questions, please refer to project documentation or submit an Issue

## 📚 Citation

If you use this dataset in your research, please cite:

```bibtex
@inproceedings{xiong2025youku,
    title={Youku Dense Caption: A Large-scale Chinese Video Dense Caption Dataset and Benchmarks},
    author={Zixuan Xiong, Guangwei Xu, Wenkai Zhang, Yuan Miao, Xuan Wu, LinHai, Ruijie Guo, Hai-Tao Zheng},
    booktitle={The Thirteenth International Conference on Learning Representations},
    year={2025},
    url={https://openreview.net/forum?id=vvi5OjPhbu}
}
```

## 📄 License

This dataset is released under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.

---
<div align="center">
⭐ Star us on GitHub if you find this dataset useful! ⭐
</div>
