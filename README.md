# statrethinking_lectures_numpyro
Repository for working through [Statistical Rethinking](https://xcelab.net/rm/statistical-rethinking/) [lectures](https://github.com/rmcelreath/statrethinking_winter2019) using [numpyro](https://num.pyro.ai/en/stable/index.html#)

## Instructions
Here are steps to get started with this repo:-

* Install [conda](https://docs.conda.io/en/latest/miniconda.html) as per your OS instructions. You can skip this step if you already have conda installed on your machine.
*  Clone the repository
  ```
  git clone git@github.com:s-mishra/statrethinking_lectures_numpyro.git
  cd statrethinking_lectures_numpyro
  ```
* Create new environment from the yml file provided
  ```
  conda env create -f environment.yml

  ## you check that this environment has been created using the command
  conda info --envs
  ```
* Activate the `statrethinking` environment
  ```
  conda activate statrethinking
  ```
* Now you can use python however you want. If you want to use notebooks start a jupyter notebook/lab server here and start working
  ```
  jupyter notebook
  ```
    or

    ```
    jupyter lab
    ```
* Once you are done you can just deactivate the environment using
  ```
  conda deactivate
  ```
* To make working with the book and lectures easy we have copied the data directory from the official [rethinking package](https://github.com/rmcelreath/rethinking/tree/master/data) here in data directory. 


