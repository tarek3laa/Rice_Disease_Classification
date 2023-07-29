# Rice Blast Disease Classification Using Multispectral Images

This project aims to classify the disease of a rice plant in RGB and Infrared images using computer vision and machine learning techniques. The objective is to predict rice blast disease, which is responsible for 30% loss in rice production worldwide, and help in early diagnosis to manage crop diseases.

## Dataset

The dataset contains RGB and Infrared images of rice plants, along with their corresponding disease labels. The dataset is provided by the organizers of the challenge on the Zindi website. The dataset is split into training and validation sets with a ratio of 80:20.

## Approach

I tried multiple approaches to classify the disease of a rice plant. Firstly, I used a custom DL model called Swish model, which was provided by a researcher in my faculty. However, the model did not perform as well as expected.

Next, I tried to use a pre-trained model ResNet18 with transfer learning to classify the disease. This approach performed better than the custom DL model.

Finally, I tried using computer vision extractors SIFT & SURF with classical machine learning models such as random forest. However, this approach did not perform as well as the ResNet18 model.

The ResNet18 model was trained on the training set and evaluated on the validation set. The model achieved an F1 score of 0.9 on the validation set.

## Results

The ResNet18 model achieved an F1 score of 0.9 on the validation set. This indicates that the model is performing very well in classifying the disease of a rice plant in multispectral images.

Compared to the baseline approach and other approaches that were tried during the challenge, our model outperformed them by a significant margin. This demonstrates the effectiveness of the ResNet18 model with transfer learning for this particular problem.

## Conclusion

In conclusion, our solution using the ResNet18 model with transfer learning achieved an F1 score of 0.9 on the validation set, which is a strong performance for classifying rice blast disease in multispectral images. This solution can help in the early detection and management of crop diseases, particularly in regions such as Egypt where there is a scarcity of experienced agricultural extension officers.
