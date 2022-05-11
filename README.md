# seattle-airbnb


This project is about:

*Coming up with three questions

*Extracting the necessary data to answer these questions.

*Performing necessary cleaning, analysis, and modeling.

*Evaluating results.

*Sharing insights with stakeholders.

I have used Seattle AirBnB dataset(https://www.kaggle.com/airbnb/seattle) to answer the following questions and find predictive variables for price.
  - Find what features affect an Airbnb price based on the features in the listings.csv
  - Find what is the trend of price change during an year.
  - Find what is the trend of prices change during a week.


## Getting Started

Instructions below will help you setup your local machine to run the copy of this project.

### Prerequisites

####  Requirements

  - Anaconda 3
  - Python 3.7.3
  - matplotlib 
  - seaborn 
  - numpy 
  - pandas
  


#### Running the notebook

  - add the dependencies in your environment.yml and install it in a conda environment
  - Run the commands below in your working directory to open the project in jupyter lab:
    ```
    git clone https://github.com/arjun-pp/seattle-airbnb.git
    
    jupyter notebook 
    
   
    ```
  - run seattle-airbnb.ipynb: This notebook includes the preliminary work, explorations.
  
## Summary
Price depends on 'accommodates', 'bathrooms', 'bedrooms', 'beds', 'guests_included', 'neighbourhood_group_cleansed', 'property_type', 'room_type', 'bed_type', 'cancellation_policy', 'zipcode'. An r2 score of 0.65 was achieved in this experiment using Linear Regression.

Price also varies during an year and is highest during Jun and July. Also there is a pattern within a week and price is highest on Fridays and Saturdays. 

## Acknowledgements

* Kaggle
* Stackoverflow
