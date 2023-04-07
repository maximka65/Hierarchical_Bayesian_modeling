# Hierarchical Bayesian modeling

for the study of the relationship between anxiety and eye tremor and contrast sensitivity in humans.

## Subject 

An exploratory study that assumes that early-level processes of visual perception will differ in individuals with different levels of anxiety.

Early level processes:

Contrast sensitivity - an individual plot of the dependence of threshold contrast on the spatial frequency of the presented stimulus. Measured at 9 spatial frequencies (0.2, 0.4, 0.6, 0.8, 1.0, 3.0, 6.0, 8.0, 10.0)

Microtremor of the eyes - high in frequency, but small in amplitude, oscillatory movement of the axes of the eyes. It has two parameters: frequency and amplitude.
According to the obtained coordinates of gaze movement for the amplitude and frequency of microtremor, the following is calculated in software: the average value; the frequency of falling into a given interval of frequency values; amplitudes in a given interval. The intervals are as follows: 0-40, 40-50, 50-60, 60-70, 70-100, 100-110 Hz. In the table, the frequency is denoted by ft, the amplitude is At. Designation ft04 - the frequency of hitting the tremor frequency in the range of 0 - 40 Hz. At110 - tremor amplitude in the range of 100-110. That is, the tremor is represented by a distribution over the ranges from 0 to 110, and the amplitude is represented by the amplitude value in a specific range. mof - the average value of the frequency of the subject, moA - the average value of the amplitude of the subject.
Anxiety is measured in two types - situational and personal. It is presented both in points and in groups (low, medium, high levels of anxiety, presented in the table as 1, 2 and 3, respectively). Due to the inequality of the groups, I was asked to use the values in the point system, and not in the group system, in the analysis. But I decided to leave the group attribute just in case.

## Experiment design

40 people, each measured the level of situational and personal anxiety in points and groups, contrast sensitivity at 9 frequencies, frequency and amplitude of tremor.

## Model
Hierarchical Bayesian Modeling is a statistical modeling technique that takes into account multiple levels of variability in data. It is based on the Bayesian approach to statistical modeling and is used in various fields, including medicine.

## Results

In order to reveal the connection between
- amplitude of eye microtremor (at different intervals)
- eye microtremor frequency (on different ranges)
- contrast sensitivity (at 9 spatial frequencies)

and target values:
- situational anxiety
- personal anxiety

hierarchical Bayesian modeling was carried out.

According to the results of the study, a statistically significant (with a 95% significance level) relationship was revealed between predictors and situational anxiety for contrast sensitivity, the average frequency of eye microtremor and its amplitude in the range of 0-40; And for personal anxiety with predictors: contrast sensitivity, average frequency of eye microtremor, average amplitude of eye microtremor, and amplitude on the range of 0-70