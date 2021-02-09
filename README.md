# Object-Detection-with-Pre-trained-YOLO


In  this  project,  YOLOv3  (You  Only  Look  Once)  algorithm  trained  on  the  COCO dataset was implemented to detect objects from an image. YOLOv3 generates bounding boxes as the predicted output across 3 different scales;  at each scale, each grid cell predicts  3  bounding  boxes  using  3  anchors.   In  the  first  stage,  all  the  bounding boxes below a confidence threshold value are filtered out.  The redundant overlapping bounding boxes are eliminated by applying Non-maximum Suppression (NMS) technique.
