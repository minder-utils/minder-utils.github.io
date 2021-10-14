There are many issues that arise from incompatibilities with Apple's M1 silicon.

- If you are a MacOS M1 user and ran ```conda install jupyterlab``` and it won't work when you run ```jupyter lab```. You also might need to run: ```conda install nbclassic==0.2.8``` to reinstall part of the Jupyter package that is broken.
- If scikit-learn keeps erroring, uninstall it and then do the following:
    - ``` conda install scikit-learn```
    - ``` conda install scipy```
- After installing the packages on Windows 10, I had to install ```six==1.15.0```, ```typing-extensions==3.7.4``` and ```scipy```, because tensorflow was erroring.