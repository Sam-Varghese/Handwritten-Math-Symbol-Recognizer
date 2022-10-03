# Handwritten Symbol Recognizer

<p align="center"><img src = "https://cdn.pixabay.com/photo/2017/09/08/19/05/a-2729782_960_720.png" /></p>

This is a handwritten symbol recognizer. It uses a convolutional neural network to classify handwritten symbols. The network is trained on [this kaggle dataset](https://www.kaggle.com/datasets/sagyamthapa/handwritten-math-symbols).

## Usage

1. Clone the repository
2. Install the dependencies using `pip install -r requirements.txt`
3. In your workspace, install [this kaggle dataset](https://www.kaggle.com/datasets/sagyamthapa/handwritten-math-symbols).
4. Now execute the cells of [this notebook](Model.ipynb) in order.
5. If you wish model to do the prediction on the handwritten digits you've made, then you may use MS Paint or any other image editor to draw the digits and save them as .png files in [this folder](self_checking/).