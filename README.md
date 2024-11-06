# Overview
This project focuses on developing a model to segment and analyze sperm images using the SegSperm dataset. The goal is to create an accurate segmentation model that distinguishes between different parts of sperm cells (e.g., head, tail) in microscopic grayscale images. This project aims to aid research and innovation in reproductive biology and related fields by improving the accuracy of sperm morphology analysis through automated methods.

## Dataset
The **SegSperm dataset** is used in this project, consisting of microscopic grayscale images of sperm with associated binary segmentation masks. The dataset was collected by **Invicta Clinics** and is licensed under **CC BY-NC 4.0**. It includes the following folders:

- **train**: 432 images and segmentation masks.
- **test**: 119 images and segmentation masks (annotator GT1).
- **test_small**: 23 images and segmentation masks, annotated by three independent raters (GT1, GT2, GT3).

### Citation

If you use the SegSperm dataset in your research, please cite:

```bash
@article{lewandowska2023ensembling,
  title={Ensembling noisy segmentation masks of blurred sperm images},
  author={Lewandowska, Emilia and W{\k{e}}sierski, Daniel and Mazur-Milecka, 
          Magdalena and Liss, Joanna and Jezierska, Anna},
  journal={Computers in Biology and Medicine},
  pages={107520},
  year={2023},
  publisher={Elsevier}
}
doi: https://doi.org/10.1016/j.compbiomed.2023.107520


Purpose and Impact
Accurate sperm segmentation is crucial for various medical and research applications, including fertility studies, reproductive health, and cell morphology research. By automating sperm segmentation, this project aims to reduce manual workload, improve consistency in morphological analysis, and enable large-scale sperm analysis that would otherwise be time-consuming.

The potential impact includes:

Improving diagnostic tools in fertility studies.
Facilitating large-scale analysis of sperm morphology, aiding in more extensive research on sperm quality.
Encouraging further research in reproductive biology and medicine by providing a more accessible, automated approach.
License
This project is based on the SegSperm dataset, licensed under CC BY-NC 4.0, allowing for non-commercial use with attribution.
