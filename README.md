# Gender Recognition of Voice Samples
Machine Learning/ Classification Project/Python and R
## Objectives
### To predict gender with corresponding voice and speech features
### Authors: Amanraj Singh, Monica Sharma
## Download the Data

#### The dataset can be downloaded here on Kaggle. It is consisted of 3,168 observations with the 21 variables, as listed below.

```
1 target variable:
label (male or female)
20 independent variables:


meanfreq: mean frequency (in kHz)
sd: standard deviation of frequency
median: median frequency (in kHz)
Q25: first quantile (in kHz)
Q75: third quantile (in kHz)
IQR: interquantile range (in kHz)
skew: skewness (see note in specprop description)
kurt: kurtosis (see note in specprop description)
sp.ent: spectral entropy
sfm: spectral flatness
mode: mode frequency
centroid: frequency centroid (see specprop)
meanfun: mean fundamental frequency measured across acoustic signal
minfun: minimum fundamental frequency measured across acoustic signal
maxfun: maximum fundamental frequency measured across acoustic signal
meandom: mean of dominant frequency measured across acoustic signal
mindom: minimum of dominant frequency measured across acoustic signal
maxdom: maximum of dominant frequency measured across acoustic signal
dfrange: range of dominant frequency measured across acoustic signal
modindx: modulation index
```
## Preprocessing the Data

#### Run the preprocessing scripts
## Modeling
#### Run the algorithms (Logistic, Decision Tree, SVM, Random Forest)
## Feed Live Data 

#### Record the sound (Male or Female). Covert it into a .wav file.
#### Create 2 folders Male and Female in your default working directory for R and paste the wav files in respective folders.
#### Run the R code – It will output the csv file with 20 features.
## Final Modeling 

#### Read the csv file in jupyter after heading “Prediction using real time voice samples”
#### Run the algorithms and it will predict the voice samples whether its Male or Female in 0’s and 1’s form
