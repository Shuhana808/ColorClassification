# ColorClassification
The color classification task is to predict the distinct color category based on the three 
input values for RGB (R: Red, G: Green, B: Blue) color code. Each of these three numbers is 
basically an integer ranging from 0 to 255 and these combined Red, Green & Blue values are 
used to generate a distinct solid color. The dataset contains 11 basic color categories for 
classification. These basic colors are Red, Green, Blue, Yellow, Orange, Pink, Purple, Brown, 
Grey, Black and White.

Load the dataset into a pandas dataframe:

![img.png](resources/dataset.png)

Encode "label" column into numerical data using sklearn LabelEncoder:

![img.png](resources/label-encoding.png)

Split the data into train and test datasets with 80:20 ratio:

![img.png](resources/split_data.png)

Install and import tensorflow library:

![img.png](resources/install_tf.png)

Build and compile the sequential model. The model has an input, an output and a hidden layer. 
Activation function of the hidden layer is relu. The model is optimized by the Adam optimizer:

![img.png](resources/model.png)

Train the model on the training dataset for 100 epochs:

![img.png](resources/train.png)

Predict the color category for the testing data and save the result in `prediction.csv` file:

![img.png](resources/predict.png)

Evaluate the accuracy score of model using the predicted data:

![img.png](resources/accuracy.png)
