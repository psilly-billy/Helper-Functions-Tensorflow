# Helper-Functions-Tensorflow

Get helper functions file
```python

import os 

if not os.path.exists("Tensorflow_helper_functions.py"):
    !wget https://raw.githubusercontent.com/psilly-billy/Helper-Functions-Tensorflow/main/Tensorflow_helper_functions.py
else:
    print("[INFO] 'Tensorflow_helper_functions.py' already exists, skipping download.")
[INFO] 'Tensorflow_helper_functions.py' already exists, skipping download.
# Import series of helper functions for the notebook (we've created/used these in previous notebooks)
from helper_functions import create_tensorboard_callback, plot_loss_curves, compare_historys
```
