# Computational-Biology
Assignment 2

The goal of homework  part 1 :

The code begins by importing the necessary libraries for data handling, visualization, and building machine learning models. It then loads the Wine Quality dataset, separates the features and target values, and displays the feature names along with a few sample rows to understand the data. The data is visualized using a scatter plot showing the relationship between alcohol and malic acid to observe how different wine samples are distributed by quality. Next, the features are standardized using the StandardScaler so they are all on the same scale, which helps the models perform better. The dataset is then divided into training and testing sets to allow the models to learn from one part of the data and be tested on another. After that, a Support Vector Machine model is trained, used to make predictions, and its accuracy is printed. The same process is repeated for the Decision Tree and Logistic Regression models to classify the wine samples based on their chemical features. Finally, the accuracy results of all three models are printed and compared to determine which performs best in predicting wine quality.

Load the Wine Quality Dataset:

<img width="1994" height="246" alt="image" src="https://github.com/user-attachments/assets/9cdcd87b-63ba-4e9f-bb01-8f61f1a6302c" />

Visualize the Data:

<img width="1024" height="722" alt="image" src="https://github.com/user-attachments/assets/91fd02a1-ac59-47fe-a6c3-a68e0a828e34" />

Evaluate the Model:

<img width="350" height="68" alt="image" src="https://github.com/user-attachments/assets/be446f3a-462e-4f00-a50e-e5bf149d1d21" />

Decision Tree model:

<img width="456" height="64" alt="image" src="https://github.com/user-attachments/assets/71447f2e-123c-4ecd-aed1-884506575b72" />

Logistic Regression:

<img width="398" height="68" alt="image" src="https://github.com/user-attachments/assets/1a2257bb-9143-4537-baa5-5a2f1599df6e" />



The goal of homework part 2 : 

In this part, the code loads the MNIST dataset, which contains many handwritten digit images from 0 to 9. It normalizes the data and splits it into training and testing sets. Then it trains three models (Random Forest, Logistic Regression, and a simple Neural Network (MLP) ) to predict which number each image represents. Finally, it checks how accurate each model is and prints the results to compare their performance.
Then the code uses a pre-trained YOLOv5 model to detect objects and faces in images. When my photo is uploaded, it is used twice ; once to test the detection and again after resizing it to make sure the model can correctly detect my face. The code runs the model on my image and shows the results with boxes drawn around the detected face.

<img width="1126" height="794" alt="image" src="https://github.com/user-attachments/assets/d553310c-d063-4f71-8aa6-76372ea2676f" />

