# SReResNet
SReResNet: Stage Recursive Residual Network. Enhancing semantic category information without extra convolutional layers.

## Updates
    Code is updating and trained models will be available soon.
    
#### For a complete installation 
[maskrcnn-benchmark](https://github.com/facebookresearch/maskrcnn-benchmark). The installation is the same as original maskrcnn-benchmark.
 
## Required hardware
Only one Nvidia 2080 GPU is needed.
Fix SOLVER setting is used like [here](SReResNet_on_FCOS/configs/fcos/fcos_R_50_FPN_1x.yaml) 
 
    SOLVER:
      BASE_LR: 0.0025
      WEIGHT_DECAY: 0.0001
      STEPS: (480000, 640000)
      MAX_ITER: 720000
      IMS_PER_BATCH: 2
      WARMUP_METHOD: "constant"

## Models
Updating...