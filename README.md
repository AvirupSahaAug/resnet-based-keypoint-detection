# Resnet-based-keypoint-detection
Pytorch deep learning model that uses deep learning to detect the 17 keypoints in human bodies although not optimized for hidden features or out of frame features , it is supposed to be the second stage in a two stage keypoint detection model
keypoint are sent throug a gaussial blur for the model to process things more easily
eg output(Note that this model was only run for 3 or 4 epochs because it was taking hours for one epoch )
![output heatmap examples](https://github.com/user-attachments/assets/7b302445-44dc-4081-bb68-4aae1a0ba54e)
sample outputs of the model with a pretrained resnet since time and computation power are limite
![keypoint outputs](https://github.com/user-attachments/assets/e14ea398-816a-4399-865b-afed6275e6db)

, will leave a from scratch resnet for experimental purposes
