# Yolov4_hs - 2022.07.01 ~ 2022.08.10
Yolov4_tiny기반으로 Yolov4 기본 모델보다 가벼우면서 정확성은 비슷한 모델을 만들고자함
Yolov4의 경우 30fps, Yolov4_tiny의 경우 180fps인데, Yolov4_hs는 80fps 정도이다.
mAP같은 경우, yolov4는 64.9 yolov4-tiny는 38.1 , yolov4_hs는 55.3으로 정확성도 높다.
darknet_ros기반이여서 Pytorch에 비해서 많이 무겁다.
