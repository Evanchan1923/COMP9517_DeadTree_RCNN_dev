
Starting at epoch 10. LR=0.00095

Checkpoint Path: /Users/evanchan19/Desktop/COMP9517/project/logs/usa_rgb20250730T2338/mask_rcnn_usa_rgb_{epoch:04d}.h5
Selecting layers to train
conv1                  (Conv2D)
bn_conv1               (BatchNorm)
res2a_branch2a         (Conv2D)
bn2a_branch2a          (BatchNorm)
res2a_branch2b         (Conv2D)
bn2a_branch2b          (BatchNorm)
res2a_branch2c         (Conv2D)
res2a_branch1          (Conv2D)
bn2a_branch2c          (BatchNorm)
bn2a_branch1           (BatchNorm)
res2b_branch2a         (Conv2D)
bn2b_branch2a          (BatchNorm)
res2b_branch2b         (Conv2D)
bn2b_branch2b          (BatchNorm)
res2b_branch2c         (Conv2D)
bn2b_branch2c          (BatchNorm)
res2c_branch2a         (Conv2D)
bn2c_branch2a          (BatchNorm)
res2c_branch2b         (Conv2D)
bn2c_branch2b          (BatchNorm)
res2c_branch2c         (Conv2D)
bn2c_branch2c          (BatchNorm)
res3a_branch2a         (Conv2D)
bn3a_branch2a          (BatchNorm)
res3a_branch2b         (Conv2D)
bn3a_branch2b          (BatchNorm)
res3a_branch2c         (Conv2D)
res3a_branch1          (Conv2D)
bn3a_branch2c          (BatchNorm)
bn3a_branch1           (BatchNorm)
res3b_branch2a         (Conv2D)
bn3b_branch2a          (BatchNorm)
res3b_branch2b         (Conv2D)
bn3b_branch2b          (BatchNorm)
res3b_branch2c         (Conv2D)
bn3b_branch2c          (BatchNorm)
res3c_branch2a         (Conv2D)
bn3c_branch2a          (BatchNorm)
res3c_branch2b         (Conv2D)
bn3c_branch2b          (BatchNorm)
res3c_branch2c         (Conv2D)
bn3c_branch2c          (BatchNorm)
res3d_branch2a         (Conv2D)
bn3d_branch2a          (BatchNorm)
res3d_branch2b         (Conv2D)
bn3d_branch2b          (BatchNorm)
res3d_branch2c         (Conv2D)
bn3d_branch2c          (BatchNorm)
res4a_branch2a         (Conv2D)
bn4a_branch2a          (BatchNorm)
res4a_branch2b         (Conv2D)
bn4a_branch2b          (BatchNorm)
res4a_branch2c         (Conv2D)
res4a_branch1          (Conv2D)
bn4a_branch2c          (BatchNorm)
bn4a_branch1           (BatchNorm)
res4b_branch2a         (Conv2D)
bn4b_branch2a          (BatchNorm)
res4b_branch2b         (Conv2D)
bn4b_branch2b          (BatchNorm)
res4b_branch2c         (Conv2D)
bn4b_branch2c          (BatchNorm)
res4c_branch2a         (Conv2D)
bn4c_branch2a          (BatchNorm)
res4c_branch2b         (Conv2D)
bn4c_branch2b          (BatchNorm)
res4c_branch2c         (Conv2D)
bn4c_branch2c          (BatchNorm)
res4d_branch2a         (Conv2D)
bn4d_branch2a          (BatchNorm)
res4d_branch2b         (Conv2D)
bn4d_branch2b          (BatchNorm)
res4d_branch2c         (Conv2D)
bn4d_branch2c          (BatchNorm)
res4e_branch2a         (Conv2D)
bn4e_branch2a          (BatchNorm)
res4e_branch2b         (Conv2D)
bn4e_branch2b          (BatchNorm)
res4e_branch2c         (Conv2D)
bn4e_branch2c          (BatchNorm)
res4f_branch2a         (Conv2D)
bn4f_branch2a          (BatchNorm)
res4f_branch2b         (Conv2D)
bn4f_branch2b          (BatchNorm)
res4f_branch2c         (Conv2D)
bn4f_branch2c          (BatchNorm)
res5a_branch2a         (Conv2D)
bn5a_branch2a          (BatchNorm)
res5a_branch2b         (Conv2D)
bn5a_branch2b          (BatchNorm)
res5a_branch2c         (Conv2D)
res5a_branch1          (Conv2D)
bn5a_branch2c          (BatchNorm)
bn5a_branch1           (BatchNorm)
res5b_branch2a         (Conv2D)
bn5b_branch2a          (BatchNorm)
res5b_branch2b         (Conv2D)
bn5b_branch2b          (BatchNorm)
res5b_branch2c         (Conv2D)
bn5b_branch2c          (BatchNorm)
res5c_branch2a         (Conv2D)
bn5c_branch2a          (BatchNorm)
res5c_branch2b         (Conv2D)
bn5c_branch2b          (BatchNorm)
res5c_branch2c         (Conv2D)
bn5c_branch2c          (BatchNorm)
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
Epoch 11/20
100/100 [==============================] - 2149s 21s/step - loss: 1.9851 - rpn_class_loss: 0.2216 - rpn_bbox_loss: 0.5844 - mrcnn_class_loss: 0.3278 - mrcnn_bbox_loss: 0.4307 - mrcnn_mask_loss: 0.4206 - val_loss: 1.8240 - val_rpn_class_loss: 0.2048 - val_rpn_bbox_loss: 0.5262 - val_mrcnn_class_loss: 0.3218 - val_mrcnn_bbox_loss: 0.3743 - val_mrcnn_mask_loss: 0.3969
Epoch 11: current LR = 0.000950
Epoch 12/20
100/100 [==============================] - 3390s 34s/step - loss: 1.9002 - rpn_class_loss: 0.2009 - rpn_bbox_loss: 0.5765 - mrcnn_class_loss: 0.3121 - mrcnn_bbox_loss: 0.4088 - mrcnn_mask_loss: 0.4019 - val_loss: 1.9593 - val_rpn_class_loss: 0.1936 - val_rpn_bbox_loss: 0.6167 - val_mrcnn_class_loss: 0.3185 - val_mrcnn_bbox_loss: 0.4212 - val_mrcnn_mask_loss: 0.4092
Epoch 12: current LR = 0.000950
Epoch 13/20
100/100 [==============================] - 2530s 25s/step - loss: 1.7453 - rpn_class_loss: 0.1753 - rpn_bbox_loss: 0.5005 - mrcnn_class_loss: 0.2916 - mrcnn_bbox_loss: 0.3845 - mrcnn_mask_loss: 0.3934 - val_loss: 1.6841 - val_rpn_class_loss: 0.1279 - val_rpn_bbox_loss: 0.4420 - val_mrcnn_class_loss: 0.2785 - val_mrcnn_bbox_loss: 0.4141 - val_mrcnn_mask_loss: 0.4217
Epoch 13: current LR = 0.000950
Epoch 14/20
100/100 [==============================] - 2005s 20s/step - loss: 1.7602 - rpn_class_loss: 0.1617 - rpn_bbox_loss: 0.5056 - mrcnn_class_loss: 0.3137 - mrcnn_bbox_loss: 0.3888 - mrcnn_mask_loss: 0.3904 - val_loss: 1.7309 - val_rpn_class_loss: 0.1637 - val_rpn_bbox_loss: 0.4673 - val_mrcnn_class_loss: 0.3149 - val_mrcnn_bbox_loss: 0.3989 - val_mrcnn_mask_loss: 0.3860
Epoch 14: current LR = 0.000950
Epoch 15/20
100/100 [==============================] - 2042s 20s/step - loss: 1.7364 - rpn_class_loss: 0.1649 - rpn_bbox_loss: 0.4931 - mrcnn_class_loss: 0.3177 - mrcnn_bbox_loss: 0.3774 - mrcnn_mask_loss: 0.3833 - val_loss: 1.6974 - val_rpn_class_loss: 0.1376 - val_rpn_bbox_loss: 0.5203 - val_mrcnn_class_loss: 0.2892 - val_mrcnn_bbox_loss: 0.3783 - val_mrcnn_mask_loss: 0.3720

