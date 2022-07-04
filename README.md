# labelme2coco
Firstly install labelme and annotate data
pip install labelme

then
convert labelme annotated data in one json file for segmentation training using command
python labelme2coco.py train --output train.json           (train is the directory of image and annotated data)
