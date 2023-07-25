
# YOLOv8-DeepSORT-Object-Tracking-and-Counting

## Google Collab Implementation

## Steps to run the code on your local machine
* Clone the GitHub Repository
```bash
git clone https://github.com/SingManjot/YOLOv8-DeepSORT-Object-Tracking-and-Counting
```
* Goto the cloned folder
```bash
cd YOLOv8-DeepSORT-Object-Tracking-and-Counting
```
* Install the Dependencies
```bash
pip install -e '.[dev]'
```
* If you face any errors using the above command, you can use this instead
```bash
pip install -r requirements.txt
```
* Setting the directory. This is the directory that will contain our driver program (predict.py), DeepSORT files, Model (link for pre-trained model provided below), Test Video
```bash
cd ultralytics/yolo/v8/detect
```
* Download the DeepSORT folder, extract it, and place the folder deep_sort_pytorch into the subfolder specified above
```bash
https://drive.google.com/drive/folders/1aBYfUWkqYcJjrE4OiaDVFmfbugBMn_op?usp=sharing 
```
* Download the pre-trained Model (not required but recommended) and place it in the subfolder specified above
```bash
https://drive.google.com/file/d/1SIqT3Y7vOQyJ6aiUYd-dpLjrgvYUV0LK/view?usp=drive_link
```
