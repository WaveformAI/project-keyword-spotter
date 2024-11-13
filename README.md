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

## Packages to install
*(replace nala with apt if you don't have nala)*

ONLY ONE OF THE FOLLOWING

```sudo nala install libedgetpu1-std``` <- for standard performance

```sudo nala install libedgetpu-max``` <- for maximum clock speed

AND

```sudo nala install libasound libasound2-dev portaudio19-dev```

## Python libraries and system packages

Run ./install_requirements.sh to install everything else
