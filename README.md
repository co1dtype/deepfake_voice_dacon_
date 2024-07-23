# deepfake_voice_dacon_

```md
dataset/
├── dacon_dataset/
│   ├── test/
│   ├── test_bandstop_denoising/
│   ├── train/
│   ├── train_bandstop_denoising/
│   ├── train_bandstop_new_dataset/
│   ├── train_segment/
│   ├── train_silent/
│   ├── unlabeled_data/
│   ├── unlabeled_data_denoising/
│   ├── unlabeled_data_silent/
│   ├── unlabeled_data_silent_split/
│   ├── valid/
│   ├── valid_denoising/
│   ├── sample_submission.csv
│   ├── test.csv
│   ├── train_bandstop_new_dataset_addmix.csv
│   ├── train.csv
├── DeepFilterNet2/
├── pretrained_model_checkpoints/
├── pretrained_models/
├── vad_bandstop_boundaries/
├── vad_bandstop_boundaries_test/
├── vad_bandstop_boundaries_unlabeled/
├── noisy_datasets.csv
├── make_new_dataset_test.ipynb
├── make_new_dataset_train.ipynb
├── make_new_dataset_valid.ipynb
├── merged_audio.wav
├── merged_audio2.wav
├── valid.csv
└── w2v2_aasist.ipynb

```

## 개발 환경
> nvcc: NVIDIA (R) Cuda compiler driver  
Copyright (c) 2005-2023 NVIDIA Corporation  
Built on Wed_Nov_22_10:17:15_PST_2023  
Cuda compilation tools, release 12.3, V12.3.107  
Build cuda_12.3.r12.3/compiler.33567101_0  
CPU: Intel(R) Xeon(R) CPU E5-2699 v4 @ 2.20GHz  
RAM: 1000GB  
GPU: RTX 3090 24GB  
OS: Linux 5.4.0-167-generic  
Python: 3.11.9  

## 환경 설치
```md
conda create -n DACON_DEEPFAKE python=3.11.9
conda env create -f environment.yml

```

## 데이터셋
https://drive.google.com/drive/folders/1K2DOK3-J_9A6-HR8dErgbJc5y0ZPFyNv?usp=sharing










