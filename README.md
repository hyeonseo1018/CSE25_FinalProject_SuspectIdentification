# CSE25 Final Project
Identicate Suspect from given video
## Dependency
### install torchreid

```
# cd to your preferred directory and clone this repo
git clone https://github.com/KaiyangZhou/deep-person-reid.git

# create environment
cd deep-person-reid/
conda create --name torchreid python=3.7
conda activate torchreid

# install dependencies
# make sure `which python` and `which pip` point to the correct path
pip install -r requirements.txt

# install torch and torchvision (select the proper cuda version to suit your machine)
conda install pytorch torchvision cudatoolkit=9.0 -c pytorch

# install torchreid (don't need to re-build it if you modify the source code)
python setup.py develop

```
## Figures and Output of YOLOv8
### /runs/detect/pedestrian_detection3

# Two Steps to run
## Step 1 : Pedestrian detection by YOLOv8 --> Pedestrain_Detection.ipynb
<img width="1680" height="947" alt="image" src="https://github.com/user-attachments/assets/00452112-865b-40f4-8a0c-b54145d13199" />

## Step 2 : Person re-identification by torchreid --> Suspect_Identification.ipynb
<img width="1646" height="1176" alt="image" src="https://github.com/user-attachments/assets/54dd0559-be0a-4477-8902-ec830459b8f2" />

