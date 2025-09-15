# Deep Learning-Based Car Plate Recognition System

**UCCD3074 — Deep Learning for Data Science (Assignment 2)**
- **Group No.:** 13
- **Group Leader:** Brandon Kong Chen Wu  
- **Group Members:** Chin Zi Wei, Ting Jun Jing, Look Zheng Hong

---

## Project

Automatic Number Plate Recognition (ANPR) built with deep learning. This repo contains the training/inference notebook, the final report, and a demo video.

---

## Repository contents

* `Group13_Report.pdf` — Final project report.
* `car_plate_recognition.ipynb` — Training and inference notebook (detection + OCR + tracking).

---

## Demo

If your platform supports HTML video tags, the demo is at `outputvideo`. Example:

![Demo GIF](./outputvideo/output_video_02.gif)
![Demo GIF](./outputvideo/output_video_03.gif)
![Demo GIF](./outputvideo/output_video_04.gif)


---

## Requirements / Install

Recommended: create and activate a virtual environment, then install required packages:

```bash
pip install python-levenshtein paddlepaddle paddleocr ultralytics deep-sort-realtime
```

---

## Quick start

1. Clone the repo and enter its folder:

   ```bash
   git clone <this-repo-url>
   cd <repo-folder>
   ```

2. Install dependencies (see above).

3. Open the notebook and run the cells:

   ```bash
   jupyter notebook car_plate_recognition.ipynb
   ```

   Follow the notebook sections for data prep, training, and inference. Inference demo cells reference `outputvideo/` and saved model paths.

---

## Usage notes

* `car_plate_recognition.ipynb` includes:

  * data loading & preprocessing
  * training loops and model saving
  * detection → OCR → tracking inference pipeline
  * visualization and evaluation utilities


---

## GitHub Repo Link

https://github.com/junjing02/deeplearingA2

---