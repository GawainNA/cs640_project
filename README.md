# CS640 Project: Evaluation on Text-to-Image Model

## Introduction
This project presents a reasonable frame to evaluate text-to-image models. With Input Text and Generated Images, it will give a score between 0 ~ 5, 0 means the worst. This frame has three components, "Object Detection", "Image Captioning" and "Sentence Analysis". We have defult model for each component but they could be customly motified.

## Generating a specified number of objects
### Method
Object Dectection and Instance Segmentation: Dectectron2-Mask-RCNN
### Evaluation Metric

## Generating objects with specified spatial positioning
LaBSE and ViT

## Generating objects with specified colors
Color analyze base on Instance Mask from Mask R-CNN

## Incorporating quoted text with correct spelling
CRAFT-Text-Extraction

EasyOCR
