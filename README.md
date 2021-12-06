# Deep Reinforcement Learning (DRL) with Generative Adversarial Network (GAN) for Network Intrusion Detection System (NIDS)

To run code, ensure you have the latest version of Anaconda (and are in the repository directory) and run the commands:

```
$ cd src
$ conda env create -f ids_env.yml
$ conda activate NetSecurity-ML
```
Each notebook is focused on the following:

i. **preprocessing.ipynb**: preprocessing and creation of train, test, validation sets of the CIC-IDS 2017 dataset presented here: http://205.174.165.80/CICDataset/CIC-IDS-2017/Dataset/.
ii. **setup_and_training.ipynb**: Building the DRL model and training on the CIC-IDS 2017 dataset.
iii. **setup_and_training_NSL-KDD.ipynb**: Building the DRL model and training on the NSL-KDD dataset (already preprocessed and stored in the directory as a .csv file)
iv. **setup_and_training_NSL-KDD-GAN-Generated_Data.ipynb**: Building the DRL model and training on the GAN-generated dataset based off of the NSL-KDD (already preprocessed and stored in the directory as a .csv file)
v. **preprocessing_NSL-KDD.ipynb**: Added file if you would like to preprocess the NSL-KDD dataset yourself.