Epoch 00015: ReduceLROnPlateau reducing learning rate to 0.00047500000800937414.
Epoch 15: current LR = 0.000475
Epoch 16/20
100/100 [==============================] - 2004s 20s/step - loss: 1.6696 - rpn_class_loss: 0.1472 - rpn_bbox_loss: 0.4857 - mrcnn_class_loss: 0.3000 - mrcnn_bbox_loss: 0.3546 - mrcnn_mask_loss: 0.3822 - val_loss: 2.0471 - val_rpn_class_loss: 0.1900 - val_rpn_bbox_loss: 0.6533 - val_mrcnn_class_loss: 0.3208 - val_mrcnn_bbox_loss: 0.4649 - val_mrcnn_mask_loss: 0.4180
Epoch 16: current LR = 0.000475
Epoch 17/20
100/100 [==============================] - 2001s 20s/step - loss: 1.6172 - rpn_class_loss: 0.1509 - rpn_bbox_loss: 0.4591 - mrcnn_class_loss: 0.2873 - mrcnn_bbox_loss: 0.3448 - mrcnn_mask_loss: 0.3751 - val_loss: 1.8234 - val_rpn_class_loss: 0.1940 - val_rpn_bbox_loss: 0.4995 - val_mrcnn_class_loss: 0.3404 - val_mrcnn_bbox_loss: 0.3923 - val_mrcnn_mask_loss: 0.3973

