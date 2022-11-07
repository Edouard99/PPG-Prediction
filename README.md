# PPG-Prediction

Hi ! :wave:

Sorry for the mess in this project's code and readMe! I am currently cleaning the project's code and building :construction_worker: the readMe! It will be soon updated! :smiley:

This project aims at using a Deep Learning model to predict the heart rate from a Blood Volume Pulse (BVP) PPG signal contaminated by motion artifact. Indeed, due to motion artifact, the heart rate can be hard to compute from a contaminated signal because the heart rate peaks are noised in the signal by acceleration. Using the Fourier spectrum and deep learning, one of the models predicts the heart rate from the spectrum directly while the other denoises the signal and then predicts the heart rate.

The methods used in this project are inspired by Chang's paper [[1]](#1) and Reiss's paper [[2]](#2) which tackle this subject.

A better readMe and a clean code will come soon ... Wait for the update ...  :hourglass:

## References

<a id="1">[1]</a> Xiangmao Chang et al. “DeepHeart”. In: ACM Transactions on Sensor Networks (TOSN)
17 (2 Jan. 2021). issn: 15504867. doi: <a href="https://doi.org/10.1145/3441626">https://doi.org/10.1145/3441626</a>.

<a id="2">[2]</a> Attila Reiss et al. “Deep PPG: Large-scale heart rate estimation with convolutional neural networks”.
In: Sensors (Switzerland) 19 (14 July 2019). issn: 14248220. doi: <a href="https://doi.org/10.3390/S19143079">https://doi.org/10.3390/S19143079</a>.
