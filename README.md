
# Brent Bot 2000
An LSTM recurrent neural net implementation to vomit out the poetry of Brent Newsom

## Technical Requirements
* Python 2.7
* Tensorflow
* Keras

## Dependency Installation for macOS

## Install Tensorflow & Keras 
Refer to these links if needed: \
https://www.tensorflow.org/install/install_mac \
https://keras.io/#installation
* Install pip \
  `sudo easy_install pip` 
* Install python virtualenv \
  `sudo pip install --upgrade virtualenv`
* Create a virtualenv for your tensorflow \
  `virtualenv --system-site-packages ~/virtualenv`
* Activate the virtualenv \
  `source ~/tensorflow/bin/activate`
* Ensure pip is installed in this virtualenv \
  `easy_install -U pip`
* Install tensflow \
  `pip install --upgrade tensorflow`
* Install Keras in your python virtualenv \
  `pip install keras`

## Dependency Installation for Other OS
 * Tensorflow with these instructions (use the virtualenv method)
  https://www.tensorflow.org/install/

* Install Keras in your python virtualenv \
  `pip install keras`


## Run the dang thing in your tensorflow virtualenv
* Activate your tensorflow/keras virtualenv  
  `source ~/tensorflow/bin/activate`
* `python brent_bot.py`