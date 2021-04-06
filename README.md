# DNN-Implementation-on-Penguins-Dataset

![image](https://user-images.githubusercontent.com/66888595/113690616-3d9a4980-96e9-11eb-860a-c3f003c5ad38.png)

## Table of Contents
<ul>
  <li>
    <a href="#Overview">
      <span>1. Overview</span>
    </a>
  </li>
  <li>
    <a href="#Dataset">
      <span>2. Dataset</span>
    </a>
  </li>
  <li>
    <a href="#Motivation">
      <span>3. Motivation</span>
    </a>
  </li>
  <li>
    <a href="#Aspects">
      <span>4. Technical Aspects</span>
    </a>
  </li>
  <li>
    <a href="#Credits">
      <span>5. Credits</span>
    </a>
  </li>
   
</ul>

<h3>
  <span id="Overview">Overview</span>
</h3>

> To predict the species of penguin, being learned from the training dataset, this model, `/penguin-classifier.h5`, predicts if a particular penguine is *Gentoo*, *Adelie*, *Chinstrap*. The dataset used in the this project is a subset of data collected and made available by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER, a member of the Long Term Ecological Research Network.

<h3>
  <span id="Dataset">Dataset</span>
</h3>

> The penguins dataset used in the this project is a subset of data collected and made available by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER, a member of the Long Term Ecological Research Network. The Species column is the label our model will predict. Each label value represents a class of penguin species, encoded as 0, 1, or 2. The following code shows the actual species to which these class labels corrrespond. 

<h3>
  <span id="Motivation">Motivation</span>
</h3>

> In reality, I can solve the penguin classification problem easily using classical machine learning techniques without the need for a deep learning model; but it's a useful, easy to understand dataset.

<h3>
  <span id="Aspects">Technical Aspects</span>
</h3>

> The contructed neural network has following features:<br>
  >  1. An input layer that receives an input value for each feature (in this case, the four penguin measurements) and applies a ReLU activation function.<br>
  >  2. A hidden layer that receives ten inputs and applies a ReLU activation function.<br>
  >  3. An output layer that uses a SoftMax activation function to generate an output for each penguin species (which represent the classification probabilities for each of the three possible penguin species). Softmax functions produce a vector with probability values that sum to 1.<br>
  >  The plot of loss distribution is ![image](https://user-images.githubusercontent.com/66888595/113700214-3167b980-96f4-11eb-8a0e-fdcf9017afa2.png)


<h3>
  <span id="Credits">Credits</span>
</h3>

> <a href="https://www.uaf.edu/cfos/people/faculty/detail/kristen-gorman.php">Dr. Kristen Gorman</a><br><a href="https://pal.lternet.edu/"> Palmer Station, Antarctica LTER</a><br><a href="https://lternet.edu/"> Long Term Ecological Research Network</a>
