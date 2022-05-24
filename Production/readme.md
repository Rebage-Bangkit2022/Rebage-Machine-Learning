# Dataset

Dilakukan augmentasi gambar berupa:

-   random_adjust_brightness
    random_adjust_brightness.max_delta = 0.1 <br>

-   random_adjust_contrast
    random_adjust_contrast.min_delta = 0.9 <br>
    random_adjust_contrast.max_delta = 1.1 <br>

-   random_adjust_saturation
    random_adjust_saturation.min_delta = 0.9 <br>
    random_adjust_saturation.max_delta = 1.1 <br>

# model_1

Train steps = 30_000 <br>
initial learning rate = 0.0001 <br>
schedule[0] steps = 10_000 <br>
schedule[0] learning rate = 0.000085667 <br>

schedule[1] steps = 20_000 <br>
schedule[1] learning rate = 0.000055667 <br>

schedule[2] steps = 30_000 <br>
schedule[2] learning rate = 0.000015667 <br>

-   Average Precision (AP) @[ IoU=0.50:0.95 | area= all | maxDets=100 ] = 0.672
-   Average Precision (AP) @[ IoU=0.50 | area= all | maxDets=100 ] = 0.938
-   Average Precision (AP) @[ IoU=0.75 | area= all | maxDets=100 ] = 0.765
-   Average Precision (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.410
-   Average Precision (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.560
-   Average Precision (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.745
-   Average Recall (AR) @[ IoU=0.50:0.95 | area= all | maxDets= 1 ] = 0.660
-   Average Recall (AR) @[ IoU=0.50:0.95 | area= all | maxDets= 10 ] = 0.748
-   Average Recall (AR) @[ IoU=0.50:0.95 | area= all | maxDets=100 ] = 0.753
-   Average Recall (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.562
-   Average Recall (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.686
-   Average Recall (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.804
    INFO:tensorflow:Eval metrics at step 30000 <br>
    INFO:tensorflow: + Loss/localization_loss: 0.099605 <br>
    I0524 19:10:50.909131 6340 model_lib_v2.py:1018] + Loss/localization_loss: 0.099605 <br>
    INFO:tensorflow: + Loss/classification_loss: 0.215143 <br>
    I0524 19:10:50.910132 6340 model_lib_v2.py:1018] + Loss/classification_loss: 0.215143 <br>
    INFO:tensorflow: + Loss/regularization_loss: 0.139656 <br>
    I0524 19:10:50.910132 6340 model_lib_v2.py:1018] + Loss/regularization_loss: 0.139656 <br>
    INFO:tensorflow: + Loss/total_loss: 0.454404 <br>
    I0524 19:10:50.911130 6340 model_lib_v2.py:1018] + Loss/total_loss: 0.454404 <br>

---
