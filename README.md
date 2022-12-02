# DSMMA workshop 2022 at University of Minnesota

This repo contains scripts and instructions for the Data Science in Multi-Messenger Astronomy
workshop held in 2022. The workshop covers the basics of downloading and working with crowd-sourced
data from the Muon Hunter Classic project hosted on Zooniverse. Part 1 covers the data mining and aggregation
step, while Part 2 covers the implementation of simple CNN to automatically predict on the aggregated data.


### Requirements
To run the files in this workshop you will need a working Python 3 installation with packages defined
in `requirements.txt`. Specifically, we will use several data analysis modules (e.g., numpy, scipy, scikit-learn)
and also PyTorch for training the neural network. You can install the packages by running the following 
command in your Python environment:
```bash
python3 -m pip install -r requirements.txt
```

### Getting the data
The data is currently hosted in two parts:

 - The classification data: This is a JSON file that contains about 2 millions classifications across
 120,000 subjects. You can download it from [this link](https://drive.google.com/file/d/16_dGBfgW5nhUDbhv37emRYQMmLFLBu2Y/view?usp=sharing)

 - The subject images: This is a tarball of the 120,000 images (sized at 128x128). You can download these from
 [this link](https://drive.google.com/file/d/1He8RX-aajAheWQIqBK1M7ovt_vbCyue9/view?usp=sharing). The filenames
 are the same as the Zooniverse subject ID.
