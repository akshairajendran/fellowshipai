# fellowshipai
## Fellowship.AI Challenge Kernel
This repository contains the kernel for my challenge submission to Fellowship.AI. I've chosen to do the Food-101 challenge, which per Fellowship.AI's [website](https://fellowship.ai/) is described as follows:
> [Food-101](https://www.vision.ee.ethz.ch/datasets_extra/food-101/) is a challenging vision problem, but everyone can relate to it.  Recent SoTA is ~80% top-1, 90% top-5.  These approaches rely on lots of TTA, large networks and  even novel architectures.
>Train a decent model >85% accuracy for top-1 for the test set, using a ResNet50 or smaller network with a reasonable set of augmentations.

## Layout
In the food-101 folder there is a data folder and main.ipynb notebook. The data folder contains a Bash script that downloads and unzips all of the necessary data, but does not contain the actual data itself for space reasons. The notebook contains everything needed to load the data, train the model and ultimately test the model. The notebook is completely self-documenting and describes the process and results in depth.
