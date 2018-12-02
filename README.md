# signature-verification

_Install Miniconda for Windows

conda create -n signature python=2
conda activate signature
conda install scipy libpython mingw
set PATH=%PATH%;c:\Users\<username>\AppData\conda\signature\mingw\bin
_Different path for Ubuntu
_Put your username at <username>

conda install theano -y
pip install opencv-python
conda install pillow pil -y
conda install jupyter matplotlib -y
pip install https://github.com/Lasagne/Lasagne/archive/master.zip

set "MKL_THREADING_LAYER=GNU"

jupyter notebook
