# CLIPCAM: Zero-shot Text-guided Object and Action Localization
## Official implementation of CLIPCAM: A Simple Baseline for Zero-shot Object and Action Localization (ICASSP 2022)

[Link to paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9747841)  

## Table of Contents
* [Environment Setup](#environment-setup)
* [Code Demo](#code-demo)


## Environment Setup
1. create conda enviroment with Python=3.7  
`conda create -n clipcam python=3.7`  
`conda activate clipcam`
2. install pytorch 1.7.1, torchvision 0.8.2 with compatible cuda version (or any compatible torch version)  
`conda install pytorch==1.7.1 torchvision==0.8.2 torchaudio==0.7.2 cudatoolkit=11.0 -c pytorch`
3. install required package  
`pip install -r requirements.txt`

### Code Demo
```bash
python clipcam.py \ 
    --image_path "images/10577.jpg" \ 
    --sentence "Give me the knife" \  
```
