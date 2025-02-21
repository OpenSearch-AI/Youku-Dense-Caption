# Youku Dense Caption

## Introduction

With the explosive growth of video content, video captions have emerged as a crucial tool for video comprehension, significantly enhancing the ability to understand and retrieve information from videos. However, most publicly available dense video captioning datasets are in English, resulting in a scarcity of large-scale and high-quality Chinese dense video captioning datasets.

To address this gap within the Chinese community and to promote the advancement of Chinese multi-modal models, we developed the **Youku Dense Caption** dataset. This is the first large-scale and high-quality dataset specifically for Chinese dense video captioning, sourced from Youku, a prominent Chinese video-sharing platform.

## Dataset Overview

- **Total Videos**: 31,466 complete short videos
- **Total Captions**: 311,921 Chinese captions
- **Language**: Chinese
- **Source**: Youku (优酷)

This dataset represents the largest publicly available collection of fine-grained Chinese video descriptions as of now. Additionally, several benchmarks for Chinese video-language tasks have been established based on the Youku Dense Caption dataset, including retrieval, grounding, and generation tasks.

## Benchmarks

We set up the following benchmarks using the Youku Dense Caption dataset:
- **Retrieval Tasks**: Assessing the retrieval capabilities of video captions.
- **Grounding Tasks**: Evaluating how well models can ground language to video content.
- **Generation Tasks**: Testing the models' ability to generate relevant captions for given video segments.

Extensive experiments and evaluations have been conducted on existing state-of-the-art multi-modal models, demonstrating the dataset’s utility and the potential for further research.

## Usage

To use this dataset for training or evaluation, you can download it from [here](https://modelscope.cn/datasets/os_ai/Youku_Dense_Caption/). Please ensure to cite the dataset in your research as follows:

```bibtex
@inproceedings{xiong2025youku,
    title={Youku Dense Caption: A Large-scale Chinese Video Dense Caption Dataset and Benchmarks},
    author={Zixuan Xiong, Guangwei Xu, Wenkai Zhang, Yuan Miao, Xuan Wu, LinHai, Ruijie Guo, Hai-Tao Zheng},
    booktitle={The Thirteenth International Conference on Learning Representations},
    year={2025},
    url={https://openreview.net/forum?id=vvi5OjPhbu}
}
```

## License

This dataset is released under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) license (Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License).
