# NTIRE2024_RAIM_iipir

This is the code repository of Restore Any Image Model (RAIM) in the Wild: An NTIRE Challenge in Conjunction with CVPR 2024.

## How to run?

### Installation

``` shell
git clone https://github.com/zzzhy03/NTIRE2024_RAIM_iipir.git
cd NTIRE2024_RAIM_iipir
pip3 install -r requirements.txt
```

### Pretrained Model

The pretrained model can be downloaded from [Google Drive](https://drive.google.com/drive/folders/1oHzTMuhQV831PPxkloox_D07nyqmyI-9?usp=drive_link).

### Inference

``` shell
python demo_phase2.py --input_folder xxx --output_folder xxx --kernel_model_path pretrained/net_kernel.pth --restore_model_path pretrained/net_g.pth
```

