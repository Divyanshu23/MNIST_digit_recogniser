## Deep Neural Network for Digit Recognition on MNIST Dataset


<img src="images/three_layered_nn.png" width="50%" height="90%"/>


### <ins>Overview</ins> ###

This project uses Deep Neural Network Classification technique to classify handwritten digit <a href="http://yann.lecun.com/exdb/mnist/">MNIST</a> dataset into 10 classes (digits from 0-9).

### <ins>Features</ins> ###

<ul>
  <li>Classify 28pixels * 28pixels grayscale images of handritten digits into appropriate values from 0-9. </li>

  <li>Build and Train the Neural Network using Tensorflow framework.</li>

  <li>Accuracy of 97% is achieved on test data using "relu" activation function and "adam" optimizer.</li>

  <li>Generate plots of Confusion Matrix using Seaborn library</li>
</ul>

### <ins>Dependencies</ins> ###

<ol>
  <li><a href="https://docs.anaconda.com/anaconda/user-guide/tasks/tensorflow/">Tensorflow</a></li>
  <li><a href="https://anaconda.org/conda-forge/matplotlib">Matplotlib</a></li>
  <li><a href="https://anaconda.org/anaconda/seaborn">Seaborn</a></li>
  <li><a href="https://anaconda.org/anaconda/numpy">Numpy</a></li>
</ol>

<p>It's recommended to instal all the libraries using <a href="https://www.anaconda.com/">conda</a> package manager.</p>

Installation of <a href="https://www.anaconda.com/">Anaconda</a> gives all the required libraries and package manager in one shot. <b>Tensorflow</b> needs to be installed on top it. Remeber to actiavte the necessary environment `conda activate $"Tensorflow environment name"`.

### <ins>Executing Code (On Ubutnu 18.04 and higher)</ins> ###

```

$ git clone git@github.com:Divyanshu23/MNIST_digit_recogniser.git

$ conda activate tf-gpu

$ jupyter notebook

```

Execute the cells of the notebook to see model training and classification in progress.