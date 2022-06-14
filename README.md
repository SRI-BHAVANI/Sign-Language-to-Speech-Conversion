# Sign-Language-to-Speech-Conversion
<ul>
<li>In this project sign language is converted to speech using Faster RCNN Resnet to train the model, that classifies the input image and the generated text(class label) is converted to speech using win32com.client with Dispatch method. </li>
<li>In this project webcam is used to perform the classification, but can also be used for single image prediction.</li>
<li>The model is built on 10 classes-[Hello, Help, Hurt,LoveYou, No, One, Phone, Please, ThankYou, Yes], where 14 images from each class is used for training, and 4 images from each class is used for testing and 2 from each class for validation.</li>
<li>The complete procedure followed to build the model for this project can be found in this tutorial - https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/  </li>
 <li>Tensorflow Object Detection API and the transfer learning model faster_rcnn_resnet101_v1_640x640_coco17_tpu-8 from the tensorflow model zoo were used.</li>
 </ul>
 <br>
 <h2>Procedure </h2>
 <ol>
 <li>For creating the dataset,(ASL Dataset.ipynb) file is used.</li>
 <li>Once the dataset is created, label the images using LabelImg tool and seperated the data into train, test and validation folders.</li>
 <li> To Build the model, follow the [tutorial](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/) and the (ASL Training Using ResNet with Transfer Learning.ipynb) file, This file also includes the code for evaluation metrics. </li>
 <li>For the live demonstration, (ASL To Speech Demo) file is used.</li>
 
