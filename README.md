# detect-various-Task-Description-classes-from-a-soccer-video-match


In this experiment, we applied the DETR (Detection Transformer) model to an original dataset without remapping the annotations to classes 0:5 and without merging the left and right teams. The primary objective was to evaluate the model's performance using the COCO (Common Objects in Context) format, which is suitable for the DETR model. We transformed the dataset from YOLO format to COCO format and investigated the model's ability to differentiate between 7 classes.

Methodology
Dataset Preparation: The original dataset, containing annotations for various classes, was used as-is without any modifications to the class mapping or team merging.

Format Conversion: We converted the dataset from YOLO format to COCO format. The COCO format is well-suited for the DETR model, facilitating seamless integration and evaluation.

DETR Model: We employed the DETR model for object detection on the prepared dataset. The DETR model utilizes a transformer-based architecture, which allows for efficient detection of objects in images.

Results
The results obtained from applying the DETR model to the original dataset were mixed. While the model displayed promising results in detecting objects across the 7 different classes present in the dataset, its performance was not consistently optimal. The model demonstrated the ability to differentiate between the diverse classes and produced satisfactory detection outcomes in some instances. However, it is important to note that the model's performance varied, and it did not consistently achieve high accuracy across all scenarios.

