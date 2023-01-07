# Assessment: Machine Learning and Statistics

![keras](img/keras.png)

## Objectives of this repository

There are two main section to this repository. The first section is in the root of the repository. This is the Machine Learning Project Notebook for this module. The topic of the project is Anomaly Detection using Keras. 

The second section is in the folder named 'practicals'. This is where the regular tasks for the module have been performed.

## Keras
The scope of this project was to use the python package keras to detect anomalies in a timeseries dataset. Keras allows the user to easily build and train neural networks and deep learning models. It is a high-level API. Keras is also one of the most popular Deep Learning frameworks among researchers and developers. Im this project it runs on top of Tensorflow (the "backend") which is also a python package. Keras is a high-performance API. It's easy to create differentiable programs using keras. It is focused on user experience. Keras provides fast prototyping and runs seamlessly on Centaral Processing Units (CPUs) and Graphic Processing Uinits (GPUs). It supports the major companies NVIDeA and AMD. Keras allows for the freedom to design any architecture and is easy to get started with. Keras also provides easy production ways for models. It uses an Artificial Neural Networks (ANNs), where each node (artificial neuron), is connected to another node and has an associated weight and threshold.

The data used in this project is server metrics/clicking rates. There are 2 columns, values and timestamps The data files for this project have been collected over years of interacting with customers on resolving their problems related to anomalies. You can view the kaggle and github links to the dataset below:

[kaggle - Numenta Anomaly Benchmark (NAB)](https://www.kaggle.com/datasets/boltzmannbrain/nab) <br>
[GitHub - numenta/NAB](https://github.com/numenta/NAB)

## Practicals

Link to Ian McLoughlin's repo to view notebooks that the practicals are based on: <br>
[GitHub - Ian McLoughlin](https://github.com/ianmcloughlin/2223-S1-machine-learn-stats)

The topics covered are:

1. Statistics (Lady Tasting Tea, t-Tests)
2. Models (Least Square Method, Absolute Value Method, Optimisation)
3. Parameters (Using numpy's polyfit to fit polynomials to two data sets)

### Statistics Questions:
#### Exercise 1
Calculate the minimum number of cups of tea required to ensure the probability of randomly selecting the correct cups is less than or equal to 1%.

Bonus Question: How many would be required if you were to let the taster get one cup wrong while maintaining the 1% threshold?

#### Exercise 2
Use scipy's version of Fisher's exact test to simulate the Lady Tasting Tea problem.

### Models Questions:
#### Exercise 1
- Use numpy and matplotlib to plot the absolute value function.
- Research and explain why the absolute value function is not typically used in fitting straight lines to data.

#### Exercise 2
- Fit a straight line to the following data points, using all three methods used in the 02-models.ipynb notebook.
- Do you think a straight line is a good model for these points?

### Parameters Question:
Use numpy's polyfit to fit polynomials to the following two data sets.

Data Set 1:

```python
x = [0.0, 1.0, 2.0, 3.0, 4.0, 5.0, 6.0, 7.0, 8.0, 9.0, 10.0, 11.0, 12.0, 13.0, 14.0, 15.0]
y = [1.3, 1.2, 9.4, 27.3, 63.1, 126.5, 217.3, 341.5, 512.8, 729.3, 1001.8, 1332.7, 1728.9, 2198.8, 2743.7, 3376.7]
```

Data Set 2:
```python
x = [0.0, 1.0, 2.0, 3.0, 4.0, 5.0, 6.0, 7.0, 8.0, 9.0, 10.0, 11.0, 12.0]
y = [5.7, 16.6, 58.0, 278.9, 1069.3, 3181.4, 7844.3, 16883.9, 32854.9, 59144.2, 100106.7, 161166.3, 248958.6]
```

## nbviewer:

Use the link below to view static versions of the jupyter notebooks in this repository.

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/Cormac88/machine-learning-and-statistics/tree/main/)

## Install

### Installing Python and Jupyter Notebook

1. Python and jupyter lab are needed to run the `.ipnb` files in this repository.

2. Download `Python` from https://www.python.org/.

3. If you use `conda`, type `conda install -c conda-forge jupyterlab`. If you use `pip`, type `pip install jupyterlab` and press enter.

4. Wait for jupyter to finish installing.

Please see the [official Installation](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) of Jupyter Lab page if you are having issues.

## Running the Code

1. Change directory to the folder that contains the.ipynb file you wish to run.

2. Type `jupyter lab` or `jupyter notebook`.

3. Jupyter lab will open in your browser as a new tab. Keep the command prompt window open as it needs to stay running while Jupyter Notebook is active.

4. Click on the `.ipynb` file you wish to run.

5. Click on `Kernel` and then select `Restart Kernal and Run All Cells`.

6. When finished, close the tab in your browser and then press press 'ctrl + C' in the command prompt to end the session.

## Credits

For the Keras project, I heavily relied on Ian McLoughlin's GitHub for the code for this project.<br>
[GitHub - Ian McLoughlin](https://github.com/ianmcloughlin/2223-S1-machine-learn-stats)

## Contact

[Cormac Hennigan](mailto:G00398284@gmit.ie)