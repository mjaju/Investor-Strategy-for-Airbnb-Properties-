# Investor-Strategy-for-Airbnb-Properties-
Data Mining and ML modeling on Airbnb Data (Austin) that gives an understanding of how different factors affect booking rates and prices.  
In order to perfomr ensembling methods, we first need to make sure the data is in the correct format and is cleaned. Find the [data processing code](https://github.com/mjaju/Investor-Strategy-for-Airbnb-Properties-/blob/main/Data_Preparation_XGBoost.Rmd) here.  
You can find the [XG Boost code ](https://github.com/mjaju/Investor-Strategy-for-Airbnb-Properties-/blob/main/Data_Preparation_XGBoost.Rmd) here.  

Libraries used : 
library("tidyverse")  
library("tidymodels")  
library("plotly")  
library("skimr")  
library("caret")  
library("ggrepel")  
library("mice")  
library("rockchalk")  
library("Hmisc")  
library("stringr")  
library("tidytext")  
library("gsubfn")  
library("tm")  
library("stopwords")  
library("gridExtra")  
library("lattice")  
library("factoextra")  
library("cowplot")  
library("topicmodels")  
library("glmnet")  
library("leaflet")  
library("leaflet.extras")  
library("wordcloud")  
library("wordcloud2")  
library("tm")  
library("RColorBrewer")  
library("dataPreparation")  
library("udpipe")  
library("lubridate")  
  
Please find the report of the findings from the machine learning and ensembling models (XGBoost) in the report attached. 
To run the files, download the data set from the kaggle link : https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings/data
