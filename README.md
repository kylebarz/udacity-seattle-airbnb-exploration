# UDacity: Explore & Blog About Seattle AirBNB Data
UDacity: Explore Seattle AirBNB Data and Blog Insights

## Overview <a name="overview"></a>

This UDacity project required the explorartation of data made available by AirBNB and blogging any relevant insights. I have taken the approach of sharing insights for potential travelers looking for rooms. 

### Prerequisites <a name="prerequisites"></a>

I originally developed this with Jupyter powered by Azure Notebooks. 

1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn
5. Kaggle

### Installing <a name="installing"></a>

The Jupyter Notebook is self-contained, including the installation of the Kaggle package to download the data. If you use this
package and download the data through the API, you will be required to download your Kaggle API Access key through your 
account overview on www.kaggle.com. Once uploaded, the script will move the .json file to the appropriate location. 

## Data Analyzed

1. I explored the differences in rates across the various neighborhoods in Seattle. I confirmed that some neighborhoods are significantly over- & under- the overall Seattle average.

2. I explored the evolution of the nightly rates by the time of the year. The Summer months (May - August) cost more than the other the seasons. 

3. Given the differences of average rates by neighborhood, I applied both a quartile and decile to each listing to explore price availability by neighborhood. This shows the distribution of prices/availability by neighborhood.

4. Finally, I explored the top 10 hosts in Seattle.


## Acknowledgments

Thanks to AirBnB for publishing the dataset and Kaggle for hosting it. The dataset is available at: https://www.kaggle.com/airbnb/seattle
