# Deep-Learning
A repository for Speech emotion recognition with Python on the RAVDESS data set.

Deep learning implemantions with different approaches:
1: Using Traditional Deep Convolutional Neural Networks, 
2: Using simple CNN and LSTM
3: Using LSTM

For the Deep Convolutional Neural Networks we extrateed the Mfcc's data from the samples.
We chose to extract only 3.1 seconds from every sample with 500 milliseconds offset, and fill with zero is there is missing data.
Then we split our data to training data and test data with train size set to 75% of our samples.
We trained 4 different set-up of CNNs to compare and understand what are the changes tha are optimising our CNNs.


req for CNNs

appdirs==1.4.4
astor==0.8.1
astunparse==1.6.3
audioread==2.1.9
certifi==2022.6.15
cffi==1.15.0
chardet==3.0.4
cloudpickle==1.3.0
cycler==0.11.0
debugpy==1.0.0
decorator==4.4.2
dill==0.3.5.1
flatbuffers==2.0
gast==0.5.3
google==2.0.3
h5py==3.1.0
httplib2==0.17.4
idna==2.10
ipykernel==4.10.1
ipywidgets==7.7.0
jax==0.3.8
jaxlib==0.3.7+cuda11.cudnn805
joblib==1.1.0
keras==2.8.0
kiwisolver==1.4.3
librosa==0.8.1
llvmlite==0.34.0
matplotlib==3.2.2
numba==0.51.2
numexpr==2.8.1
numpy==1.21.6
oauth2client==4.1.3
packaging==21.3
pandas==1.3.5
pathlib==1.0.1
pexpect==4.8.0
pickleshare==0.7.5
pooch==1.6.0
portpicker==1.3.9
psutil==5.4.8
ptyprocess==0.7.0
pyarrow==6.0.1
pyasn1==0.4.8
pygments==2.6.1
pyparsing==3.0.9
pytz==2022.1
requests==2.23.0
resampy==0.2.2
rsa==4.8
scipy==1.4.1
seaborn==0.11.2
simplegeneric==0.8.1
six==1.15.0
sklearn==0.0
soundfile==0.10.3.post1
statsmodels==0.10.2
tblib==1.7.0
tensorboard==2.8.0
tensorflow==2.8.2+zzzcolab20220527125636
termcolor==1.1.0
threadpoolctl==3.1.0
tornado==5.1.1
tqdm==4.64.0
traitlets==5.1.1
uritemplate==3.0.1
urllib3==1.24.3
wcwidth==0.2.5
wrapt==1.14.1

# CNN+LSTM & Simple LSTM requirements
cycler==0.11.0
six==1.15.0
numpy==1.21.6
cffi==1.15.0
portpicker==1.3.9
tornado==5.1.1
decorator==4.4.2
matplotlib==3.2.2
pyparsing==3.0.9
ptyprocess==0.7.0
wcwidth==0.2.5
pathlib==1.0.1
ipywidgets==7.7.0
google==2.0.3
pygments==2.6.1
debugpy==1.0.0
pexpect==4.8.0
astor==0.8.1
traitlets==5.1.1
ipykernel==4.10.1
pickleshare==0.7.5
simplegeneric==0.8.1
kiwisolver==1.4.3
psutil==5.4.8
