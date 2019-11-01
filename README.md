# Objective : _This is a mini tutorial which aims to develop intuition about how matrices gets/changes/modifies their shapes as they go from layer to layer in a neural network._   

### Prerequisite : Basic knowledge of representation of [Neural Networks](https://en.wikipedia.org/wiki/Neural_network) and [Matrices](https://en.wikipedia.org/wiki/Matrix_(mathematics)).

* This is a necessary concept to be understood in understanding how actually, we are building more complex neural networks becasue layers stacked over one another keeps the matrices computations overly abstracted but getting deeper insight into their shapes will help us in understanding how our inputs and outputs are related and also very useful while debugging the code as most of the errors occur due to in consistent shapes of matrix.    

* Here we only talk a simple network with simple examples because again, we need to look deeper and so we need to understand fundamentals first, others are just stacking over one another.

![anime1](/images/1.gif)    
![anime1](/images/2.gif)     

### Here, is a simple overview of what the inner code says for itself.

![matrixshapes](/images/overviewmatrices.png)

### Just for recap : 

![matmul](/images/matmul.png)     
       
### Installation :    
1. Clone the repository and navigate to the folder where repo is downloaded.     
`git clone https://github.com/souravs17031999/NeuralNets-Pure-Python.git`    
`cd NeuralNets-Pure-Python`

2. Install all the requirements (maybe create a separate environment using [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)).     
`pip install -r requirements.txt`
* For your reference : requirements mainly includes [Python](https://www.python.org/ftp/python/3.8.0/python-3.8.0.exe) [Numpy](https://pypi.org/project/numpy/) [Jupyter Notebook](https://pypi.org/project/jupyter/)

3. Open file "Analysis_neural_networks.ipynb" on Jupyter Notebook.    
`Jupyter Notebook Analysis_neural_networks.ipynb`

4. Now you should see the notebook opened in your browser on local server host.   
Feel free to explore.

> Highly recommended following tutorials and articles if you feel a bit perplexed !       
         
             
References :    
[Andrew Trask blog](https://iamtrask.github.io/2015/07/12/basic-python-network/)       
[Numpy tutorial](http://cs231n.github.io/python-numpy-tutorial/)      
[Python tutorial](https://docs.python.org/3/tutorial/)     
[Refresher on Gradient descent](https://medium.com/secure-and-private-ai-writing-challenge/playing-with-gradient-descent-intuition-e5bde385078)    
[Refresher on backpropogation](https://medium.com/secure-and-private-ai-writing-challenge/playing-with-backpropagation-algorithm-intuition-10c42578a8e8)
