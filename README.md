# CS640 Project: Evaluation on Text-to-Image Model

## Introduction
This project presents a reasonable frame to evaluate text-to-image models. With Input Text and Generated Images, it will give a score between 0 ~ 5, 0 means the worst. This frame has three components, "Object Detection", "Image Captioning" and "Sentence Analysis". We have defult model for each component but they could be customly motified.


## Method
**Object Dectection and Instance Segmentation:** Dectectron2-Mask-RCNN

**Sentence embed:** LaBSE

**Image Caption:** Vit-GPT2

**OCR:** CRAFT-Text-Extraction and EasyOCR

## Dataset
COCO 2017 with Caption

## How to use
Follow the `Evaluation_Frame.ipynb` to build a frame with defult model setting.
