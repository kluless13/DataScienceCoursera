## Getting and Cleaning Data Project

Author: Angad M

### Description
Additional information about the variables, data and transformations used in the course project for the Johns Hopkins Getting and Cleaning Data course.

### Source Data
Data + Description can be found here [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

### Data Set Information
The trials were carried out on a group of 30 participants ranging in age from 19 to 48 years. Each participant completed six activities while wearing a smartphone (Samsung Galaxy S II) on the waist (WALKING, WALKING UPSTAIRS, WALKING DOWNSTAIRS, SITTING, STANDING, LAYING). We measured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz using the integrated accelerometer and gyroscope. The studies were videotaped in order to manually identify the data. The obtained dataset was randomly partitioned into two sets, with 70% of the volunteers generating training data and 30% generating test data.

The sensor data (accelerometer and gyroscope) were pre-processed using noise filters before being sampled in 2.56 sec fixed-width sliding windows with 50% overlap (128 readings/window). A Butterworth low-pass filter was used to split the sensor acceleration data, which contains gravitational and body motion components, into body acceleration and gravity. Because the gravitational force is believed to contain only low frequency components, a filter with a cutoff frequency of 0.3 Hz was chosen. A vector of features was produced from each window by computing variables in the time and frequency domains.

### Attribute Information
For each record in the dataset it is provided: 
- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration. 
- Triaxial Angular velocity from the gyroscope. 
- A 561-feature vector with time and frequency domain variables. 
- Its activity label. 
- An identifier of the subject who carried out the experiment.
