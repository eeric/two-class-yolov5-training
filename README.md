# two-class-yolov5-training
two classificiation training online to person and nonhuman

not change label while modify target online, please see 245-247th line in train_two_class.py
# yolov5
https://github.com/ultralytics/yolov5
# anchors calculation
if model trained different with coco classes, recalculation anchors 

eg.

anchors:

    -[10,13, 16,30, 33,23]  # P3/8

    -[30,61, 62,45, 59,119]  # P4/16

    -[116,90, 156,198, 373,326]  # P5/32

using data/gen_anchors/calculate_anchors.py

from https://github.com/PeterH0323/Smart_Construction


