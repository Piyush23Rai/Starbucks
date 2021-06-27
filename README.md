
### Table of Contents

1. [Installation](#installation)
2. [Project Description](#description)
3. [Files in the Repository](#files)
4. [Instructions](#Instructions)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The list of commands required to install necessary libraries are given in requirements.txt file.  The code should run with no issues using Python versions 3.*. 

## Project Description<a name="description"></a>

The exercise is a part of Udacity Data Science NanoDegree Programme. It was orginally a take home assignment for job seeking candidates at Starbucks.

The task is to use the training data and design out a promotion strategy for customers. As sending out promotions to every customers will cannibalize owing to the fact that there will certain segment of customers who behave differently (For e.g. will buy/not buy the product irrespective of Promotion).

A machine learning model is used to understand what patterns in the features (V1-V7; provided abstractly) indicate a promotion to the user. Our Goal will be to maximize following to evaluation metrics.

1. Incremental Response Rate (IRR)
2. Net Incremental Revenue (NIR)

More detailed information for the exercise is given in the Jupyter Notebook. 

For Full description of the take home assignment you may visit this [link](https://drive.google.com/file/d/18klca9Sef1Rs6q8DW4l7o349r8B70qXM/view).



## Files in the Repository<a name="files"></a>

    • Starbucks.ipynb – Jupyter Notebook where exercise was completed
    • Starbucks-Copy_to_start_afresh.ipynb – Jupyter Notebook where you can start from scratch
    • Test.csv – Test data provided by the starbucks.   
    • Training.csv -Training data provided by the starbucks
    • test_results.py – utility file to check how promotion strategy performed and what is the benchmark
    • requirements.txt – List of libraries used in the exercise
    • README.md


## Instructions <a name="Instructions"></a>

1. Install all the necessary libraries in the requirements.txt file
2. Run the Jupyter notebook Starbucks.ipynb till the end to get the results.


## Results<a name="results"></a>

Choosing 75th quantile as our threshold for uplift score (calculated for each customer in the test data), our promotion strategy yielded an IRR of 0.0190 and NIR of 200.50 i.e. it has surpassed the benchmark (what starbucks did, IRR of 0.0188 and NIR of 189.45). 


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The entire exercise is part of Data Science Nanodegree Program offered by UDACITY. It is a great learning exercise backed by a real world problem.

The videos and lectures on A/B testing has guided me towards completing this exercise along with following references.

The modeling aspect of the Exercise was inspired from these two links

1. [Uplift Modelling](https://towardsdatascience.com/uplift-modeling-e38f96b1ef60)
2.[Uplift Modelling Workshop](https://www.slideshare.net/odsc/victor-lomachinelearningpresentation)



