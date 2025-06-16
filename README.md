# t-SNE_WebGL_3DPlotter

# Installation & Dependencies
We maintain several platform-specific installation cookbooks online.

Broadly speaking, to install the Python dependencies, we recommend you install Anaconda and then create a conda environment with a Python 3.7 runtime:

conda create --name=3.7 python=3.7
source activate 3.7
Then you can install the dependencies by running:

bash
pip install https://github.com/yaledhlab/pix-plot/archive/master.zip
The website that PixPlot eventually creates requires a WebGL-enabled browser.

# Quickstart
If you have a WebGL-enabled browser and a directory full of images to process, you can prepare the data for the viewer by installing the dependencies above then running:

pixplot --images "path/to/images/*.jpg"
To see the results of this process, you can start a web server by running:

"# for python 3.x"

python -m http.server 5000


"# for python 2.x"

python -m SimpleHTTPServer 5000

The visualization will then be available at http://localhost:5000/output.
