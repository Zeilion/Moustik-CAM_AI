<h1 align="center">Moustik-CAM AI</h1>

<p align="center">
  <img alt="Moustik-CAM_ico" src="./imgs/Moustik-cam_ico.png">
</p>

<p>
In order to detect if my cat (Moustik) wants to enter or leave my house (and also to detect potential intruders), I am training different homemade multi-box detection models, on the COCO dataset. The model with best performances will then be used in the Moustik-CAM program. 

These models will, at first, only be trained to distinguish cats and humans. Later, I will try to train it to distinguish other cats from mine. To do this, I will increase the amount of data in the "Moustik" class using a GAN. 

At first, the Moustik-CAM program will just send me an SMS, in order to warn me if my cat wants to go in or out. Then, in a second time, I will automate the window opening and closing.
</p>

<br>

> Why not directly use existing pre-trained algorithms for object detection?  

To improve my data science skills, follow my own workflow, build my own models and complete my first big "full stack" project.

<br>

<p>
This project is in early development and you can find <a href="./notebooks/datavis/Moustik_Cam_COCO_Dataset.ipynb">here</a> the Notebook I used to make my DataVis as well as the first tests of functions and training.
I started this project on Google Colab, before being able to invest in a 3080, that's why the first prototypes (models 1 to 4) were trained on this Notebook.

I'm currently editing the whole thing on PyCharm and will upload it once I have a working workflow to train and compare different models. However, I need to implement metrics first, like mAP (mean Average Precision).
</p>

<br>

Live test of a first prototype of Moustik-CAM AI, inspired by YOLOv1, trained on the COCO dataset (see model 4 in the notebook `Moustik-Cam_COCO_Dataset.ipynb`). The loss function still needs to be improved :

<p align="center">
  <img alt="Test_MCam_nms_230402" src="./imgs/Test_MCam_nms_230402.gif">
</p>

<br>

<p align="center">
  <a href="https://www.linkedin.com/in/matthieu-pelingre-3667b0210/">LinkedIn</a>
</p>
