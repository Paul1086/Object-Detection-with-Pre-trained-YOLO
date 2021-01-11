# Object-Detection-with-Pre-trained-YOLO


In  this  project,  YOLOv3  (You  Only  Look  Once)  algorithm  trained  on  the  COCOdataset was implemented to detect objects from an image. YOLOv3 generates boundingboxes as the predicted output across 3 different scales;  at each scale, each grid cellpredicts  3  bounding  boxes  using  3  anchors.   In  the  first  stage,  all  the  boundingboxes below a confidence threshold value are filtered out.  The redundant overlappingbounding boxes are eliminated by applying Non-maximum Suppression (NMS) technique.
