<div align="right">
  English | <a href="https://github.com/DIG-Beihang/XrayDetection/blob/master/readme_chinese.md">简体中文</a>
</div>

# Object Detection Under X-ray Security Inspection Scenario: Dataset & Papers <sup>📌</sup>


<p>📈 This is the summary web of open source dataset and critical papers for Object Detection under X-ray security inspection scenario done by the research group in the State Key Laboratory of Software Development Environment (SKLSDE) at Beihang University. We hope our work can contribute to the community and encourage more researchers to continue to work in this field.


## Introduction

This is the summary web of open source dataset and critical papers for Object Detection under X-ray security inspection scenario done by the research group in the State Key Laboratory of Software Development Environment (SKLSDE) at Beihang University. We hope our work can contribute to the community and encourage more researchers to continue to work in this field.

# Table of Contents

- [Introduction](#introduction)

- [Datasets](#1-released-datasets-for-xray-object-detection)
  - [OPIXray](#1opixray-occluded-prohibited-items-x-ray)
  - [HiXray](#2hixray-high-quality-x-ray)
  - [EDS](#3eds-endogenous-domain-shift)
  - [Xray FSOD](#4xray-fsod)

## 1. Released Datasets for Xray Object Detection

### 1）OPIXray: Occluded Prohibited Items X-ray

👆 [<b>BACK to Table of Contents</b> -->](#table-of-contents)
### 2）HiXray: High-quality X-ray

👆 [<b>BACK to Table of Contents</b> -->](#table-of-contents)

### 3）EDS: Endogenous Domain Shift

👆 [<b>BACK to Table of Contents</b> -->](#table-of-contents)

### 4）Xray FSOD

The dataset is constructed from images of defected electrical commutators that were provided and annotated by Kolektor Group. Specifically, microscopic fractions or cracks were observed on the surface of the plastic embedding in electrical commutators. The surface area of each commutator was captured in eight non-overlapping images. The images were captured in a controlled environment.

<div align=center><img src="metal_surface.png"></div>
<br>

- Official Link:https://www.vicos.si/Downloads/KolektorSDD

- Download Link：https://pan.baidu.com/share/init?surl=HSzHC1ltHvt1hSJh_IY4Jg (password：``1zlb``)


The dataset consists of:

- 50 physical items (defected electrical commutators)
- 8 surfaces per item
- Altogether 399 images:<br>
-- 52 images of visible defect<br>
-- 347 images without any defect
- Original images of sizes:<br>
-- width: 500 px<br>
-- height: from 1240 to 1270 px
- For training and evaluation images should be resized to 512 x 1408 px

For each item the defect is only visible in at least one image, while two items have defects on two images, which means there were 52 images where the defects are visible. The remaining 347 images serve as negative examples with non-defective surfaces.

<br>

👆 [<b>BACK to Table of Contents</b> -->](#table-of-contents)


