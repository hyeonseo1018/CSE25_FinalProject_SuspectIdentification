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

## Step 2 : Person re-identification by torchreid --> Suspect_Identification.ipynb
