# Machine Learning course EPFL - Project II -  Road Segmentation
## Description
The main goal of this project is to propose an algorithm that segments satellite images, more explicitly the algorithm will have to detect road portions on the image. We have at our disposal a set of train of 100 images, that is to say for each of the images an associated image in black and white, where the white will represent the portions of road detected and the black the rest. In short, each pixel of the images must be binary classified (road=1, background=0). We must then evaluate our model on a test set of 50 images.

All the data is available via [AIcrowd page](https://www.aicrowd.com/challenges/epfl-ml-road-segmentation).

The best result obtained on AIcrowd:
* ID :
* Username :

## Reproduce our results

## Team members
* Thomas Hasler
* Léa Grandoni
* Blerton Rashiti

## External libraries
We used the following libraries:
* [scikit-learn](https://scikit-learn.org/stable/)
* [keras](https://keras.io/)
* [tensorflow](https://www.tensorflow.org/install/)
* [Matplotlib](https://matplotlib.org/)
* [numpy](https://numpy.org/)
* [pandas](https://https://pandas.pydata.org/)
* [tqdm](https://tqdm.github.io/)
* [opencv](https://opencv.org/)
* [os](https://docs.python.org/3/library/os.html)
* [sys](https://docs.python.org/fr/3/library/sys.html)
* [glob](https://docs.python.org/3/library/glob.html)
* [Random](https://docs.python.org/3/library/random.html)

## Python code

We have created several python files that allow us to achieve our goal:

`Data.py`: This is the file which takes care of the data augmentation.

`Evaluation.py`: This file is used to evaluate the results obtained on the validation test by looking at various metrics.

`Metrics.py`: File containing useful functions for the simulation (loss function, iou ...) 

`Model.py`: File containing the u-net model structure.

`Train.py`: File dedicated to the training of  the u-net model structure.

`All_in_one.py`: This is a file containing all the others as one. This is only to be run if there is a problem with the rest. This was the code that was used through out the project. The separation of files was done to emphasize a better project structure and facilitate partial code running.
