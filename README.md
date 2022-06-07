# The machine learning part required by the Rebage application

<p align="center" ><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ab/TensorFlow_logo.svg/512px-TensorFlow_logo.svg.png?20211220215155" width="325"/> </p>

## To perform object detection, we conducted experiments to learn how to create bounding boxes and also perform dataset creation.

-   ObjectDetectionBoundingBox : https://github.com/KrisnaPinasthika/ObjectDetectionBoundingBox

## Reference dataset:

-   https://www.kaggle.com/datasets/arkadiyhacks/drinking-waste-classification
-   https://www.kaggle.com/datasets/deadskull7/cola-bottle-identification
-   https://www.kaggle.com/datasets/moezabid/bottles-and-cans
-   Creating datasets manually by taking photos through a smartphone camera

## Object label to be detected and classified

1. glass bottle
2. plastic bottles
3. cans
4. cardboard
5. rubber
6. paper
7. plastic
8. straws

## Documentation:

1. Looking for references and creating datasets manually by taking photos through a smartphone camera
2. Provide a bounding box and label for each data
3. Perform analysis for each image that has been given a bounding box
4. Divide the data in a ratio of 80 (train) and 10 (test)
5. Create TFRecord for train and test data
6. Experiment for freezing layer on feature extractor section of MobileNet v2 architecture
7. Augmenting image data
8. Tuning hyperparameter
9. Conduct machine learning model training experiments with 50,000 to 75,000 train steps
10. Evaluate the model
11. Testing real data using real photos
12. Testing real data using a webcam
13. Save the model by changing the input to base64
14. Deploy the model to Vertex AI
