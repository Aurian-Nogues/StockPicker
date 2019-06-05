
Database_1.csv contains factors and a three way classification in the last column: -1 for underperformer, 0 for un line performance and 1 for outperformer

Database_2.csv contains factors and a binary classification: 1 for outperformer and 0 for non outperformer

stock_picker_binary.ipynb is a machine learning algorithm to classify stock from database_2.csv data. It handles tasks from training to results export

stock_picker_categorical.ipynb is a machine learning algorithm to classify stock from database_1.csv data. It handles tasks from training to results export

1 / 2/ 3 layer(s)_nodes_tuning are a grid search algorithm to tune the number of nodes in 1, 2 an 3 layers neural networks

lr _ and_regularization_tuning.ipynb is a grid search algorithm to tune learning rate and l1/l2 regularizers

#------anaconda commands reminder---------

#create Anaconda environment with anaconda packages
conda create -n keras_environment python=3.6.2 anaconda
#activate environment
conda activate keras_environment
#install tensorflow
pip install --ignore-installed --upgrade tensorflow==1.9
#install keras
pip install keras

#exit environment
conda deactivate

# tranfer anaconda environment:
#Export environment
conda env export > environment.yml

#send environment to other computer and run
conda env create -f environment.yml


