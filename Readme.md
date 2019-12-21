## Project Write a data science blog post

1. Project Motivation
2. Questions answered
3. Method and Results
4. File Descriptions
5. Used Libraries
6. Installations and Dependencies
7. Licensing, Authors, Acknowledgements, etc.

## Project Motivation

this project wants to examine starbuck's offerings. it is the final thesis and a little challenge.

## Questions answered

With the available data, i.e. offers, customer profiles and transactional data, I asked myself the following questions:

Who are Starbucks customers (gender and age)
What income do customers have and what do they spend
How can offers be assigned to customers (offer, age group, gender)
Which offers are most accepted by customers (type of offer, customer group (m / f / c / d))

The article detailing the key findings of this project can be found [here](https://medium.com/@geraldfranzkrieg/).

## Method and Results

The project followed the CRISP-DM method of data exploration's six steps of:
1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation, design and show the results
6. Deployment

The developed code  for the analysis can he found in the [notebook](https://github.com/gerald-e/StarbuckCapstone/blob/master/Starbucks_Capstone_notebook.ipynb).


## File Descriptions

* `Starbucks_Capstone_notebook.ipynb` contains the Python notebook containing all steps and further explanation for this analysis
* `./figure/*.jpg` are the outputs from all jpegs
* `./figure/*.png` are the outputs from all png
* `./figure/*.html` are the results from HTML GeoInformation
* `./data/*` are all nesaccery data for this analysis
* `Readme.md` this file

## Used Libraries

The following libraries are required to run the notebook:

* matplotlib
* numpy
* pandas
* sklearn


## Installations and Dependencies

Each directory has a `requirements.txt` describing the minimal dependencies required to run the notebooks in that directory.

### Installations via pip

To install these dependencies with pip, you can issue `pip3 install -r requirements.txt`.


## Licensing, Authors, Acknowledgements, etc.

You can the Licensing for the data and other descriptive information is available at Udacity Data Science Nanodegree project. Otherwise, feel free to use the code here as you wish.
