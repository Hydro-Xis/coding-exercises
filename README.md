# coding-exercises

This live repo provides a list of Python coding exercises for new onboarders in Hydro-Xis group, including the following topics: information theory, causal analysis, deep learning, and differentiable modeling.

# Exercises
Below is the list of tentative exercises:
- (TBD) Exercise 1: Entropy and mutual information
- (TBD) Exercise 2: Conditional mutual information and transfer entropy
- (TBD) Exercise 3: Multivariate interaction and partial information decomposition
- (TBD) Exercise 4: Statistical significance test
- (TBD) Exercise 5: Causal inference and PCMCI
- (TBD) Exercise 6: Machine learining basics
- (TBD) Exercise 7: Artificial neural network
- (TBD) Exercise 8: Recurrent neural network
- (TBD) Exercise 9: Convolutional neural network
- (TBD) Exercise 10: Fourier neural operator
- (TBD) Exercise 11: Differentiable programming for hybrid modeling

# (TODO) Prerequisite
As a Python programmer or programmer in general, you are expected to have basic knowledge of the following tools
- Unix shell: The default shell scripts and also a powerful tool that  allows users to perform complex and powerful tasks with just a few keystrokes or lines of code. Please refer to [this short tutorial](https://swcarpentry.github.io/shell-novice/index.html) for its basic usage.
- Git: The version control tool. Please refer to [this short tutorial](https://swcarpentry.github.io/git-novice/) for its basic usage.
- Anaconda: A free and open-source Python distribution that simplifies package management and deployment through its package manager Conda. Please refer to [this post](https://www.anaconda.com/docs/getting-started/getting-started) for the installation of conda. We use the [conda virtual environment](https://docs.conda.io/docs/user-guide/tasks/manage-environments.html) for this repo.

# How-to-guide
Please perform the following steps in your terminal.
 
1. Download the git repo
```sh
git clone https://github.com/Hydro-Xis/coding-exercises.git
```

2. Create Python virtual environment
```sh
conda env create -f environment.yml
```

3. Activate the virtual environment
```sh
conda activate exercises
```

4. Launch an instance of jupyterlab from the command line under this repo:
```sh
jupyter lab
```

5. A Jupyter Lab webpage should pop up and show the contents of the repo. Now you can play with the notebooks in the `exercises` folder!

# Author
Peishi Jiang (peishi.jiang@ua.edu)