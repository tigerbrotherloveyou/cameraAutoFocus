# Camera autofocus methods and lens evaluation
## Introduction
This project provides a fast tool as well as the source code to find the best metric to adjust the camera focus that can be used in your camera based application. Not only does it decribe the advantages of each method and their comparison in evaluation the lens of your products' camera hardware, but also the sample results, validation patterns, images of the patterns under continous changing lens rotation angles are provided and visualized. The evaluation contains characterization of the lenses with respect to Focus Of View, image quality, and deformations caused due to misaligned lenses or lens characteristics. Meanwhile, different camera autofocus algorithms are compared and assessed for the suitability of the specific patterns and purposes. 
## Project Structure
The project folder is consisted of two folders, which are /scripts and /Test_results. Inside of /scripts, the functions and contents of the scripts are described as follows:
* **iBin_Autofocus_Metrics.py** 37 different types of metrics, including the reknowed kernels such as "Variance of Median", "Tenengrad Scharr", "Tenengrad Sobel", "Laplacian". 
* **Read_metric_from_Excel.py** a script that loads the scores after evaluation each metric on the given samples images, and draws the curves which indicate the ideal lens rotation angle, in another way, the best focus angle. 
## Prerequisites
The following instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Python 3
Python 3 is used when this project is constructed. This project requires the following packages to be installed:
  
Python 3 can be acquired at the [official website](https://www.python.org/), download page. 
 To check which packages have already been installed in your python 3 environment, you can run the following command in your
 shell or powershell terminal:
 ```
python3 freeze
```
### Verification of preparing the dependencies


## Running the scripts

## Author

* **Yao Zhang** - *Initial work* - [yancy-zh](https://github.com/yancy-zh)


