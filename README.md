# Hyperspectral Object Tracking with Spectral Information Prompt (SP-HST)
Our Model Weight: [Baidu:vvw7](https://pan.baidu.com/s/131DRXutRF8bJpvTgVIj26g)  
Pretrain model: [TransT](https://drive.google.com/drive/folders/1GVQV1GoW-ttDJRRqaVAtLUtubtgLhWCE)  
Raw Result: [Baidu:5qry](https://pan.baidu.com/s/1k5n9qm55Bm1DqANlw_5LeA)  


![SP-HST](pipline.png)

## Usage

### Installation  
Create and activate a conda environment, we've tested on this env: You can follow the env setting of [TransT](https://github.com/chenxin-dlut/TransT).   

### Data Preparation  
* Hyperspectral training and test datasets:  
  * [HOTC2020](https://www.hsitracking.com/hot2020/)
  * [IMEC25](https://github.com/Chenlulu1993/HOMG)

### Path Setting  
Following [TransT](https://github.com/chenxin-dlut/TransT)

### Testing  
```
python pysot_toolkit/test.py
```

## Citation  
```
@article{gao2024hyperspectral,
  title={Hyperspectral Object Tracking with Spectral Information Prompt},
  author={Gao, Long and Chen, Langkun and Jiang, Yan and Xie, Weiying and Li, Yunsong},
  journal={Authorea Preprints},
  year={2024},
  publisher={Authorea}
}
```
