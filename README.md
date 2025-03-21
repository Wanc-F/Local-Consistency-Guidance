# Local-Consistency-Guidance

<div align="center">
  <video src="assets/teaster.mp4" width="70%" poster=""> </video>
</div>

## News

👍2025/03/07: This paper accepted to Computer Vision and Image Understanding.

## Environment

```
conda create -n LCG python=3.10
conda activate LCG
pip install -r requirement.txt
```
Then configuration [Ebsynth](https://github.com/jamriska/ebsynth).

## 1. Download Weights

We have provided weights for the three styles pre-trained in the paper:
    [Miles](https://www.alipan.com/s/vkhG1PV2Ccm), 
    [JinX](https://www.alipan.com/s/kR23SFnLzVv), 
    [Elsa](https://www.alipan.com/s/SpjHrQPxoM1). 
You can put them into the 'dreambooth_models/' directory.

## 2. Quick Start

Inference:
```
bash inference_video2video.sh
```

## 3. Personlized Training

You can take 20 512-by-512 anime character faces from the anime/CG to train Dreambooth yourself. For specific training, see [Dreambooth](https://huggingface.co/docs/diffusers/training/dreambooth).

Or you can download the SD1.5 Dreambooth model from [Civitai](https://civitai.com/) and use it directly.

## 4. Citation
If you find our work helpful, please cite us.

```
@article{Local Consistency Guidance,
    title   = {Local Consistency Guidance: Personalized Stylization Method of Face Video},
    author  = {W Feng, Y Liu, J Pei, G Cheng, L Wang},
    journal = {Computer Vision and Image Understanding},
    year    = {2025}
}
```



