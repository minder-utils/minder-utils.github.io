If you are on Windows 10 and use the conda environment manager, then you may want to use the ```environment.yml``` file that is supplied within the package, located here: [minder_utils package](https://github.com/ImperialCollegeLondon/minder_utils). Otherwise, please follow the instructions below.


If attempting to install this package on MacOS with M1 silicon then please follow the instructions here: [Installing Tensorflow on MacOS](https://github.com/apple/tensorflow_macos/issues/153) (Please ask Alex if you need help because this is quite unfriendly). Then you may move to step 1. If you are installing on windows, move to step 1.

1. Install tensorflow 2 using the command here: [Tensorflow Installation Guide](https://www.tensorflow.org/install)
    - The package has been tested with tensorflow 2.6.0 on windows and 2.4.0 on MacOS.

2. Install pytorch, using the command here: [Pyorch Installation Guide](https://pytorch.org/get-started/locally/)
    - The package has been tested with pytorch 1.9.1 with cuda 10.2 on windows and 1.9.1 on MacOS.

3. Install scikit-learn using the command here: [Scikit-Learn Installation Guide](https://scikit-learn.org/stable/install.html)
    - The package has been tested with scikit-learn 1.0 on windows and 1.0 on MacOS.

4. Install the minder_utils package using the following command:
    - ```pip install -e git+https://github.com/ImperialCollegeLondon/minder_utils.git#egg=minder_utils```

Then, should be up and running! If you have any issues, please consult the troubleshooting below.