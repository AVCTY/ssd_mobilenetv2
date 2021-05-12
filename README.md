# inference_saved_model
Run tensorflow object detection from saved model

The folders in here are the saved model and validation images for the object detection model.

How To Use:
Clone the repo into the python notebook and replace the fine_tuned_model folder with the one provided in this repo.
Run the model with the validation images to see the object detection.

Model used: ssd mobilenet v2
Number of steps: 20,000
Number of eval steps: 50
Batch size: 8
IOU threshold: 0.50
