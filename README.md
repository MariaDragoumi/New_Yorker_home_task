# New Yorker home task
In this repository I upoloaded my solution to the home task assigned to me during my application to New Yorker as a Data Scientist.

### Briefing of the assignment:

Let’s imagine you have historical data of clients’ receipts and your manager
asks you to examine this data to figure out which items are often - or rarely -
being sold together.
Please, design a report that will answer your manager’s questions, implemented
with Python and the tools of your choice.

Use the following Kaggle datasets for the tasks (this dataset is from Kaggle
competitions but we are interested only in the data, so you can ignore Kaggle’s tasks):

https://www.kaggle.com/c/h-and-m-personalized-fashion-recommendations/overview.

Once you are done, create a short presentation explaining your findings.


## My solution

To approach the problem I created a jupiter notebook file where one can run one-by-one the blocks of code and guide through my findings. 

Running requirments:

- Jupyter Notebook (for installation: https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/install.html)
- Python3 (3.9)
- Pandas (1.3.5)
- matplotlib (3.5.1)

To run the code:

1) On the terminal, navigate to a desired folder and clone this repository:

```console
git clone https://github.com/MariaDragoumi/New_Yorker_home_task.git
```

and change into the folder:

```console
cd New_Yorker_home_task
```

2) Create a folder calded *data*:

```console
mkdir data
cd data
```

and download the data from kaggle:

using the api:
```console
kaggle competitions download -c h-and-m-personalized-fashion-recommendations
```
(see here for installation of the kaggle api: https://github.com/Kaggle/kaggle-api)

or download from tthe website: 

https://www.kaggle.com/c/h-and-m-personalized-fashion-recommendations/overview

and save them in the *data* folder.

3) Change back to the *New_Yorker_home_task* and run the notebook:

```console
cd ..
```

```console
jupyter-notebook new_yorker_home_task.ipynb
```


