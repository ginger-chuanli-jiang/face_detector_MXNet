# face_detector_MXNet

FaceJ:
    a simplified YOLO-based face detection model trained with WIDER_FACE datasets;

YOLO training pipeline:
    adapted from MXNET/GLUON tutorial;

WIDER_FACE:
    converted from jpg to rec using gluon tool im2rec;

Architecture:
    1. Resnet18: high speed;
    2. Resnet34: high accuracy;
    3. originally designed; ideas adopted from https://towardsdatascience.com/faced-cpu-real-time-face-detection-using-deep-learning-1488681c1602
