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

## 🚀 Usage

The dataset is available for download from [ModelScope](https://modelscope.cn/datasets/os_ai/Youku_Dense_Caption/).

### 📦 Method 1: Using ModelScope SDK

First, authenticate with your SDK token:
```python
from modelscope.hub.api import HubApi

api = HubApi()
api.login('your_sdk_token')  # Get token from: https://modelscope.cn/my/myaccesstoken
```

#### Download Options:

**Full Dataset:**
```python
from modelscope.msdatasets import MsDataset

ds = MsDataset.load('os_ai/Youku_Dense_Caption')
```

**Specific Split:**
```python
from modelscope.msdatasets import MsDataset

ds = MsDataset.load('os_ai/Youku_Dense_Caption', split='Culture')
```

### 📥 Method 2: Using Git LFS

```bash
git lfs install
git clone https://oauth2:your_git_token@www.modelscope.cn/datasets/os_ai/Youku_Dense_Caption.git
```
> 🔑 Get your git token from: https://modelscope.cn/my/myaccesstoken

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
