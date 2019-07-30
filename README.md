# 100_days_of_ml_code
The repository for my 100 Days of (Medical) ML Code challenge

I have a passion for medicine and deep learning, so focusing my 100 Days of ML Code challenge to medicine seemed like the natural thing to do. My undergraduate degree is in math, completed Udacitity's Deep Learning Nanodegree program, and do some light data science for my work, so I have some experience but this repository is an opportunity to learn more about ML in medicine, apply more theory, and work on good coding practices (I'm reading Clean Code by Martin). Any feedback is always welcome!

I should also include a disclaimer that I am not a medical professional and anything I discuss in this repository should be construed as medical advice. The output of my models or work should not be interpreted as medical opinion regarding any conditions the reader may or may not have based on any symptoms. If you have concerns about your health, you should schedule an appointment with your primary if possible.

## Day 0 - July 25, 2019
Set up a repository and perused medical datasets to begin with cleaning, EDA, and visualization projects. I eventually decided on starting with the arrhythmia dataset found at: http://archive.ics.uci.edu/ml/datasets/Arrhythmia <br>
I'm not certain what the greater project or application will be, I'll keep an open mind for now while working through some of the basics.

## Day 1 - July 26,  2019
Started a basic analysis of the dataset when I noticed one column had many missing values and decided to use the opportunity to highlight the effects of imputation and interpolation methods on the distribution.

## Day 2 - July 27, 2019
Cleaned the dataset, performed some basic EDA, demonstrated effects of PCA. Will consider training a simple regression model using the scikit-learn pipeline.

## Day 2.5 - July 28, 2019
I didn't have time to do much today other than read Deep Reinforcement Learning for Automated Radiation Adaptation in Lung Cancer by Tseng et al., but did not find time to do a write up, and update the README to clarify that I am not a medical professional nor offering medical advice. So, I considered this a partial day.

https://deepblue.lib.umich.edu/bitstream/handle/2027.42/141551/mp12625.pdf?sequence=1&isAllowed=y

## Day 3 - July 29, 2019
Today I created six pipelines using six basic models from a variety of scikit-learn modules to see which out of the box model resulted in the highest F1 score for predicting if the patient had an arrhythmia (0) or is normal (1). Due to the imbalance across the 16 original classes, the problem was reduced to a binary classification problem. If it were a clinical setting and a model were being created for an application, there would be a lot more risk, and ethical concerns, with trying to classify what type of arrhythmia a patient had rather than if their pattern might be abnormal and warrants further review by a cardiologist. Of course, there are many other considerations that need to be made in such an application, but this gives a glimpse of somethings that need to be considered with the potential practical implementations of machine learning models in healthcare.