Epoch 00017: ReduceLROnPlateau reducing learning rate to 0.00023750000400468707.
Epoch 17: current LR = 0.000238
Epoch 18/20
100/100 [==============================] - 2002s 20s/step - loss: 1.5616 - rpn_class_loss: 0.1328 - rpn_bbox_loss: 0.4424 - mrcnn_class_loss: 0.2845 - mrcnn_bbox_loss: 0.3295 - mrcnn_mask_loss: 0.3725 - val_loss: 1.6708 - val_rpn_class_loss: 0.1375 - val_rpn_bbox_loss: 0.4716 - val_mrcnn_class_loss: 0.2752 - val_mrcnn_bbox_loss: 0.4141 - val_mrcnn_mask_loss: 0.3723
Epoch 18: current LR = 0.000238
Epoch 19/20
100/100 [==============================] - 1995s 20s/step - loss: 1.5549 - rpn_class_loss: 0.1424 - rpn_bbox_loss: 0.4285 - mrcnn_class_loss: 0.2878 - mrcnn_bbox_loss: 0.3275 - mrcnn_mask_loss: 0.3686 - val_loss: 1.5307 - val_rpn_class_loss: 0.1117 - val_rpn_bbox_loss: 0.3874 - val_mrcnn_class_loss: 0.2728 - val_mrcnn_bbox_loss: 0.3720 - val_mrcnn_mask_loss: 0.3869
Epoch 19: current LR = 0.000238
Epoch 20/20
100/100 [==============================] - 2001s 20s/step - loss: 1.5130 - rpn_class_loss: 0.1251 - rpn_bbox_loss: 0.4269 - mrcnn_class_loss: 0.2668 - mrcnn_bbox_loss: 0.3228 - mrcnn_mask_loss: 0.3713 - val_loss: 1.8250 - val_rpn_class_loss: 0.1525 - val_rpn_bbox_loss: 0.6644 - val_mrcnn_class_loss: 0.2438 - val_mrcnn_bbox_loss: 0.3735 - val_mrcnn_mask_loss: 0.3908
Epoch 20: current LR = 0.000238
