![image](https://github.com/user-attachments/assets/84d89aee-87f6-4960-a45c-2075cd1a3e40)## U-Net++
UNet++ is an architecture for semantic segmentation based on the U-Net. Through the use of densely connected nested decoder sub-networks, it enhances extracted feature processing and was reported by its authors to outperform the U-Net in Electron Microscopy (EM), Cell, Nuclei, Brain Tumor, Liver and Lung Nodule medical image segmentation tasks.

![image](https://github.com/user-attachments/assets/f44ffda0-b3a4-49f2-a00b-43cc88337b44)

## Key Features
- **Nested Dense Skip Pathways**: Redesigned skip connections reduce the semantic gap between encoder and decoder feature maps, enabling the optimizer to learn more efficiently.
- **Deep Supervision**: Multi-level supervision during training improves convergence and segmentation accuracy.
  
## Reference
- **Paper**: [UNet++: A Nested U-Net Architecture for Medical Image Segmentation](https://doi.org/10.48550/arXiv.1807.10165)
- **Authors**: Zongwei Zhou, Md Mahfuzur Rahman Siddiquee, Nima Tajbakhsh, Jianming Liang
- **Published**: Accepted by the 4th Deep Learning in Medical Image Analysis (DLMIA) Workshop.

## Citation
If you find this work useful, please cite the original paper:
