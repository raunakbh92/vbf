# vbf
Implementation of Deep Variational Bayes Filter. Example command:

`python3 train_bayes_filter.py --seq_length 32 --extractor_size 64 64 --inference_size 64 64  --kl_weight 0.1`

# Notes
- tensorflow version 1.12
- gym environments acrobot and cartpole need to be modified to allow continuous actions.
See how pendulum does it and repeat
- Use python3
