# CSCI 5527 Project Fall 2023: EXPLORING UNCHARTED TERRAIN: OFF-ROAD DRIVABLE AREA SEGMENTATION WITH CYCLEGAN

## Goal
In our project, we plan to employ CycleGAN as a pivotal tool for generating ground truth labels due to its unique ability to address the challenges associated with off-road data. CycleGAN facilitates the creation of synthetic off-road images and corresponding segmentation masks, effectively expanding the available dataset without the need for extensive manual labelling. By leveraging CycleGAN, we not only alleviate data scarcity issues but also enhance domain adaptation, making the segmentation model more robust to variations in off-road environments. This approach contributes to more costeffective and efficient data generation. It allows us to tackle the scarcity of labelled off-road data while ensuring the model’s capacity to perform effectively in a wide range of off-road scenarios.

During the initial phase of our project, we focused on data exploration and understanding, as well as a comprehensive study of CycleGAN to ensure we have a solid grasp of its functioning and capabilities. This phase allowed us to identify specific dataset nuances and requirements unique to off-road scenarios. The dataset used is the ”Yamaha Off-Road Dataset” which has a lot of variability. In the later stages of the project, we shifted our attention to assessing the practical utility of the generated off-road images and segmentation masks. This evaluation involved rigorous testing of the model’s segmentation capabilities on an entirely unseen dataset, mimicking real-world scenarios that autonomous vehicles encounter. The goal is to measure the model’s generalization and ability to handle diverse off-road environments effectively. By carrying out these comprehensive testing procedures, we aim to validate the model’s robustness, thereby ensuring that it can reliably assist in off-road autonomous vehicle applications and contribute to the successful navigation of complex terrains.

Contributors: Prakadeeswaran Manivannan, Harish Gnana Sekaran, Supreeth Gadamsetty & Amitabha Deb

Advisor: Ju Sun

Reference Code: CycleGAN_Pytorch: Nachiket293: https://www.kaggle.com/code/nachiket273/cyclegan-pytorch/notebook

![result](https://github.com/adeb567/CSCI-5527-Project/blob/main/result.png?raw=true)

Weights: https://drive.google.com/drive/folders/1UFVdaxsCktq5Sd8npbrw21imXusHLDaH?usp=drive_link

Yamaha Dataset for training our model
:Daniel Maturana, Po-Wei Chou, Masashi Uenoyama, and Sebastian Scherer. "Real-time semantic mapping for autonomous off-road navigation." In Field and Service Robotics, pp. 335-350. Springer, 2018
