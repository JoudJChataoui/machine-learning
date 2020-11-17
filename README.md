# Machine Learning projects
This repository contains Jupyter notebooks where ML models have been trained using vanilla Python and Numpy.

Implementing those algorithms from scratch is a good exercise to strenghten one's grasp on the underlying math.

## Running the notebooks
To run these notebooks, you need to make sure you have the appropriate dependencies.
You will need the following:
* Python 3
* Numpy: Python library that provides high level functions to operate on matrices easily.
* Matlplotlib: Plotting library. It is not necessary but useful to visualize some of the data. If you do not install it, make sure you comment out the lines that use it.
* Jupyter: The files in this repository are primarily Jupyter notebooks. If you have an Python IDE, you can simply use that.
* Scikit-learn: I used scikit-learn only to access some common ML datasets like MNIST digits or the Iris dataset. You can still run the models on different datasets.

With the above dependencies you can launch any jupyter notebook. For instance:
```
jupyter notebook digit-classifier/Digit\ classifier.ipynb
```

## Viewing the notebooks
You can simply navigate to the notebooks and Github will render them in your browser as html.

However, you may sometimes run into an issue saying *Sorry, something went wrong. Reload?*. This is likely due to an issue with Github.

**A workaround to access the notebooks** without running them locally would be to view them on https://nbviewer.jupyter.org/.
* Go to https://nbviewer.jupyter.org/
* Grab the Github link for the Jupyter notebook you want to see. For instance the [Decision Tree Iris classifier](https://github.com/JoudJChataoui/machine-learning/blob/master/iris-classifier/Decision%20Tree%20Iris.ipynb)
* Paste it in the viewer. This will take you to a page where the notebook is rendered [like this one](https://nbviewer.jupyter.org/github/JoudJChataoui/machine-learning/blob/master/iris-classifier/Decision%20Tree%20Iris.ipynb)
