# Time Series modelling of Crypto Currencies


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#code-usage">Code Usage</a>
      <ul>
        <li><a href="#Regression">Regression</a></li>
        <li><a href="#Classification">Classification</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#reference">Reference</a></li>    

    
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

We are Frankfurt School (FS) students who are currently pursing Masters in Applied Data Science. As part of our Deep learning course we had perform Time series analysis to predict the returns from 10 Crypto coins. We have performed wide range of Exploratory Data Analysis (EDA) and applied from basic Machine Learning(ML) algorthms to advanced Neural Network analysis. 

We have followed both classification and regression approach to understand which is more accurate with the predictions. We attached the notebooks for both in the repo.


![Product Name Screen Shot](https://github.com/chaitanya2593/Crypto_Timeseries_Analysis/blob/main/overview.png)




<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* Python
  * Data science packages 
  * tensorflow
  * Plotly
  * seglearn
* Google Colab



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Code development is performed in the google drive, Google colab notebooks are used for development. Colab already has 
required data science packages preinstalled and provided the pip (python package installer) commands where it is required.

### Prerequisites

* The user should have an google account and access to the google drive as well.
* Please install the packages listed in the requirements.txt by `pip install -r requirements.txt`

  
### Installation

You can simply go to Google Colab and you can choose 'GitHub' on the box which you can see when you just go to the Colab site and login. Colab will automatically redirect you to github in order to authorize your github account. Then you can choose repository to use at Google Colab!

- Share google drive folders mentioned in the notebooks to the mounting drive before starting executing 
- Please mount the google drive and execute the notebooks cell



<!-- USAGE EXAMPLES -->
## Code Usage  



### Regression  

Overall end-to-end process has been divided into 3 steps. The execution of the files should also be in the same order.
In individual the required input files are already mentioned in the code comments.We have three ipynb files in this folder, the first one for EDA and  classical modelling; LGBM, XGB,RF, Elastic Net Regression, second one for LSTM model and the final one for ARIMA.

- 01_Time_Series_Regression_LGBM_XGBOOST_RF_Elastic_Net_LR.ipynb
    - EDA and  classical modelling; LGBM, XGB,RF, Elastic Net Regression
- 02_LSTM_model.ipynb
  -	LSTM model
- 03_ARIMA.ipynb
  -	ARIMA model
 

### Classification
Overall end-to-end process has been divided into 5 steps. we have applied wide range of algorithms with different datasets.
- 0_preprocess_data.ipynb
  - The script is developed to pool the data together and generate hourly/daily/weekly data
- 1_Classification_Hourly/Daily_EDA.ipynb
  - In this script, we tried to explore partial correlation and seasonality of our target variable. After deciding to use daily data, there are additional EDA for only daily data
- 2_model_building_tuning_F3.ipynb
  - In this script, we only use columns provided in original data and time variables to build dummy classifier, random forest and LGBM
- 3_model_building_tuning_F13.ipynb
  - In this script, we generate lag, technical analysis and market features and apply dummy, random forest, XGB and LSTM classifier
- 4_model_building_LSTM_F13.ipynb
  - In this script, we use new features, roll the data and apply LSTM
- 5_model_Testing_F13.ipynb
  - This script is developed to plot the comparison between different models

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- LICENSE -->
## License

Distributed under the GNU License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Students from Frankfurt school - MADS class of 2023.

1. [Eduardo Garcia](https://github.com/egarcia00), 
2. [Nari Kim](https://github.com/gooodmood), 
3. [Thi Anh Ba Dang](https://github.com/chloe68),
4. [Vishnu Prabhakar](https://github.com/vishnuprabhakar619), 
5. [VS Chaitanya Madduri](https://github.com/chaitanya2593), 
6. [Yumeng Zhang](https://github.com/ppage0211)

Project Link: [https://github.com/chaitanya2593/Crypto_Timeseries_Analysis.git](https://github.com/chaitanya2593/Crypto_Timeseries_Analysis.git)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->  
## Reference

* Ensemble Deep Learning Models for Forecasting Cryptocurrency Time-Series → [https://www.mdpi.com/1999-4893/13/5/121/htm](https://www.mdpi.com/1999-4893/13/5/121/htm)
* Deep Learning Algorithm to Predict Cryptocurrency Fluctuation Prices: Increasing Investment Awareness → [https://www.mdpi.com/2079-9292/11/15/2349/pdf?version=1659092830](https://www.mdpi.com/2079-9292/11/15/2349/pdf?version=1659092830)
* LSTM code implementation: [https://towardsdatascience.com/cryptocurrency-price-prediction-using-lstms-tensorflow-for-hackers-part-iii-264fcdbccd3f](https://towardsdatascience.com/cryptocurrency-price-prediction-using-lstms-tensorflow-for-hackers-part-iii-264fcdbccd3f)
* Multi-class classification: [https://towardsdatascience.com/comprehensive-guide-on-multiclass-classification-metrics-af94cfb83fbd](https://towardsdatascience.com/comprehensive-guide-on-multiclass-classification-metrics-af94cfb83fbd)


<p align="right">(<a href="#readme-top">back to top</a>)</p>


