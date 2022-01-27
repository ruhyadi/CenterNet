# CenterNet3D
This repository for implementations CenterNet for 3D Object Detection based on Keypoint Estimation

## Multipose
```
python ./src/demo.py \
    multi_pose \
    --demo ./images \
    --load_model ./models/multi_pose_dla_3x.pth
```

## 3D Object Detection
```
python ./src/demo.py \
    ddd \
    --demo ./images \
    --load_model ./models/ddd_3dop.pth
```