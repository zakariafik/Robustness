## Steps to reproduce the experiments:

To get the samples of the HDFS data:
- https://github.com/logpai/loghub

To get other data:
	- MNIST: Keras or scikit-learn library
	- Twitter: https://www.kaggle.com/arkhoshghalb/twitter-sentiment-analysis-hatred-speech
	- Adult: https://archive.ics.uci.edu/ml/datasets/Adult

For the full data, access must be requested:
- https://zenodo.org/record/3227177

To parse the HDFS data, use the Drain model from: 
- https://github.com/logpai/logparser

To reduce the HDFS data:
- Generate_HDFS_data.ipynb

The HDFS models are available under:
- https://github.com/logpai/loglizer

The PyTorch implementation of the DeepLog model:
- https://github.com/wuyifan18/DeepLog

To run experiments for Adult, Twitter and MNIST data:
- Robustness-{Adult,Twitter,MNIST}.ipynb

To visualize the results:
- Robustness-Plot.ipynb

Our results are available in the Robustness-{HDFS,Adult,Twitter,MNIST}.csv
