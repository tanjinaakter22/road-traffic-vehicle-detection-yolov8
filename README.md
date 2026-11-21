# Vehicle Detection Using YOLOv8 (Car & Motorcycle)

A hands-on computer vision project built with **YOLOv8**, **Python**, and **Google Colab** to detect target vehicles (`car` and `motorcycle`) in dense road traffic video footage.

## Overview

Urban road traffic involves overlapping vehicles, varying distances, and fast motion. This project demonstrates how to run **Ultralytics YOLOv8** on a **Google Colab T4 GPU** environment, filter specific vehicle classes (`car` = class `2`, `motorcycle` = class `3`), tune confidence thresholds, and export key detection frames as `.jpg` images for inspection and presentation.

## Key Features

* **GPU-Accelerated Inference:** Runs smoothly in Google Colab with T4 GPU support.
* **Targeted Class Filtering:** Focuses specifically on `car` (class `2`) and `motorcycle` (class `3`) rather than all COCO classes.
* **Confidence Threshold Control:** Adjustable `conf` value to capture vehicles in busy traffic scenes.
* **Frame-by-Frame Image Export:** Saves selected detection frames (`.jpg`) directly from video inference streams so results can be easily viewed and shared.

## Tech Stack

* **Language:** Python
* **Model / Library:** Ultralytics YOLOv8 (`yolov8n.pt`)
* **Environment:** Google Colab (T4 GPU)
* **Video / Media Utilities:** `yt-dlp`, OpenCV / Ultralytics prediction pipeline

## Workflow Steps

1. **Environment Setup:** Enable GPU acceleration in Google Colab and install required packages (`ultralytics`, `yt-dlp`).
2. **Video Input:** Load traffic video footage into `/content/` (via download or manual upload).
3. **Vehicle Detection:** Run YOLOv8 inference with `classes=[2, 3]` and a chosen `conf` threshold.
4. **Output Extraction:** Save annotated detection frames (such as `frame_90.jpg` and `frame_180.jpg`) and download the Colab notebook (`.ipynb`).


## Sample Detection Outputs

### 1. Detection Frame 1
<img width="720" height="1280" alt="frame_90" src="https://github.com/user-attachments/assets/a4761309-bd0d-4742-a523-ccf414a6e095" />


### 2. Detection Frame 2
<img width="720" height="1280" alt="frame_210" src="https://github.com/user-attachments/assets/e23c6dea-4036-4cb5-807b-4185c88cde94" />


### 3. Detection Frame 3
<img width="720" height="1280" alt="frame_360" src="https://github.com/user-attachments/assets/089d21f8-97d5-45f9-9b0c-0d43f8a7cb8e" />

---

## Author

**Tanjina Akter**  
AI Automation Expert | Computer Vision & Workflow Automation Enthusiast
