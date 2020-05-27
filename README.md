# License Plate Recogniton Using Azure AI Services

## Tasks Involved

* Object Detection (License Plate)
* Optical Character Recognition 

## Azure AI Services

<img src="https://www.softbanktech.co.jp/-/Media/SMC/special/blog/ms-azure_blog/2018/0036/dg01.png" height=200 width=400>

* <b>Custom Vision</b>

    * Dataset with Object Annotations Required to train your own model and then download model file.
    * In this project, we have downloaded TensorFlow model from Azure Custom Vision service.

* Azure Cognitive Services OCR.

## GUI

* Tkinter Python

<b>To use directly without GUI, use the predict function to send in the image (using OpenCv) and get the text.</b>

## Future Scope

Use Azure Functions to make it available as a REST service.

<img src="https://www.henkboelman.com/content/images/2018/08/overview.jpg" height=200 width=400>
