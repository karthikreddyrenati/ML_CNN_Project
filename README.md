# ML_CNN_Project
*1. Imports and Dataset Loading:*
The code begins by importing necessary libraries for data manipulation, visualization, machine learning, and deep learning.
It utilizes ucimlrepo to fetch the Optical Recognition of Handwritten Digits dataset.
Data is loaded into Pandas DataFrames (X for features and y for labels).
Metadata and variable information are printed to provide insights into the dataset.

*2. Data Preprocessing:*
The features and labels data types are printed to confirm they are Pandas DataFrames.
Shapes of feature and label arrays are printed.
Features information is printed.
The dataset is split into training and testing sets using train_test_split from sklearn.model_selection.
Features data is reshaped to be suitable for CNN input and normalized to the range [0, 1].
A sample image is visualized using Matplotlib.

*3. CNN Architecture:*
A Sequential model is defined using Keras with layers for convolution, pooling, flattening, and fully connected layers.
Model summary is printed to show the architecture and number of parameters.
Visualizations of the Max Pooling layer are shown.

*4. Model Training:*
The model is compiled with Adam optimizer and categorical crossentropy loss.
Training is performed using model.fit() function for 10 epochs, with validation data.
Training history (history) is stored for visualization.

*5. Model Evaluation:*
Model accuracy is evaluated on the test set using model.evaluate().
Training and validation loss curves are plotted to visualize model performance during training.
Training and validation accuracy curves are plotted to visualize model accuracy during training.

*6. K-Fold Cross Validation:*
Scikit-learn's KFold cross-validation is used to evaluate the model's performance.
Model is trained and validated for 5 folds, and accuracy for each fold is stored.
Mean accuracy of K-Fold cross-validation is calculated and printed.

*7. Confusion Matrix:*
Confusion matrix is generated using confusion_matrix from scikit-learn.
Confusion matrix is visualized using a heatmap.

*8. Model Metrics:*
Additional metrics such as accuracy, precision, recall, and F1-score are calculated using scikit-learn metrics functions.
Metrics are printed out.
Metrics are visualized using a bar chart.

*Conclusion:*
The code successfully implements a CNN model for optical recognition of handwritten digits. It covers all essential steps from data loading and preprocessing to model training, evaluation, and performance analysis. Visualizations aid in understanding the model's behavior and performance. Finally, comprehensive metrics provide insights into the model's effectiveness in classifying handwritten digits.

![arc](https://github.com/Narendrakumar14-R/CNN-Project/assets/147754023/3d58cfb5-48d9-4377-830f-63336b780725)
