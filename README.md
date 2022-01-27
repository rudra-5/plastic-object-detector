# plastic-object-detector
A YOLOv5 object detector with over 85% accuracy in detecting plastic items.

In order to use the trained weights to detect, do the following (in cmd):
```bash
git clone https://github.com/rudra-first/plastic-object-detector.git # clone this repo
cd plastic-object-detector 
pip install -qr requirements.txt # install necessary packages
python detect.py --weights weights/plastic_best_89.pt --img 416 --conf 0.4 --source 0 #for webcam 
                                                                                    {path} #to the image or the video               
```
