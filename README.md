# Video Preprocessing 
This repository provides tools for preprocessing videos for TaiChi, VoxCeleb and UvaNemo dataset used in [paper](https://papers.nips.cc/paper/8935-first-order-motion-model-for-image-animation).

<!---
# Downloading
VoxCeleb with our preprocessing can be download in [.mp4](https://yadi.sk/d/6XkWUoJzjzuwVA) format and in [.png](https://drive.google.com/file/d/1VLhAbzbrexqg-nHq8l1AV8oc-Sq-x0kZ/view?usp=sharing). 

TaiChi can be downloade directly in format [.mp4](https://yadi.sk/d/03C366987mkS1w) or [.png](https://drive.google.com/file/d/10b_OiRxMKRgbrOQHQvM-OEISPWfiM7zY/view?usp=sharing).
-->

## Dowloading videos and cropping according to precomputed bounding boxes
1) Instal requirments:
```
pip install -r requirements.txt
```

2) Run the script
```
python crop_vox.py --workers 40 --device_ids 0,1,2,3,4,5,6,7 --format .mp4 --dataset_version 2
```

#### Additional notes

Citation:

```
@InProceedings{Siarohin_2019_NeurIPS,
  author={Siarohin, Aliaksandr and Lathuilière, Stéphane and Tulyakov, Sergey and Ricci, Elisa and Sebe, Nicu},
  title={First Order Motion Model for Image Animation},
  booktitle = {Conference on Neural Information Processing Systems (NeurIPS)},
  month = {December},
  year = {2019}
}
```
