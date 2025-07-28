# CAMO-GenOS: Generative One-Shot Camouflage Instance Segmentation

This repository is the official implementation of the paper entitled: **Generative One-Shot Camouflage Instance Segmentation**. <br>
**Authors**: Thanh-Danh Nguyen, Vinh-Tiep Nguyen†, and Tam V. Nguyen.

[[Paper]](https://doi.org/) [[Code]](https://github.com/danhntd/CAMO-GenOS) [[Project Page]](https://danhntd.github.io/projects.html)

---
## Updates
- **[2025/07]** We have released the initial page for CAMO-GenOS⚡!
- **[2025/07]** Added environment setup instructions

## 1. Environment Setup

### Requirements

- CUDA 12.x (tested on Docker container)

### Quick Start

1. **Build and start the container:**
   ```bash
   cd environment
   docker compose build
   docker compose up -d
   ```

2. **Enter the container:**
   ```bash
   docker exec -it mmlab_danhnt_fs /bin/bash
   ```

3. **Verify GPU access (inside container):**
   ```bash
   nvidia-smi
   conda info --envs
   ```

## 2. Data & Weights

### Dataset

### Pre-trained Weights


## 3. Training Pipeline


### Datasets


### Configuration

All training configurations are located in the `./src/*/configs/` directory. Each configuration file contains detailed hyperparameters and training settings for different experimental setups.

### Training Commands

All training scripts are located in the `./src/*/scripts/` directory. Detailed usage instructions and command examples are provided in the respective script files.

## 4. Citation

If you find this work useful for your research, please cite our paper:

```bibtex
@article{

}
```

## 5. Acknowledgements

We would like to acknowledge the following open-source projects that have contributed to this work:

- **[Detectron2](https://github.com/facebookresearch/detectron2.git)**
- **[iMTFA](https://github.com/danganea/iMTFA)**
- **[iFSRCNN](https://github.com/VinAIResearch/iFS-RCNN)**
