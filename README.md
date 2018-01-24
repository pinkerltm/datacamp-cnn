# Setup

* `virtualenv --system-site-packages ~/dev/venv/tf`
* `source ~/dev/venv/tf/bin/activate`
* Install python dependencies
  * On Systems with CUDA enabled: `pip3 install -r requirements_GPU.txt`
  * Without CUDA (only on CPU): `pip3 install -r requirements_CPU.txt`

# Run
* `jupyter notebook`
* browse to [http://localhost:8888/notebooks/cnn-fashion-mnist.ipynb](http://localhost:9000/cnn-fashion-mnist.ipynb)