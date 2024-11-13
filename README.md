# Keyword Detector using Coral.AI
## Linux ONLY

Only detecting keywords in file config/labels_gc2.raw

We will need to re-train the model to recognize other keywords or to classify sounds

# Setup
## Python and Pyenv Setup
Install pyenv (if not present)

```pyenv install 3.8.20``` (if not present)

```pyenv virtualenv 3.8.20 coral```

```pyenv local coral```

## Driver Packages to install

ONLY ONE OF THE FOLLOWING

```sudo apt-get install libedgetpu1-std``` <- for standard performance

```sudo apt-get install libedgetpu-max``` <- for maximum clock speed

## Python libraries and system packages

Simply run install_requirements.sh

