# Bi-level Optimization of cnn on fpga

### Hardware details: 

The experiment is conducted without deploying on the FPGA board, thus any device with CPU or GPU and jupyter notebook can reproduce my experiment. Google Colab which is free and pre-installing all dependencies is highly recommended for reproducing the experiment. 
### Software dependencies: 
* Jupyter Notebook 
* Python 3.6+ and pip3
* Pytorch + cuda11 or pytorch
### Installation: 
* For jupyter notebook: please follow steps on https://jupyter.org/install to download 
* For python3.6 and pip3
  sudo apt-get install python python-pip python3 python3-pip
  sudo add-apt-repository ppa:jonathonf/python-3.6
  sudo apt-get update
  sudo apt-get install python3.6
 * For Pytorch
  pip3 install torch torchvision torchaudio 
### Experiment workflow:
  Sequentially click "run" button of each cell in the Jupyter Notebook File "EA\_Explore" will reproduce my experiment.
### Evaluation and expected results: This step is expected to have similar plots as the experiment results of combined exploration.
![results1](https://github.com/duyubo/bi-level-optimization-of-cnn-on-fpga/blob/main/result1.JPG)
![results2](https://github.com/duyubo/bi-level-optimization-of-cnn-on-fpga/blob/main/result2.JPG)
![results3](https://github.com/duyubo/bi-level-optimization-of-cnn-on-fpga/blob/main/result3.JPG)

