# [PYTHON] QuickDraw

## Introduction

Here is my python source code for QuickDraw - an online game developed by google. with my code, you could: 
* **Run an app which you could draw in front of a camera (If you use laptop, your webcam will be used by default)**
* **Run an app which you could draw on a canvas**

## Camera app
Below is the demo by running the sript **camera_app.py**:
<p align="center">
  <img src="demo/quickdraw.gif" width=800><br/>
  <i>Input video</i>
</p>

## Drawing app
The script and demo will be released soon

## Dataset
The dataset used for training my model could be found at [Quick Draw dataset] https://console.cloud.google.com/storage/browser/quickdraw_dataset/sketchrnn. Here I only picked up 20 files for 20 categories

## Categories:
The table below shows 20 categories my model used:

| Dataset                | Classes | Train samples | Test samples |
|------------------------|:---------:|:---------------:|:--------------:|
| AG’s News              |    4    |    120 000    |     7 600    |
| Sogou News             |    5    |    450 000    |    60 000    |
| DBPedia                |    14   |    560 000    |    70 000    |
| Yelp Review Polarity   |    2    |    560 000    |    38 000    |
| Yelp Review Full       |    5    |    650 000    |    50 000    |
| Yahoo! Answers         |    10   |   1 400 000   |    60 000    |
| Amazon Review Full     |    5    |   3 000 000   |    650 000   |
| Amazon Review Polarity |    2    |   3 600 000   |    400 000   |



## Requirements

* **python 3.6**
* **cv2**
* **pytorch** 
* **numpy**
