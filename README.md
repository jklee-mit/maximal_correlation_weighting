# maximal_correlation_weighting

This is the code for the Maximal Correlation Weighting algorithm.

Note: code for downloading and preparing the Dogs and Tiny ImageNet datasets is not yet available. The preprocessed Cifar-100 dataset files are already included in the "datasets" folder. For the Stanford Dogs and Tiny ImageNet datasets, is suffices to download the datasets and unzip them into the folder labeled "datasets" in the main directory.

nets.py contains the LeNet architecture used for the experiments

datasets.py contains the dataloaders for the datasets

main.py contains the main code for the MCW method. To use, change "mode" on line 4 to the appropriate dataset, and change the number of source samples in line 5 as needed.