Starting at epoch 0. LR=0.0014

Checkpoint Path: /Users/evanchan19/Desktop/COMP9517/project/logs/usa_rgb20250803T2343/mask_rcnn_usa_rgb_{epoch:04d}.h5
Selecting layers to train
fpn_c5p5               (Conv2D)
fpn_c4p4               (Conv2D)
fpn_c3p3               (Conv2D)
fpn_c2p2               (Conv2D)
fpn_p5                 (Conv2D)
fpn_p2                 (Conv2D)
fpn_p3                 (Conv2D)
fpn_p4                 (Conv2D)
In model:  rpn_model
    rpn_conv_shared        (Conv2D)
    rpn_class_raw          (Conv2D)
    rpn_bbox_pred          (Conv2D)
mrcnn_mask_conv1       (TimeDistributed)
mrcnn_mask_bn1         (TimeDistributed)
mrcnn_mask_conv2       (TimeDistributed)
mrcnn_mask_bn2         (TimeDistributed)
mrcnn_class_conv1      (TimeDistributed)
mrcnn_class_bn1        (TimeDistributed)
mrcnn_mask_conv3       (TimeDistributed)
mrcnn_mask_bn3         (TimeDistributed)
mrcnn_class_conv2      (TimeDistributed)
mrcnn_class_bn2        (TimeDistributed)
mrcnn_mask_conv4       (TimeDistributed)
mrcnn_mask_bn4         (TimeDistributed)
mrcnn_bbox_fc          (TimeDistributed)
mrcnn_mask_deconv      (TimeDistributed)
mrcnn_class_logits     (TimeDistributed)
mrcnn_mask             (TimeDistributed)
Epoch 1/15
100/100 [==============================] - 2059s 21s/step - loss: 2.1252 - rpn_class_loss: 0.2486 - rpn_bbox_loss: 0.6578 - mrcnn_class_loss: 0.2996 - mrcnn_bbox_loss: 0.4800 - mrcnn_mask_loss: 0.4391 - val_loss: 2.2218 - val_rpn_class_loss: 0.2406 - val_rpn_bbox_loss: 0.7797 - val_mrcnn_class_loss: 0.3033 - val_mrcnn_bbox_loss: 0.4510 - val_mrcnn_mask_loss: 0.4472
Epoch 1: current LR = 0.001400
Epoch 2/15
100/100 [==============================] - 3386s 34s/step - loss: 2.0914 - rpn_class_loss: 0.2374 - rpn_bbox_loss: 0.6454 - mrcnn_class_loss: 0.3120 - mrcnn_bbox_loss: 0.4623 - mrcnn_mask_loss: 0.4343 - val_loss: 2.0948 - val_rpn_class_loss: 0.1984 - val_rpn_bbox_loss: 0.6482 - val_mrcnn_class_loss: 0.3336 - val_mrcnn_bbox_loss: 0.4769 - val_mrcnn_mask_loss: 0.4377
Epoch 2: current LR = 0.001400
Epoch 3/15
100/100 [==============================] - 1846s 18s/step - loss: 1.9999 - rpn_class_loss: 0.2244 - rpn_bbox_loss: 0.5994 - mrcnn_class_loss: 0.3094 - mrcnn_bbox_loss: 0.4432 - mrcnn_mask_loss: 0.4235 - val_loss: 2.0500 - val_rpn_class_loss: 0.2155 - val_rpn_bbox_loss: 0.6554 - val_mrcnn_class_loss: 0.3225 - val_mrcnn_bbox_loss: 0.4443 - val_mrcnn_mask_loss: 0.4123
Epoch 3: current LR = 0.001400
Epoch 4/15
100/100 [==============================] - 1847s 18s/step - loss: 1.9707 - rpn_class_loss: 0.2169 - rpn_bbox_loss: 0.5973 - mrcnn_class_loss: 0.3003 - mrcnn_bbox_loss: 0.4376 - mrcnn_mask_loss: 0.4185 - val_loss: 2.0392 - val_rpn_class_loss: 0.2700 - val_rpn_bbox_loss: 0.5097 - val_mrcnn_class_loss: 0.3356 - val_mrcnn_bbox_loss: 0.4839 - val_mrcnn_mask_loss: 0.4399
Epoch 4: current LR = 0.001400
Epoch 5/15
100/100 [==============================] - 1845s 18s/step - loss: 1.9003 - rpn_class_loss: 0.1980 - rpn_bbox_loss: 0.5570 - mrcnn_class_loss: 0.3147 - mrcnn_bbox_loss: 0.4171 - mrcnn_mask_loss: 0.4135 - val_loss: 2.1685 - val_rpn_class_loss: 0.2020 - val_rpn_bbox_loss: 0.6639 - val_mrcnn_class_loss: 0.3703 - val_mrcnn_bbox_loss: 0.4827 - val_mrcnn_mask_loss: 0.4496
Epoch 5: current LR = 0.001400
Epoch 6/15
100/100 [==============================] - 1845s 18s/step - loss: 1.8711 - rpn_class_loss: 0.1962 - rpn_bbox_loss: 0.5688 - mrcnn_class_loss: 0.3091 - mrcnn_bbox_loss: 0.4016 - mrcnn_mask_loss: 0.3955 - val_loss: 1.8402 - val_rpn_class_loss: 0.1614 - val_rpn_bbox_loss: 0.5170 - val_mrcnn_class_loss: 0.3273 - val_mrcnn_bbox_loss: 0.4189 - val_mrcnn_mask_loss: 0.4156
Epoch 6: current LR = 0.001400
Epoch 7/15
100/100 [==============================] - 1847s 18s/step - loss: 1.8668 - rpn_class_loss: 0.2013 - rpn_bbox_loss: 0.5522 - mrcnn_class_loss: 0.3086 - mrcnn_bbox_loss: 0.4005 - mrcnn_mask_loss: 0.4042 - val_loss: 1.8676 - val_rpn_class_loss: 0.2030 - val_rpn_bbox_loss: 0.5238 - val_mrcnn_class_loss: 0.2982 - val_mrcnn_bbox_loss: 0.4270 - val_mrcnn_mask_loss: 0.4157
Epoch 7: current LR = 0.001400
Epoch 8/15
100/100 [==============================] - 1850s 19s/step - loss: 1.7999 - rpn_class_loss: 0.1805 - rpn_bbox_loss: 0.5341 - mrcnn_class_loss: 0.3018 - mrcnn_bbox_loss: 0.3892 - mrcnn_mask_loss: 0.3942 - val_loss: 1.6877 - val_rpn_class_loss: 0.1604 - val_rpn_bbox_loss: 0.4795 - val_mrcnn_class_loss: 0.2463 - val_mrcnn_bbox_loss: 0.3830 - val_mrcnn_mask_loss: 0.4184
Epoch 8: current LR = 0.001400
Epoch 9/15
100/100 [==============================] - 1848s 18s/step - loss: 1.7938 - rpn_class_loss: 0.1875 - rpn_bbox_loss: 0.5420 - mrcnn_class_loss: 0.2840 - mrcnn_bbox_loss: 0.3841 - mrcnn_mask_loss: 0.3962 - val_loss: 1.9376 - val_rpn_class_loss: 0.2394 - val_rpn_bbox_loss: 0.5940 - val_mrcnn_class_loss: 0.3097 - val_mrcnn_bbox_loss: 0.3950 - val_mrcnn_mask_loss: 0.3994
Epoch 9: current LR = 0.001400
Epoch 10/15
100/100 [==============================] - 1859s 19s/step - loss: 1.7711 - rpn_class_loss: 0.1826 - rpn_bbox_loss: 0.5165 - mrcnn_class_loss: 0.3157 - mrcnn_bbox_loss: 0.3689 - mrcnn_mask_loss: 0.3874 - val_loss: 1.8001 - val_rpn_class_loss: 0.1997 - val_rpn_bbox_loss: 0.4511 - val_mrcnn_class_loss: 0.3326 - val_mrcnn_bbox_loss: 0.4304 - val_mrcnn_mask_loss: 0.3863

