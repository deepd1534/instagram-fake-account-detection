# Instagram Fake Account Detection Project
The aim of this project is to build and train a deep neural network model to detect fake or spam instagram accounts.

**<H3 align:right>FAKE INSTAGRAM ACOUNT DETECTOR</H3>** 

---
**<h4>UNDERSTANDING THE PROBLEM**



* This project aim is to build and train a deep neural network model to detect fake or spam instagram accounts.
*  These days spam accounts have become a major problem in in all the social media platforms.
* Many users are creating fake accounts to create an illusion of having many followers to thier personal accounts.
*  Fake accounts are being created to sell fake products and services. 
*  They are also being used to impersonate other account users from common people to celebrities in order to influence, criticize, hurt feelings and reputation.


*  There are few key input features which we considered to determine if the account is fake or not.

*   THE *INPUT FEATURES* ARE:

1.   **PROFILE PICTURE** - The user has profile picture or not.
2.   **NUMS/LENGTH USERNAM**E - The ratio of number of numerical chars in username to its length.
3.  **FULLNAME WORDS** - Full name in word tokens
4.   **NAME/LENGTH OF FULL NAME** - The ratio of number of numerical characters in full name to its length.
5.   **NAME == USERNAME** - Are username and full name literally the same?
6.   **DESCRIPTION LENGTH** - Bio length in characters.
7.   **EXTERNAL URL** - Has external URL or not.
8.   **PRIVATE** - Private or not.
9.   **POSTS** - Number of posts.
10.  **FOLLOWERS** - Number of followers.
11.  **FOLLOWS** - Number of follows.

  
  *<h4> TRAINED DETECTOR MODEL:**

This model is trained such that it considers the above given features and determines whether a particular account is fake or not. By resulting the output as either 0 or 1 meaning TRUSTED or FAKE respectively. Our intention is to make this software capable of thinking like a human, based on the data it is given and results in maximum probability of success.
  
**HOW TO RUN THE CODE**

This is an executable [*Jupyter notebook*](https://jupyter.org) You can run and experiment with the code in a couple of ways: *using free online resources* (recommended) or *on your own computer*.

#### Option 1: Running using free online resources using Google Colab or on Binder
  https://mybinder.org/

#### Option 2: Running on your computer locally

1. Install Conda by [following these instructions](https://conda.io/projects/conda/en/latest/user-guide/install/index.html). Add Conda binaries to your system `PATH`, so you can use the `conda` command on your terminal.

2. Create a Conda environment and install the required libraries by running required commands on the terminal.

You can now access Jupyter's web interface by clicking the link that shows up on the terminal or by visiting http://localhost:8888 on your browser. Click on the notebook file (it has a `.ipynb` extension) to open it.

  
  **<h2> REFERENCES : </h2>**
Check out the following resources to learn more about the tools and libraries used in this notebook:

<i>


* Pandas user guide: https://pandas.pydata.org/docs/user_guide/index.html

* Matplotlib user guide: https://matplotlib.org/3.3.1/users/index.html

* Seaborn user guide & tutorial: https://seaborn.pydata.org/tutorial.html

* Tensorflow user guide : https://www.tensorflow.org/guide

* Tensorflow Playground : https://playground.tensorflow.org

* Neural Networks : https://towardsdatascience.com/the-mostly-complete-chart-of-neural-networks-explained-3fb6f2367464





