
1.	 OBJECTIVE
Some industries employ robotic welding machines to get the required job done. These robotic machines can weld automatically for a lot of hours at a single stretch. No human interventions require in this process; but despite this exciting invention of autonomous weld, there are possibilities of occurrence of defects in the welding done by these machines. Hence it becomes necessary for these defects to be identified immediately. In this project, we will be developing an image classification model which would efficiently identify whether the welding done by the robotic machines are good or defective.
2.	 DATASET
The data will be collected from Kaggle. It consists of 2 folders: train and test, each containing images of good and bad welding. Going forward, we can also collect weld images from google to test our model accuracy.
•	Source: https://www.kaggle.com/datasets/prataproychoudhury/weld-classification
3.	METHOD
We will be implementing an image classification model preferably using pre-trained image classification models like ResNet, EfficientNet along with optimization to achieve the above-mentioned objective. These Convolutional Neural Networks (ResNet, EfficientNet) would have been previously trained on the ImageNet database. Before this, we would be pre-processing the images with steps like compression, resizing, augmentation (rotation, flip, changing brightness, exposure, and saturation) to create more training data for the model to generalize even better. Finally, we will verify our model’s performance with some evaluation metrics at place like F1-Score.
4.	EXPECTED RESULT
Once the model is trained, it would give us binary predictions on test (unseen) images with classes such as good welding and bad welding. The prediction performance will also be verified with an F1-Score. These binary inferences could then prove useful in the further stages.
