
Public Pre-Trained Models
=========================

.. |rocket| image:: ../../images/rocket.png
  :width: 18

.. |star| image:: ../../images/star.png
  :width: 18

Here, we give the full list of publicly pre-trained models supported by the Hailo Model Zoo.

* Network available in `Hailo Benchmark <https://hailo.ai/products/ai-accelerators/hailo-8l-ai-accelerator-for-ai-light-applications/#hailo8l-benchmarks/>`_ are marked with |rocket|
* Networks available in `TAPPAS <https://github.com/hailo-ai/tappas>`_ are marked with |star|
* Benchmark and TAPPAS  networks run in performance mode
* All models were compiled using Hailo Dataflow Compiler v3.29.0



.. _Object Detection:

----------------

COCO
^^^^

.. list-table::
   :widths: 31 9 7 11 9 8 8 8 7 7 7
   :header-rows: 1

   * - Network Name
     - mAP
     - HW Accuracy
     - FPS (Batch Size=1)
     - FPS (Batch Size=8)
     - Input Resolution (HxWxC)
     - Params (M)
     - OPS (G)
     - Pretrained
     - Source
     - Compiled    
   * - centernet_resnet_v1_18_postprocess   
     - 26.37
     - 25.04
     - 79
     - 121
     - 512x512x3
     - 14.22
     - 31.21
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/centernet/centernet_resnet_v1_18/pretrained/2023-07-18/centernet_resnet_v1_18.zip>`_
     - `link <https://cv.gluon.ai/model_zoo/detection.html>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/centernet_resnet_v1_18_postprocess.hef>`_    
   * - centernet_resnet_v1_50_postprocess   
     - 31.77
     - 29.4
     - 52
     - 81
     - 512x512x3
     - 30.07
     - 56.92
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/centernet/centernet_resnet_v1_50_postprocess/pretrained/2023-07-18/centernet_resnet_v1_50_postprocess.zip>`_
     - `link <https://cv.gluon.ai/model_zoo/detection.html>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/centernet_resnet_v1_50_postprocess.hef>`_    
   * - damoyolo_tinynasL20_T   
     - 42.8
     - 42.29
     - 93
     - 175
     - 640x640x3
     - 11.35
     - 18.02
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/damoyolo_tinynasL20_T/pretrained/2022-12-19/damoyolo_tinynasL20_T.zip>`_
     - `link <https://github.com/tinyvision/DAMO-YOLO>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/damoyolo_tinynasL20_T.hef>`_    
   * - damoyolo_tinynasL25_S   
     - 46.53
     - 45.33
     - 76
     - 147
     - 640x640x3
     - 16.25
     - 37.64
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/damoyolo_tinynasL25_S/pretrained/2022-12-19/damoyolo_tinynasL25_S.zip>`_
     - `link <https://github.com/tinyvision/DAMO-YOLO>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/damoyolo_tinynasL25_S.hef>`_    
   * - damoyolo_tinynasL35_M   
     - 49.7
     - 47.64
     - 31
     - 55
     - 640x640x3
     - 33.98
     - 61.64
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/damoyolo_tinynasL35_M/pretrained/2022-12-19/damoyolo_tinynasL35_M.zip>`_
     - `link <https://github.com/tinyvision/DAMO-YOLO>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/damoyolo_tinynasL35_M.hef>`_    
   * - detr_resnet_v1_18_bn   
     - 33.91
     - 31.7
     - 18
     - 39
     - 800x800x3
     - 32.42
     - 61.87
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/detr/detr_resnet_v1_18/2022-09-18/detr_resnet_v1_18_bn.zip>`_
     - `link <https://github.com/facebookresearch/detr>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/detr_resnet_v1_18_bn.hef>`_    
   * - detr_resnet_v1_50   
     - 35.38
     - 34.86
     - 7
     - 10
     - 800x800x3
     - 41.1
     - 120.4
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/detr/detr_resnet_v1_50/2024-03-05/detr_resnet_v1_50.zip>`_
     - `link <https://github.com/facebookresearch/detr>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/detr_resnet_v1_50.hef>`_    
   * - efficientdet_lite0   
     - 27.32
     - 26.49
     - 74
     - 182
     - 320x320x3
     - 3.56
     - 1.94
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/efficientdet/efficientdet_lite0/pretrained/2023-04-25/efficientdet-lite0.zip>`_
     - `link <https://github.com/google/automl/tree/master/efficientdet>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/efficientdet_lite0.hef>`_    
   * - efficientdet_lite1   
     - 32.27
     - 31.82
     - 45
     - 95
     - 384x384x3
     - 4.73
     - 4
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/efficientdet/efficientdet_lite1/pretrained/2023-04-25/efficientdet-lite1.zip>`_
     - `link <https://github.com/google/automl/tree/master/efficientdet>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/efficientdet_lite1.hef>`_    
   * - efficientdet_lite2   
     - 35.95
     - 34.75
     - 26
     - 48
     - 448x448x3
     - 5.93
     - 6.84
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/efficientdet/efficientdet_lite2/pretrained/2023-04-25/efficientdet-lite2.zip>`_
     - `link <https://github.com/google/automl/tree/master/efficientdet>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/efficientdet_lite2.hef>`_     
   * - nanodet_repvgg  |star| 
     - 29.3
     - 28.57
     - 176
     - 321
     - 416x416x3
     - 6.74
     - 11.28
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/nanodet/nanodet_repvgg/pretrained/2024-11-01/nanodet.zip>`_
     - `link <https://github.com/RangiLyu/nanodet>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/nanodet_repvgg.hef>`_    
   * - nanodet_repvgg_a12   
     - 33.73
     - 31.8
     - 110
     - 171
     - 640x640x3
     - 5.13
     - 28.23
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/nanodet/nanodet_repvgg_a12/pretrained/2024-01-31/nanodet_repvgg_a12_640x640.zip>`_
     - `link <https://github.com/Megvii-BaseDetection/YOLOX>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/nanodet_repvgg_a12.hef>`_    
   * - nanodet_repvgg_a1_640   
     - 33.28
     - 32.94
     - 83
     - 119
     - 640x640x3
     - 10.79
     - 42.8
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/nanodet/nanodet_repvgg_a1_640/pretrained/2024-01-25/nanodet_repvgg_a1_640.zip>`_
     - `link <https://github.com/RangiLyu/nanodet>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/nanodet_repvgg_a1_640.hef>`_       
   * - ssd_mobilenet_v1 |rocket| |star| 
     - 23.19
     - 22.41
     - 367
     - 367
     - 300x300x3
     - 6.79
     - 2.5
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/ssd/ssd_mobilenet_v1/pretrained/2023-07-18/ssd_mobilenet_v1.zip>`_
     - `link <https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf1_detection_zoo.md>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/ssd_mobilenet_v1.hef>`_    
   * - ssd_mobilenet_v2   
     - 24.18
     - 22.97
     - 109
     - 241
     - 300x300x3
     - 4.46
     - 1.52
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/ssd/ssd_mobilenet_v2/pretrained/2023-03-16/ssd_mobilenet_v2.zip>`_
     - `link <https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf1_detection_zoo.md>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/ssd_mobilenet_v2.hef>`_      
   * - tiny_yolov3 |rocket|  
     - 14.66
     - 14.36
     - 899
     - 899
     - 416x416x3
     - 8.85
     - 5.58
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/tiny_yolov3/pretrained/2021-07-11/tiny_yolov3.zip>`_
     - `link <https://github.com/Tianxiaomo/pytorch-YOLOv4>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/tiny_yolov3.hef>`_    
   * - tiny_yolov4   
     - 19.18
     - 17.72
     - 474
     - 474
     - 416x416x3
     - 6.05
     - 6.92
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/tiny_yolov4/pretrained/2023-07-18/tiny_yolov4.zip>`_
     - `link <https://github.com/Tianxiaomo/pytorch-YOLOv4>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/tiny_yolov4.hef>`_    
   * - yolov10b   
     - 52.0
     - 50.82
     - 23
     - 39
     - 640x640x3
     - 20.15
     - 92.09
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov10b/pretrained/2024-07-02/yolov10b.zip>`_
     - `link <https://github.com/THU-MIG/yolov10>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov10b.hef>`_    
   * - yolov10n   
     - 38.5
     - 36.59
     - 126
     - 280
     - 640x640x3
     - 2.3
     - 6.8
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov10n/pretrained/2024-05-31/yolov10n.zip>`_
     - `link <https://github.com/THU-MIG/yolov10>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov10n.hef>`_    
   * - yolov10s   
     - 45.86
     - 45.05
     - 63
     - 127
     - 640x640x3
     - 7.2
     - 21.7
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov10s/pretrained/2024-05-31/yolov10s.zip>`_
     - `link <https://github.com/THU-MIG/yolov10>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov10s.hef>`_    
   * - yolov10x   
     - 53.7
     - 51.84
     - 11
     - 18
     - 640x640x3
     - 31.72
     - 160.56
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov10x/pretrained/2024-07-02/yolov10x.zip>`_
     - `link <https://github.com/THU-MIG/yolov10>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov10x.hef>`_    
   * - yolov3   
     - 38.42
     - 38.41
     - 15
     - 19
     - 608x608x3
     - 68.79
     - 158.10
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov3/pretrained/2021-08-16/yolov3.zip>`_
     - `link <https://github.com/AlexeyAB/darknet>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov3.hef>`_    
   * - yolov3_416   
     - 37.73
     - 37.62
     - 25
     - 38
     - 416x416x3
     - 61.92
     - 65.94
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov3_416/pretrained/2021-08-16/yolov3_416.zip>`_
     - `link <https://github.com/AlexeyAB/darknet>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov3_416.hef>`_    
   * - yolov3_gluon   
     - 37.28
     - 35.76
     - 16
     - 21
     - 608x608x3
     - 68.79
     - 140.7
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov3_gluon/pretrained/2023-07-18/yolov3_gluon.zip>`_
     - `link <https://cv.gluon.ai/model_zoo/detection.html>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov3_gluon.hef>`_    
   * - yolov3_gluon_416   
     - 36.27
     - 34.25
     - 25
     - 38
     - 416x416x3
     - 61.92
     - 65.94
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov3_gluon_416/pretrained/2023-07-18/yolov3_gluon_416.zip>`_
     - `link <https://cv.gluon.ai/model_zoo/detection.html>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov3_gluon_416.hef>`_    
   * - yolov4_leaky   
     - 42.37
     - 41.19
     - 21
     - 31
     - 512x512x3
     - 64.33
     - 91.04
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov4/pretrained/2022-03-17/yolov4.zip>`_
     - `link <https://github.com/AlexeyAB/darknet/wiki/YOLOv4-model-zoo>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov4_leaky.hef>`_    
   * - yolov5m   
     - 42.59
     - 41.29
     - 45
     - 72
     - 640x640x3
     - 21.78
     - 52.17
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov5m_spp/pretrained/2023-04-25/yolov5m.zip>`_
     - `link <https://github.com/ultralytics/yolov5/releases/tag/v2.0>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov5m.hef>`_    
   * - yolov5m6_6.1   
     - 50.68
     - 49.35
     - 15
     - 19
     - 1280x1280x3
     - 35.70
     - 200.04
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov5m6_6.1/pretrained/2023-04-25/yolov5m6.zip>`_
     - `link <https://github.com/ultralytics/yolov5/releases/tag/v6.1>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov5m6_6.1.hef>`_    
   * - yolov5m_6.1   
     - 44.74
     - 43.47
     - 52
     - 82
     - 640x640x3
     - 21.17
     - 48.96
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov5m_6.1/pretrained/2023-04-25/yolov5m_6.1.zip>`_
     - `link <https://github.com/ultralytics/yolov5/releases/tag/v6.1>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov5m_6.1.hef>`_     
   * - yolov5m_wo_spp  |star| 
     - 43.06
     - 41.5
     - 49
     - 77
     - 640x640x3
     - 22.67
     - 52.88
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov5m/pretrained/2023-04-25/yolov5m_wo_spp.zip>`_
     - `link <https://github.com/ultralytics/yolov5/releases/tag/v2.0>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov5m_wo_spp.hef>`_    
   * - yolov5s   
     - 35.33
     - 34.08
     - 93
     - 167
     - 640x640x3
     - 7.46
     - 17.44
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov5s_spp/pretrained/2023-04-25/yolov5s.zip>`_
     - `link <https://github.com/ultralytics/yolov5/releases/tag/v2.0>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov5s.hef>`_    
   * - yolov5s_c3tr   
     - 37.13
     - 35.68
     - 89
     - 163
     - 640x640x3
     - 10.29
     - 17.02
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov5s_c3tr/pretrained/2023-04-25/yolov5s_c3tr.zip>`_
     - `link <https://github.com/ultralytics/yolov5/tree/v6.0>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov5s_c3tr.hef>`_    
   * - yolov5s_wo_spp   
     - 34.79
     - 33.88
     - 107
     - 195
     - 640x640x3
     - 7.85
     - 17.74
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov5s/pretrained/2023-04-25/yolov5s.zip>`_
     - `link <https://github.com/ultralytics/yolov5/releases/tag/v2.0>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov5s_wo_spp.hef>`_    
   * - yolov5xs_wo_spp   
     - 33.18
     - 32.23
     - 138
     - 299
     - 512x512x3
     - 7.85
     - 11.36
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov5xs/pretrained/2023-04-25/yolov5xs.zip>`_
     - `link <https://github.com/ultralytics/yolov5/releases/tag/v2.0>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov5xs_wo_spp.hef>`_    
   * - yolov5xs_wo_spp_nms_core   
     - 32.73
     - 31.75
     - 138
     - 299
     - 512x512x3
     - 7.85
     - 11.36
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov5xs/pretrained/2022-05-10/yolov5xs_wo_spp_nms.zip>`_
     - `link <https://github.com/ultralytics/yolov5/releases/tag/v2.0>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov5xs_wo_spp_nms_core.hef>`_    
   * - yolov6n   
     - 34.29
     - 32.48
     - 355
     - 355
     - 640x640x3
     - 4.32
     - 11.12
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov6n/pretrained/2023-05-31/yolov6n.zip>`_
     - `link <https://github.com/meituan/YOLOv6/releases/tag/0.1.0>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov6n.hef>`_    
   * - yolov6n_0.2.1   
     - 35.16
     - 33.98
     - 160
     - 339
     - 640x640x3
     - 4.33
     - 11.06
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov6n_0.2.1/pretrained/2023-04-17/yolov6n_0.2.1.zip>`_
     - `link <https://github.com/meituan/YOLOv6/releases/tag/0.2.1>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov6n_0.2.1.hef>`_    
   * - yolov6n_0.2.1_nms_core   
     - 35.16
     - 34.05
     - 69
     - 120
     - 640x640x3
     - 4.32
     - 11.12
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov6n_0.2.1/pretrained/2023-04-17/yolov6n_0.2.1.zip>`_
     - `link <https://github.com/meituan/YOLOv6/releases/tag/0.2.1>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov6n_0.2.1_nms_core.hef>`_    
   * - yolov7   
     - 50.6
     - 48.75
     - 25
     - 35
     - 640x640x3
     - 36.91
     - 104.51
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov7/pretrained/2023-04-25/yolov7.zip>`_
     - `link <https://github.com/WongKinYiu/yolov7>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov7.hef>`_    
   * - yolov7_tiny   
     - 37.07
     - 36.28
     - 115
     - 197
     - 640x640x3
     - 6.22
     - 13.74
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov7_tiny/pretrained/2023-04-25/yolov7_tiny.zip>`_
     - `link <https://github.com/WongKinYiu/yolov7>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov7_tiny.hef>`_    
   * - yolov7e6   
     - 55.37
     - 53.69
     - 4
     - 5
     - 1280x1280x3
     - 97.20
     - 515.12
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov7e6/pretrained/2023-04-25/yolov7-e6.zip>`_
     - `link <https://github.com/WongKinYiu/yolov7>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov7e6.hef>`_    
   * - yolov8l   
     - 52.44
     - 51.78
     - 19
     - 27
     - 640x640x3
     - 43.7
     - 165.3
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov8l/2023-02-02/yolov8l.zip>`_
     - `link <https://github.com/ultralytics/ultralytics>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov8l.hef>`_     
   * - yolov8m  |star| 
     - 49.91
     - 49.11
     - 38
     - 60
     - 640x640x3
     - 25.9
     - 78.93
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov8m/2023-02-02/yolov8m.zip>`_
     - `link <https://github.com/ultralytics/ultralytics>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov8m.hef>`_    
   * - yolov8n   
     - 37.02
     - 36.43
     - 182
     - 464
     - 640x640x3
     - 3.2
     - 8.74
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov8n/2023-01-30/yolov8n.zip>`_
     - `link <https://github.com/ultralytics/ultralytics>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov8n.hef>`_    
   * - yolov8s   
     - 44.58
     - 43.9
     - 88
     - 151
     - 640x640x3
     - 11.2
     - 28.6
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov8s/2023-02-02/yolov8s.zip>`_
     - `link <https://github.com/ultralytics/ultralytics>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov8s.hef>`_    
   * - yolov8x   
     - 53.45
     - 52.92
     - 11
     - 14
     - 640x640x3
     - 68.2
     - 258
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov8x/2023-02-02/yolov8x.zip>`_
     - `link <https://github.com/ultralytics/ultralytics>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov8x.hef>`_    
   * - yolov9c   
     - 52.6
     - 51.25
     - 18
     - 27
     - 640x640x3
     - 25.3
     - 102.1
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolov9c/pretrained/2024-02-24/yolov9c.zip>`_
     - `link <https://github.com/WongKinYiu/yolov9>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolov9c.hef>`_     
   * - yolox_l_leaky  |star| 
     - 48.68
     - 46.53
     - 20
     - 27
     - 640x640x3
     - 54.17
     - 155.3
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolox_l_leaky/pretrained/2023-05-31/yolox_l_leaky.zip>`_
     - `link <https://github.com/Megvii-BaseDetection/YOLOX>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolox_l_leaky.hef>`_    
   * - yolox_s_leaky   
     - 38.13
     - 37.31
     - 107
     - 216
     - 640x640x3
     - 8.96
     - 26.74
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolox_s_leaky/pretrained/2023-05-31/yolox_s_leaky.zip>`_
     - `link <https://github.com/Megvii-BaseDetection/YOLOX>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolox_s_leaky.hef>`_    
   * - yolox_s_wide_leaky   
     - 42.0
     - 40.0
     - 49
     - 70
     - 640x640x3
     - 20.12
     - 59.46
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolox_s_wide_leaky/pretrained/2023-05-31/yolox_s_wide_leaky.zip>`_
     - `link <https://github.com/Megvii-BaseDetection/YOLOX>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolox_s_wide_leaky.hef>`_    
   * - yolox_tiny   
     - 32.64
     - 31.39
     - 155
     - 334
     - 416x416x3
     - 5.05
     - 6.44
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ObjectDetection/Detection-COCO/yolo/yolox/yolox_tiny/pretrained/2023-05-31/yolox_tiny.zip>`_
     - `link <https://github.com/Megvii-BaseDetection/YOLOX>`_
     - `download <https://hailo-model-zoo.s3.eu-west-2.amazonaws.com/ModelZoo/Compiled/v2.13.0/hailo8l/yolox_tiny.hef>`_
