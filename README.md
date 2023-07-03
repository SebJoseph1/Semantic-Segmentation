# Cityscapes Pixel-Level Segmentation Benchmark!

For this assignment, you will create a baseline for [the Cityscapes Pixel-Level Segmentation Benchmark](https://www.cityscapes-dataset.com/)! You will do this in groups of two students.  Use the [template](https://github.com/5LSM0/Assignments/blob/main/Assignment%202/Assignment_2_Cityscapes_Baseline_template.ipynb) for this assignment on github. The goal is to create a network that performs semantic segmentation on the Cityscapes dataset. This dataset is a large collection of pictures taken from the perspective of a driver in various German cities. Each picture has a corresponding ground-truth image, where each pixel is given a color that corresponds to the class of the object appearing in that pixel. The table below shows the expected input and output of the solution you will be creating.

![alt text](https://github.com/5LSM0/Assignments/blob/main/Assignment%202/cityscapes_sample.png?raw=true)


This assignment determines **10%** of your final grade, and is also a warm-up for the final assignment, where you will be challenged with a harder task! You can use the outcome of this assignment as a starting point.

Training your neural network will likely take many hours, take this into account when making your working schedule. This notebook downloads the required data for the benchmark and sets up a training pipeline so you can focus on creating networks using the skills you learned during this course. Some exercises have been included to get you started. Join us during computer class or message an assistant if you have any questions.

# Deliverables
First, submit the template (questions with answers included) with your own code to your groups github page when you’re finished. 

Second, you have to submit your model for a first evaluation at phase 1 of our own [competition server](https://codalab.lisn.upsaclay.fr/competitions/11173#learn_the_details). (you have multiple opportunities for this please try it early to avoid problems). This will also be necessary for the final assignment.



Student1: Xingyi Li - x.li@student.tue.nl - Xavier321456 - Xavier321456

Student2: Sebastian Joseph - s.joseph1@student.tue.nl - SebJoseph1 - CodaLab username

The links to various datasets- most of these links expire by 5/5/23

snow truth label - https://filesender.surf.nl/download.php?token=70b03c8b-67fe-4a3f-9728-79997add31ca&files_ids=13209839
rain truth label - https://filesender.surf.nl/download.php?token=70b03c8b-67fe-4a3f-9728-79997add31ca&files_ids=13209843
fog truth label -https://filesender.surf.nl/download.php?token=70b03c8b-67fe-4a3f-9728-79997add31ca&files_ids=13209847
snow images - https://filesender.surf.nl/download.php?token=70b03c8b-67fe-4a3f-9728-79997add31ca&files_ids=13209851
rain image - https://filesender.surf.nl/download.php?token=f76f4413-d105-4069-b773-557dd6109623&files_ids=13213195
fog image - https://filesender.surf.nl/download.php?token=986159ae-fc42-453a-9171-c21352ada40b&files_ids=13213285
normal truth label - https://filesender.surf.nl/download.php?token=d9146b2e-5982-472a-9c41-1f5652d39f38&files_ids=13213593
normal image - https://filesender.surf.nl/download.php?token=07dc545a-c9f4-4a02-a181-7235849ad47c&files_ids=13213595

The link to trained model weights
deeplabv3 - https://filesender.surf.nl/download.php?token=185c5a86-23c7-476e-b614-9653c45ff960&files_ids=13234535
