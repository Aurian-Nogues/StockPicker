
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