Epoch 00010: ReduceLROnPlateau reducing learning rate to 0.000699999975040555.
Epoch 10: current LR = 0.000700
Epoch 11/15
100/100 [==============================] - 1862s 19s/step - loss: 1.6940 - rpn_class_loss: 0.1688 - rpn_bbox_loss: 0.4934 - mrcnn_class_loss: 0.2911 - mrcnn_bbox_loss: 0.3538 - mrcnn_mask_loss: 0.3869 - val_loss: 1.4548 - val_rpn_class_loss: 0.1197 - val_rpn_bbox_loss: 0.4423 - val_mrcnn_class_loss: 0.1551 - val_mrcnn_bbox_loss: 0.3560 - val_mrcnn_mask_loss: 0.3817
Epoch 11: current LR = 0.000700
Epoch 12/15
100/100 [==============================] - 1886s 19s/step - loss: 1.6786 - rpn_class_loss: 0.1676 - rpn_bbox_loss: 0.4842 - mrcnn_class_loss: 0.2909 - mrcnn_bbox_loss: 0.3513 - mrcnn_mask_loss: 0.3846 - val_loss: 1.8571 - val_rpn_class_loss: 0.1860 - val_rpn_bbox_loss: 0.4938 - val_mrcnn_class_loss: 0.3450 - val_mrcnn_bbox_loss: 0.4043 - val_mrcnn_mask_loss: 0.4280
Epoch 12: current LR = 0.000700
Epoch 13/15
100/100 [==============================] - 2013s 20s/step - loss: 1.5936 - rpn_class_loss: 0.1570 - rpn_bbox_loss: 0.4572 - mrcnn_class_loss: 0.2759 - mrcnn_bbox_loss: 0.3312 - mrcnn_mask_loss: 0.3724 - val_loss: 2.0003 - val_rpn_class_loss: 0.1854 - val_rpn_bbox_loss: 0.6101 - val_mrcnn_class_loss: 0.3108 - val_mrcnn_bbox_loss: 0.4727 - val_mrcnn_mask_loss: 0.4213

Epoch 00013: ReduceLROnPlateau reducing learning rate to 0.0003499999875202775.
Epoch 13: current LR = 0.000350
Epoch 14/15
100/100 [==============================] - 2189s 22s/step - loss: 1.6182 - rpn_class_loss: 0.1616 - rpn_bbox_loss: 0.4732 - mrcnn_class_loss: 0.2690 - mrcnn_bbox_loss: 0.3384 - mrcnn_mask_loss: 0.3760 - val_loss: 2.0835 - val_rpn_class_loss: 0.2125 - val_rpn_bbox_loss: 0.7165 - val_mrcnn_class_loss: 0.3410 - val_mrcnn_bbox_loss: 0.4165 - val_mrcnn_mask_loss: 0.3970
Epoch 14: current LR = 0.000350
