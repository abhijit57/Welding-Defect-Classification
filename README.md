
# Welding Defect Classification

## 1.	 OBJECTIVE
Some industries employ robotic welding machines to get the required job done. These robotic machines can weld automatically for a lot of hours at a single stretch. No human interventions require in this process; but despite this exciting invention of autonomous weld, there are possibilities of occurrence of defects in the welding done by these machines. Hence it becomes necessary for these defects to be identified immediately. In this project, we will be developing an image classification model which would efficiently identify whether the welding done by the robotic machines are good or defective.

## 2.	 DATASET
The data was collected from Kaggle. It consists of 2 folders: train and test, each containing images of good and bad welding. Going forward, we can also collect weld images from google to test our model accuracy. I am attaching the zip file link to my google drive as the Kaggle link was from a limited competition. So, the raw data can be downloaded from this link below.
•	Link: https://drive.google.com/file/d/1Rnqn6CpbjTNwmqPT1lwB7-Y7B2yWnz9O/view?usp=sharing

## 3.	METHOD
We implemented an image classification model preferably using pre-trained image classification models like ResNet, EfficientNet along with optimization to achieve the above-mentioned objective. These Convolutional Neural Networks (ResNet, EfficientNet) would have been previously trained on the ImageNet database. Before this, we pre-processed the images with steps like compression, resizing, augmentation (rotation, flip, changing brightness, exposure, and saturation) to create more training data for the model to generalize even better.

## 4.	EXPECTED RESULT
Once the model was trained, it gave us binary predictions on test (unseen) images with classes such as good welding and bad welding. The model's performance was evalauted with it's prediction accuracy. These binary inferences could then prove useful in the further stages.
