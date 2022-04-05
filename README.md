# ECE1512_2022W_ProjectRepo_AotingChen_YunhongTian
# Project A: Visual Interpretation of Convolutional Neural Networks
This project endeavors to generate explanation maps that interpret the behavior of two models trained on different datasets. The first model is a very shallow CNN trained on “MNIST-1D”, a small-scale dataset prepared for generic array classification. The second model is a VGG- 7 network trained on the “HMT” dataset utilized for histopathologic tissue classification. There are three methods used: SISE, SmoothGrad, IntegratedGrad
* For MNIST-1D dataset: run the  MNIST1D.ipynb with suporting .py files saved in supplementPY folder.
* For HMT dataset: run the HMT.ipynb with suporting .py files saved in both supplementPY folder (only InteGrad_model2 files) and HMT_py folder.
# Project B
This project is divided into 2 tasks, (1) using conventional knowledge distillation framework as a model compression method for a popular digit classification dataset, “MNIST” and (2) using transfer learning and knowledge distillation to train a lightweight model for mimicking a pre-trained larger model in a clinical histopathology dataset, “MHIST”
* For MNIST dataset: run Task1-final.ipynb, the trained models can be found in Task1-model folder to save time and skip the compling process
* For MHIST dataset: run Task2-final.ipynb, the trained models can be found in Task2-model folder again to load
