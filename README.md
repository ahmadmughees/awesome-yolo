# awesome-yolo :rocket: :star:


# Object Detection DNN Algorithms

**Most of the DNN object detection algorithm can:**
- classifies object
- localize object (find the coordinates of the bounding box enclosing the object)

# YOLO - You Only Looks Once
- **Yolo v1** (2016) Joseph Redmon [‘You Only Look Once: Unified, Real-Time Object Detection’](https://arxiv.org/abs/1506.02640)
- [**Yolo v2**](https://github.com/longcw/yolo2-pytorch) (2017) Joseph Redmon [‘YOLO9000: Better, Faster, Stronger’](https://arxiv.org/abs/1612.08242)
- [**Yolo v3**](https://github.com/ultralytics/yolov3) (2018) Joseph Redmon [‘YOLOv3: An Incremental Improvement’](https://arxiv.org/abs/1804.02767)
- [**Yolo v4**](https://github.com/AlexeyAB/darknet) (2020) Alexey Bochkovskiy [‘YOLOv4: Optimal Speed and Accuracy of Object Detection’](https://arxiv.org/abs/2004.10934). AP increase by 10% and FPS by 12% compared to v3
- [**Yolo v5**](https://github.com/ultralytics/yolov5) (2020) Glen Jocher - PyTorch implementation (v1 to v4 Darknet implementation). The major improvements includes mosaic data augmentation and auto learning bounding box anchors
- [**PP-Yolo**](https://github.com/PaddlePaddle/PaddleDetection) (2020) Xiang Long et al.(Baidu) [‘PP-YOLO: An Effective and Efficient Implementation of Object Detector’](https://arxiv.org/abs/2007.12099). PP-YOLO is based on v3 model with replacement of Darknet 53 backbone of YOLO v3 with a ResNet backbone and increase of training batch size from 64 to 192. Improved mAP to 45.2% (from 43.5 for v4) and FPS from 65 to 73 for Tesla V100 (batch size = 1). Based on PaddlePaddle DL framework
- **Yolo Z** (2021) Aduen Benjumea et al. [‘YOLO-Z: Improving small object detection in YOLOv5 for autonomous vehicles’](https://arxiv.org/abs/2112.11798v2)
- [**Yolo-ReT**](https://github.com/guotao0628/yoloret) (2021) Prakhar Ganesh et al. [‘YOLO-ReT: Towards High Accuracy Real-time Object Detection on Edge GPUs’](https://arxiv.org/abs/2110.13713)
- [**Scaled-Yolo v4**](https://github.com/WongKinYiu/ScaledYOLOv4) (2021) Chien-Yao Wang et al. ['Scaled-YOLOv4: Scaling Cross Stage Partial Network'](https://arxiv.org/abs/2011.08036)
- [**YoloX**](https://github.com/Megvii-BaseDetection/YOLOX) (2021) Zheng Ge at all. [‘YOLOX: Exceeding YOLO Series in 2021’](https://arxiv.org/abs/2107.08430). Good for edge devices. YOLOX-Tiny and YOLOX-Nano outperform YOLOv4-Tiny and NanoDet offering a boost of 10.1% and 1.8% respectively
- [**YoloR**](https://github.com/WongKinYiu/yolor) (You Only Learn One) (2021) Chien-Yao Wang et al. [‘You Only Learn One Representation: Unified Network for Multiple Tasks’](https://arxiv.org/abs/2105.04206)
- [**YoloS**](https://github.com/hustvl/YOLOShttps://github.com/hustvl/YOLOS) (2021) Yuxin Fang at all. ['You Only Look at One Sequence: Rethinking Transformer in Vision through Object Detection'](https://arxiv.org/abs/2106.00666v3)
- [**YoloF**](https://github.com/megvii-model/YOLOF) (2021) Qiang Chen at all. ['You Only Look One-level Feature'](https://arxiv.org/abs/2103.09460) 
- [**YoloP**](https://github.com/hustvl/YOLOP) (2022-v7) Dong Wu at all. [‘YOLOP: You Only Look Once for Panoptic Driving Perception’](https://arxiv.org/abs/2108.11250). YoloP was designed to perform three visual perception tasks: traffic object detection, drivable area segmentation and lane detection simultaneously in real-time on an embedded device (Jetson TX2, 23 FPS). It is based on one encoder for feature extraction and three decoders to handle the specific tasks
- [**Yolov6**](https://github.com/meituan/YOLOv6) (2022) Hardware-friendly design for backbone and neck, efficient Decoupled Head with SIoU Loss,
- [**Yolov7 not official**](https://github.com/jinfagang/yolov7) (2022) A simple and standard training framework with Transformers for any detection && instance segmentation tasks, based on detectron2,
- [**Yolov7 official**](https://github.com/WongKinYiu/yolov77) (2022) Chien-Yao Wang at all. ['Trainable bag-of-freebies sets new state-of-the-art for real-time object detectors'](https://arxiv.org/abs/2207.02696) YOLOv7 currently outperforms all known real-time object detectors with 30 FPS or higher on GPU V100. YOLOv7-E6 object detector (56 FPS V100, 55.9% AP),
- [**DAMO-YOLO**](https://github.com/tinyvision/DAMO-YOLO) (2022) Xianzhe Xu at all. ['A Report on Real-Time Object Detection Design'](https://arxiv.org/abs/2211.15444v2) DAMO-YOLO including Neural Architecture Search (NAS), efficient Reparameterized Generalized-FPN (RepGFPN), a lightweight head with AlignedOTA label assignment, and distillation enhancement,
- [**EdgeYOLO**](https://github.com/LSH9832/edgeyolo) (2023) Shihan Liu at all. ['EdgeYOLO: An Edge-Real-Time Object Detector'](https://arxiv.org/abs/2302.07483) EdgeYOLO model accuracy of 50.6% AP50:95 and 69.8% AP50 in MS COCO2017 dataset, 26.4% AP50:95 and 44.8% AP50 in VisDrone2019-DET dataset, FPS>=30 on edge-computing device Nvidia Jetson AGX Xavier,
- [**Yolov8**](https://github.com/ultralytics/ultralytics) (2023) developed by Ultralytics,
- [**Yolov6 v3.0**](https://github.com/meituan/YOLOv6) (2023) Chuyi Li at all. ['YOLOv6 v3.0: A Full-Scale Reloading'](https://arxiv.org/abs/2301.05586v1) YOLOv6-N hits 37.5% AP on the COCO dataset at a throughput of 1187 FPS tested with an NVIDIA Tesla T4 GPU.
- [**Yolo-NAS**](https://github.com/Deci-AI/super-gradients) (2023) Deci-AI. They used their proprietary Neural Architecture Search (AutoNAC) to find and optimize a new Deep Learning Architecture Yolo-NAS: number and sizes of the stages, blocks, channels. Using quantization-aware “QSP” and “QCI” modules consisting of QA-RepVGG blocks provide 8-bit quantization and ensuring that model architecture would be compatible with Post-Training Quantization (PTQ) - giving minimal accuracy loss during PTQ. Yolo-NAS also use hybrid quantization method that selectively quantizes specific layers to optimize accuracy and latency tradeoffs as well as the attention mechanism and inference time reparametrization to enhance detection capabilities. Pre-trained weights are available for research use (non-commercial) on SuperGradients, Deci’s PyTorch-based, open-source CV library.
# Object Detection DNN Algorithms Benchmark

- [Real-Time Object Detection on COCO - **Mean Average Precission (MAP)**](https://paperswithcode.com/sota/real-time-object-detection-on-coco) - YOLOv6-L6
- [Real-Time Object Detection on COCO - **Speed FPS**](https://paperswithcode.com/sota/real-time-object-detection-on-coco?metric=FPS%20(V100%2C%20b%3D1)) - 	
DAMO-YOLO-T
- [Object Detection on COCO - **Mean Average Precission (MAP)**](https://paperswithcode.com/sota/object-detection-on-coco) - Co-DETR

# Key parameters of object detection algorithms
- **Accuracy (A)** = (Number of Correct Predictions) / (Total Number of Predictions)
   - Accuracy measures the overall correctness of the algorithm's predictions.
- **Precision (P)** = (True Positives) / (True Positives + False Positives)
   -  It quantifies the algorithm's ability not to label false positives. It measures the fraction of correctly predicted positive instances among all predicted positive instances.
- **Recall (R)** = (True Positives) / (True Positives + False Negatives)
   - It quantifies the algorithm's ability to find all positive instances.
- **F1 Score (F1)** = 2 * (Precision * Recall) / (Precision + Recall)
   - F1 score providing a balanced measure of the algorithm's performance, it is the harmonic mean of precision and recall.
- **Average Precision (AP)** = ∑(P_i) * ΔR_i
  - P_i is the precision value at the i-th recall point.
  - ΔR_i is the change in recall from the i-th to the (i+1)-th recall point
  - AP summarizes the performance of an algorithm across different confidence thresholds
  - It quantifies the precision-recall trade-off for a given class
- **Mean Average Precision (mAP)** = (AP_1 + AP_2 + AP_3 + ... + AP_n) / n
  - AP_1, AP_2, ..., AP_n are the Average Precision values for each class
  - n is the total number of classes
- **Intersection over Union (IoU)** = (Area of Intersection) / (Area of Union)
  -  It is used to determine the accuracy of localization, it measures the overlap between predicted bounding boxes and ground truth bounding boxes
- **Inference Time** - time taken to make predictions on a single input image
  - It measures the time it takes for the algorithm to process the input and produce the output (bounding boxes, class predictions) without considering any external factors. 
- **Processing Speed (FPS)** - time taken by the algorithm to process a given dataset or a single image.
  - Often represented as FPS - Frames Per Second, number of frames (or images) that the algorithm can process per second
  - It takes into account factors such as data loading, pre-processing, and post-processing steps in addition to the inference time.
- **Number of Parameters**
  - The number of model parameters indicates the model's complexity and memory requirements.
- **Memory Usage**
  - It measures the amount of memory consumed by the algorithm during inference. 

# Tests and comparisons of models
[![**Yolo v6 vs Yolo v8**](https://img.youtube.com/vi/hG6kQHeMyz0/0.jpg)](https://youtu.be/hG6kQHeMyz0)
[![**Yolo v8**](https://img.youtube.com/vi/5jEuWE1Z5Po/0.jpg)](https://www.youtube.com/watch?v=5jEuWE1Z5Po)
[![**Yolo v7**](https://img.youtube.com/vi/2NRuwKj2HL8/0.jpg)](https://www.youtube.com/watch?v=2NRuwKj2HL8)
[![**YoloR vs YoloX**](https://img.youtube.com/vi/Qm3GTj2I_Kk/0.jpg)](https://www.youtube.com/watch?v=Qm3GTj2I_Kk)
[![**Yolo_v5 vs YoloX**](https://img.youtube.com/vi/V6wIxnfOJCs/0.jpg)](https://www.youtube.com/watch?v=V6wIxnfOJCs)
[![**YoloX**](https://img.youtube.com/vi/m7yRGpjiatM/0.jpg)](https://www.youtube.com/watch?v=m7yRGpjiatM)

# Practical application examples
[![**Counting Tree Logs by Size**](https://img.youtube.com/vi/AocLsvLPAqk/0.jpg)](https://www.youtube.com/watch?v=AocLsvLPAqk)
[![**Pipe Counting**](https://img.youtube.com/vi/4ONcSj6-S8k/0.jpg)](https://www.youtube.com/watch?v=4ONcSj6-S8k)
