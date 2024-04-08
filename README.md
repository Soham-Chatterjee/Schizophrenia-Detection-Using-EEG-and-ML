# Detection of Schizophrenia in subjects by analysing their brain EEG signals and applying machine learning algorithms like Logistic Regression and 1D Convolutional Neural Networks

## Abstract of the project:

In this project, we have tried to analyze the EEG signals collected from **14 healthy subjects** and **14 schizophrenic subjects** using the **standard 10-20 EEG montage** with **19 EEG channels** and train a Machine Learning model to accurately predict the onset of Schizophrenia in an unknown subject.
The data from the subjects is segregated into fixed length overlapping epochs with a duration of 5 seconds each. The subjects are divided into groups (0, 1, 2, ...) and then split into training and testing sets for the machine learning models.
Different features such as the **average, standard deviation, peak to peak, variance, minimum, maximum etc.** have been extracted from the data and fed into the algorithm for achieving better performance of the model.
We have used the Logistic Regression classification algorithm and a 1D Convolutional Neural Network algorithm comprising of 13 layers (11 hidden layers) for this classification. It was observed that the Logistic Regression model achieves an accuracy of **66.03%** and the Deep Convolutional Neural Network is able to achieve an accuracy of **71.72%** on the validation data.

Overall, this project offers a comprehensive analysis of different EEG signals for prediction of schizophrenia in subjects and demonstrates the use of logistic regression and deep neural
network models in motor imagery classification tasks.

**Keywords**: EEG signal analysis, Schizophrenia, Machine Learning Classification, Logistic
Regression, Convolutional Neural Networks
