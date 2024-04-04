# LADA

# LADA: Semi-Supervised Domain Adaptation for Object Detection

## Overview

This repository contains supplementary materials and code related to the paper titled "[LADA: Semi-Supervised Domain Adaptation for Object Detection](https://arxiv.org/pdf/2404.01842.pdf)," which presents a new suggested labels for opensource hpwren dataset.

## Abstract

The paper "LADA: Learning Artificially Driven Agents" introduces a novel protocol for wildfire detection, leveraging semi-supervised Domain
Adaptation for object detection, accompanied by a corresponding dataset designed for use by both academics and industries. Our dataset encompasses 30 times more diverse labeled scenes for the current largest benchmark wildfire dataset, HPWREN, and introduces a new labeling policy for wildfire detection. 

## Contents

- `hpwren_source.json`: this json file contains bbox labels in coco-json format for source domain labels. It offers merged bbox as suggested in paper.
- `hpwren_source_original.json`: this json file contains bbox labels in coco-json format for source domain labels. It offers splitted bbox.
- `target_label_x%.json`: this json file contains bbox labels in coco-json format for x% labels for target domain labels. It offers merged bbox as suggested in paper.
- `target_label_x%_original.json`: this json file contains bbox labels in coco-json format for x% labels for target domain labels. It offers splitted bbox.

## Citation

If you find the LADA framework or the insights from our paper useful in your research, please consider citing:

`@article{lada, title={LADA: Semi-Supervised Domain Adaptation for Object Detection}, author={ Jang, JooYoung and Cha, Youngseo and Kim, Jisu and Lee, SooHyung and Lee, Geonu and Cho, Minkook and Hwang, Young and Kwak, Nojun}, journal={Tackling Climate Change with Machine Learning (ICLR 2024 Workshop), May 2024.}, year={2024}, }`