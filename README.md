# Image-Captioning-Project

# Instructions
### 1. Please ensure you install coco api
```
cd cocoapi/PythonAPI
make
```
or 
```
python setup.py install
```
### 2. Make sure your cocoapi folder in following tree struct (images/ at least with train and val)
```
cocoapi
├─annotations
│  └─.idea
├─common
├─images
│  ├─test2014
│  ├─train2014
│  └─val2014
├─MatlabAPI
│  └─private
├─PythonAPI
│  ├─build
│  │  ├─lib.win-amd64-3.6
│  │  │  └─pycocotools
│  │  └─temp.win-amd64-3.6
│  │      ├─common
│  │      ├─MatlabAPI
│  │      │  └─private
│  │      └─Release
│  │          └─pycocotools
│  ├─demos
│  └─pycocotools
│      └─__pycache__
└─results
```

### 3. Play with the app

* Move to working dir
```
cd img_caption
```
* Run the app
```
python TinkerUI.py
```
* Click ```Browse``` and we do provide some test images for you:
```
img_caption/user_uploaded
```
* Boom! You should have see some good stuff!

### 4. Model Applied
![alt text](https://github.com/Joe627487136/img_caption_project/blob/master/img_caption/images/encoder-decoder.png)
Our models is in:
```
img_caption\models\legit_model
```
(PS: Dont ask how many times failed in training and just take a look in the jupyter notebook log - ```img_caption\2_Training.ipynb```)


### 5. Jupyter Notebook Workflow
* Vocab generation -- ```img_caption\1_Preliminaries.ipynb```
* Training (with Val BLEU score at the bottom of the notebook) -- ```img_caption\2_Training.ipynb```
* Demo -- ```img_caption\3_Demo.ipynb```

### 6. Legit and Funny Outputs
* Perfect captioning:

![alt text](https://github.com/Joe627487136/img_caption_project/blob/master/img_caption/out_result/Plane_legit.png)
![alt text](https://github.com/Joe627487136/img_caption_project/blob/master/img_caption/out_result/Tennis_legit.png)

* Weird sentence format or not fully captioning

![alt text](https://github.com/Joe627487136/img_caption_project/blob/master/img_caption/out_result/Dog_legit.png)
![alt text](https://github.com/Joe627487136/img_caption_project/blob/master/img_caption/out_result/Moto_partial.png)

* These are some really funny outcome

![alt text](https://github.com/Joe627487136/img_caption_project/blob/master/img_caption/out_result/Taxi_bad.png)
![alt text](https://github.com/Joe627487136/img_caption_project/blob/master/img_caption/out_result/Bear_bad.png)

(PS: I can be a giraffe as well!!!)


### 7. Group Member

```
1001603 ZHOU XUEXUAN
1001427 WENG YUNFAN
1001417 ZHANG CHENG
1001426 SHANG XIAOSHENG (Play less PUBG plz)
```





