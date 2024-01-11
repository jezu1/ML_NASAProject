# ML_NASAProject

Our project was created on:
- Python 3.7.6
- Jupyter Notebook 6.0.3

The Nasa kaggle dataset needs to be dowloaded from: 
https://www.kaggle.com/datasets/arashnic/exoplanets

And moved to the same folder as the jupyter notebook file.

To be able to run our notebook the follwing packages need to be installed (for pandas we specified a version as some pandas versions
do not support a function we used):

pip install numpy
pip install matplotlib
pip install seaborn
pip install pandas==1.3.5
pip install scikit-learn
pip install scipy
pip install mlxtend
pip install graphviz

To be able to use the graphviz package in addition the graphviz software needs to be installed it can be found here:
https://graphviz.org/download/

After installing the Graphviz installation path needs to be added to the system's PATH variable.

We used graphviz for vizualization of decision trees. If the software is not installed all of our results can still be
obtained just the rendering of the decision tree images will fail.
