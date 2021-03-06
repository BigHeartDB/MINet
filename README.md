# Multi-scale Interactive Network for Salient Object Detection

CVPR 2020.

## Changelog

The code and experimental results have be released now :smile:.

* 2020/4/7: Simplify the structure of the repository.
* 2020/3/29: Update the method of evaluating results. (See the [`readme.md`](./code/readme.md#Evaluation) for more details.)
* 2020/3/28: Update our code, results, pretrained parameters and some documents.

## Repository Details

* `code`: Complete training and testing code about our method. The `readme.md` file describes how to use the code.
* `docs`: Github page about out paper. Here are some paper details.

## Related Links

* Paper:
    - Baidu Pan: <https://pan.baidu.com/s/1zN7m4aeDhRvTOeF2naATRg> (baidu: 48au)
    - Google Drive: <https://drive.google.com/file/d/1gUYu0hO_8Xc5jgpzetuOVFDrqeSOiKZN/view?usp=sharing>
* Results & Pretrained Parameters:
    - https://drive.google.com/drive/folders/16yTcf_m-ehnhWgXlN6hbZpBKMy6lYIQQ?usp=sharing

## Paper Details

### Abstract

> Deep-learning based salient object detection methods achieve great progress. However, the variable scale and unknown category of salient objects are great challenges all the time. These are closely related to the utilization of multi-level and multi-scale features. In this paper, we propose the aggregate interaction modules to integrate the features from adjacent levels, in which less noise is introduced because of only using small up-/down-sampling rates. To obtain more efficient multi-scale features from the integrated features, the self-interaction modules are embedded in each decoder unit. Besides, the class imbalance issue caused by the scale variation weakens the effect of the binary cross entropy loss and results in the spatial inconsistency of the predictions. Therefore, we exploit the consistency-enhanced loss to highlight the fore-/back-ground difference and preserve the intra-class consistency. Experimental results on five benchmark datasets demonstrate that the proposed method without any post-processing performs favorably against 23 state-of-the-art approaches. The source code will be publicly available at https://github.com/lartpang/MINet.

### Architecture

![](./assets/Network.png)

![](./assets/AIM.png)

![](./assets/SIM.png)

### Comparison

![](./assets/TableofResults.png)

![](./assets/CurveFigure.png)

![](./assets/VisualFigure.png)

## BibTeX

```text
@inproceedings{MINet-CVPR2020,
    author = {Youwei Pang and Xiaoqi Zhao and Lihe Zhang and Huchuan Lu},
    title = {Multi-scale Interactive Network for Salient Object Detection},
    booktitle = CVPR,
    year = {2020}
}
```
