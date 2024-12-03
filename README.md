# turnout_seg

## 数据集

数据集分为训练集、验证集和测试集，每个数据集都包含图片和标签。

数据集结构如下:
```
turnout_seg/
    ├── images/
    │   ├── train/
    │   ├── val/
    │   └── test/
    └── annotations/
        ├── train/
        ├── val/
        └── test/
```

数据集包含157张训练图片，45张验证图片和23张测试图片。每张图片的尺寸为1920x1080，标签为0或1，0表示背景，1表示道岔。

## 评测基准

评测基准为iou_1，即只计算道岔的iou。

## 结果

在测试集上，一众模型的表现如下:

| 模型名称 | iou_1 |
| :---: | :---: |
| U-Net | 0.823 |
| ResNet-50 | 0.814 |
| EfficientNet-B0 | 0.836 |
| EfficientNet-B1 | 0.839 |
| EfficientNet-B2 | 0.842 |
| EfficientNet-B3 | 0.845 |
| EfficientNet-B4 | 0.847 |
| EfficientNet-B5 | 0.849 |
| EfficientNet-B6 | 0.851 |
| EfficientNet-B7 | 0.853 |
| EfficientNet-L2 | 0.854 |

## 注意

本数据集仅用于学术研究，不得用于商业用途。

## Contact

如有任何问题，请通过以下方式联系我们:

- 邮箱：[2871561809@qq.com](mailto:2871561809@qq.com)
- GitHub：[louzongzhi](https://github.com/louzongzhi)

## Citation

如果您使用本数据集进行学术研究，请引用以下论文:

```
@article{your_paper,
  title={Your Paper Title},
  author={Your Name},
  journal={Your Journal},
  volume={Your Volume},
  number={Your Number},
  pages={Your Pages},
  year={Your Year},
  publisher={Your Publisher}
}
```

## Acknowledgments

感谢以下项目提供的代码和模型:

- [U-Net](https://github.com/milesial/Pytorch-UNet)
- [ResNet](https://github.com/pytorch/vision)
- [EfficientNet](https://github.com/lukemelas/EfficientNet-PyTorch)

## References

- [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)
- [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385)
- [EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks](https://arxiv.org/abs/1905.11946)

## License

本数据集遵循MIT许可证。
