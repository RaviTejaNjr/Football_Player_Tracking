
# Football_Player_Tracking

This project uses YOLO (You Only Look Once) V8 object detection model and Supervision for Detecting and Tracking football players, referees, and ball in football match videos


## Demo
Please watch the demo here:

https://github.com/user-attachments/assets/f56f44f2-838d-4d20-afb8-b187a220aa53


## Run Locally or on Google Colab
I have run the files both on my Local PC and on Google Colab.
Both the files can be found out in the Repo.

Please refer the name of the file carefully:

Football_Player_Tracking_Local_GoogleColab.ipynb
Football_Player_Tracking_Local_Machine.ipynb


## Installation
Creating a new environment variable is recommended.

If Conda is available, use the following commands to create one:

```bash
conda create -n Football python==3.8

conda activate Football
```
    

Install all the Dependensies Required using the requirements file

```bash
pip install -r requirements.txt
```
    
## Challenges
For the TeamClassifier module, I used the package directly available in Roboflow Github which can be found here: 
[**Roboflow Sports Package**](https://github.com/roboflow/sports)

And to use this package GIT needs to be Installed for windows, and after installation, if you get any issues, follow the below instructions.

If you face any problem 'Cannot find command 'git', Go through this:
[**Problem installing GitHub packages**](https://github.com/stefmolin/Hands-On-Data-Analysis-with-Pandas-2nd-edition/issues/3#issuecomment-841834571)

Follow the instructions below for setting the path and variables
[**Instructions Here**](https://www.computerhope.com/issues/ch000549.htm)

## Required Files
All the **source videos** are taken from:  
**https://www.kaggle.com/datasets/saberghaderi/-dfl-bundesliga-460-mp4-videos-in-30sec-csv**

The **Pretrained model** is trained on RoboFlow on the following Dataset:
**https://app.roboflow.com/carton-box/football_project-qi0r6/1**

The **Pretrained model** has been trained on my **Local Machine** for **50 Epochs** and can be found on my other Repo: [**Link Here**]