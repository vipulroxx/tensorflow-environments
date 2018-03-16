# Installation

# Linux installation without GPU

## Type these commands on the terminal

###  Install the required packages

Clone the repository and cd into it to install the required packages.

`sudo easy_install pip`.

`sudo apt-get install python3-pip python3-dev python-virtualenv`.

`source env/energy-linux-no-gpu/bin/activate`.

`pip install -r requirements-cpu-linux.txt`.

### Test to check if TensorFlow is running or not

`python test-tensorflow.py`

You should get the output `Hello, TensorFlow!`.

# Windows installation with GPU
## Type these commands on the terminal

###  Install the required packages

Clone the repository and cd into it to install the required packages.

`env\energy\Scripts\activate`.

`pip install -r requirements-gpu-windows.txt`.

### Test to check if TensorFlow is running or not

`python test-tensorflow.py`

You should get the output `Hello, TensorFlow!`.
