# Human-Activity-Recognition-using-Classical-ML-and-LSTM
![image](https://user-images.githubusercontent.com/115543070/233274895-21df273b-788c-4137-bc20-e262dcd8fceb.png)


<h2>Introduction</h2>

Human Activity Recognition (HAR) uses sensors to predict what activities a person is doing based on their movements. These movements can be normal indoor activities like standing, sitting, jumping, or going up stairs. Sensors, often located on a smartphone or vest, record accelerometer and gyroscope data in three dimensions. HAR identifies actions by exploiting information from various sources like environmental or body-worn sensors. Once the subject's activity is recognized, an intelligent computer system can offer assistance. Deep learning methods have been successful in HAR due to their ability to automatically learn higher-order features. However, the challenge lies in the large volume of sensor data collected, and conventional pattern recognition approaches heavily rely on hand-crafted feature extraction, hindering their generalization performance. Recent advancements in deep learning have made it possible to perform automatic high-level feature extraction, achieving promising performance in many areas of sensor-based activity recognition.

<h2>Dataset Description</h2>

The Human Activity Recognition database was built from the recordings of 30 study participants performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors. The objective is to classify activities into one of the six activities performed.

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

Accelerometer and Gyroscope readings are taken from 30 volunteers(referred as subjects) while performing the following 6 Activities.

1.Walking

2.WalkingUpstairs

3.WalkingDownstairs

4.Standing

5.Sitting

6.Lying

*    Readings are divided into a window of 2.56 seconds with 50% overlapping.

*    Accelerometer readings are divided into gravity acceleration and body acceleration readings, which has x,y and z components each.

*    Gyroscope readings are the measure of angular velocities which has x,y and z components.

*    Jerk signals are calculated for BodyAcceleration readings.

*    Fourier Transforms are made on the above time readings to obtain frequency readings.

*    Now, on all the base signal readings., mean, max, mad, sma, arcoefficient, engerybands,entropy etc., are calculated for each window.

*    We get a feature vector of 561 features and these features are given in the dataset.

*    Each window of readings is a datapoint of 561 features.

<h2>Machine Learning Objective</h2>

* Given a data classifiy it into a one of the 6 Activity

* Multi-Class Classification Problem

<h2>Perfomance Metric</h2>

*    Accuracy

*    Confusion Metrics



