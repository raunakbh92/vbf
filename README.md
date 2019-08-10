# vbf
Implementation of Deep Variational Bayes Filter. Example command:

`python3 train_bayes_filter.py --seq_length 32 --extractor_size 64 64 --inference_size 64 64  --kl_weight 0.1`

# Notes
- gym environments acrobot and cartpole need to be modified to allow continuous actions.
See how pendulum does it and repeat

# Install instructions
- Make virtual environment with python 3.6
```
(base) raunak@bombay:/scratch/tensorflow$ conda create -n tensorflow python=3.6
```
- Activate the virtualenv
```
(base) raunak@bombay:/scratch/tensorflow$ conda activate tensorflow
(tensorflow) raunak@bombay:/scratch/tensorflow$ 
```

- Install tensorflow 1.12
```
(tensorflow) raunak@bombay:/scratch/vbf$ pip install --upgrade tensorflow==1.12
```

- Install gym, progressbar, matplotlib
```
(tensorflow) raunak@bombay:/scratch/vbf$ pip install progressbar
(tensorflow) raunak@bombay:/scratch/vbf$ pip install gym
(tensorflow) raunak@bombay:/scratch/vbf$ pip install matplotlib
```

- Install tex fonts and stuff
```
(tensorflow) raunak@bombay:/scratch/vbf$ sudo apt-get install dvipng texlive-latex-extra texlive-fonts-recommended
```
- Create directory to store resulting images
```
(tensorflow) raunak@bombay:/scratch/vbf$ mkdir bf_predictions
```
