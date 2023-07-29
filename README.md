# Rice Blast Disease Classification Using Multispectral Images

This project aims to classify the disease of a rice plant in RGB and Infrared images using computer vision and machine learning techniques. The objective is to predict rice blast disease, which is responsible for 30% loss in rice production worldwide, and help in early diagnosis to manage crop diseases.

## Dataset

The dataset contains RGB and Infrared images of rice plants, along with their corresponding disease labels. The dataset is provided by the organizers of the challenge on the Zindi website. The dataset is split into training and validation sets with a ratio of 80:20.

## Approach

I tried multiple approaches to classify the disease of a rice plant. Firstly, I used a custom DL model called Swish model, which was provided by a researcher in my faculty. However, the model did not perform as well as expected.

Next, I tried to use a pre-trained model ResNet18 with transfer learning to classify the disease. This approach performed better than the custom DL model.

Finally, I tried using computer vision extractors SIFT & SURF with classical machine learning models such as random forest. However, this approach did not perform as well as the ResNet18 model.

The ResNet18 model was trained on the training set and evaluated on the validation set. The model achieved an accuracy of 85% on the validation set.

## Conclusion

In conclusion, the ResNet18 model with transfer learning was the most effective approach for classifying rice blast disease in multispectral images. The model achieved an accuracy of 85% on the validation set. This solution can help in the early detection and management of crop diseases, particularly in regions such as Egypt where there is a scarcity of experienced agricultural extension officers.
