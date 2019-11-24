### Setting up an environment for librosa
* Click Windows Start Menu -> Anaconda Prompt (Anaconda3)
* Create a new environment:
```
> conda create -n dsp python=3.6
```
* Activate the environment:
```
> conda activate dsp
```
* Install needed packages:
```
> conda install jupyter numpy scipy matplotlib
> conda install -c conda-forge -n dsp librosa
> conda install -c conda-forge -n dsp ffmpeg
```

### Setting up an environment for the book "Kalman-and-Bayesian-Filters-in-Python"
* Click Windows Start Menu -> Anaconda Prompt (Anaconda3)
* Create a new environment:
```
> conda create -n kalman python=3.6
```
* Activate the environment:
```
> conda activate kalman
```
* Install needed packages:
```
> conda install jupyter numpy scipy matplotlib
```
* Install filterpy via pip:
```
> pip install filterpy
```
