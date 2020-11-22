# CSE499
## Install all the libraries
conda create -n tanzim python=3.7 -y
conda activate tanzim
pip install opencv-python
conda install -c conda-forge pydicom -y
conda install -c anaconda pandas -y
conda install -c conda-forge matplotlib -y
conda install -c anaconda seaborn -y
conda install scikit-image -y
conda install -c anaconda scikit-learn -y
conda install -c conda-forge tqdm -y
conda install -c plotly plotly -y
pip install tikzplotlib
conda install scikit-learn -y
conda install -c conda-forge ipywidgets -y
jupyter nbextension enable --py widgetsnbextension
pip install -U efficientnet
conda install -c anaconda keras -y
pip install tensorflow==2.2.0
