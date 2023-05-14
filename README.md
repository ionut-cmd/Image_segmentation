# Skin Cancer Detection using Image Segmentation on HAM10000 Dataset

This repository contains the implementation of various image segmentation models for skin cancer detection using the HAM10000 dataset. We experimented with different architectures, including pretrained models such as EfficientNet, DeepLabV3Plus + U-Net, and UNet3+ with skip connections.

## Models

- EfficientNet: A pretrained convolutional neural network.
- DeepLabV3Plus + U-Net: A combination of the DeepLabV3+ architecture with the U-Net architecture.
- UNet3+: An encoder-decoder architecture with full-scale skip connections and deep supervisions for better accuracy and computational efficiency in medical image segmentation.

## Dataset

The [HAM10000](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T) dataset is a large collection of multi-source dermatoscopic images of common pigmented skin lesions.

## Getting Started

1. Clone this repository.
2. Download and extract the HAM10000 dataset.
3. Install the required packages.
4. Run the training scripts for the desired model(s).

## Citations

## Dataset

```bibtex
@article{Tschandl_2018,
  doi = {10.1038/sdata.2018.161},
  url = {https://doi.org/10.1038%2Fsdata.2018.161},
  year = 2018,
  month = {aug},
  publisher = {Springer Science and Business Media {LLC}},
  volume = {5},
  number = {1},
  author = {Philipp Tschandl and Cliff Rosendahl and Harald Kittler},
  title = {The {HAM}10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions},
  journal = {Scientific Data}
}
```

## For the UNet3+ implementation, please cite the following paper:

```bibtex
@misc{huang2020unet,
title={UNet 3+: A Full-Scale Connected UNet for Medical Image Segmentation},
author={Huimin Huang and Lanfen Lin and Ruofeng Tong and Hongjie Hu and Qiaowei Zhang and Yutaro Iwamoto and Xianhua Han and Yen-Wei Chen and Jian Wu},
year={2020},
eprint={2004.08790},
archivePrefix={arXiv},
primaryClass={eess.IV}
}
```

## License

This project is licensed under the [MIT License](LICENCE).
