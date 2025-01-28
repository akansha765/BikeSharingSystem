# Bike Sharing Demand Prediction
> A project to predict daily bike-sharing demand using a multiple linear regression model.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- **Background**: This project aims to predict the daily demand for bike-sharing services based on historical data. The dataset includes factors such as weather conditions, holidays, and seasonal trends.
- **Business Problem**: BoomBikes, a US-based bike-sharing service provider, suffered a dip in revenue during the COVID-19 pandemic. This project provides insights into the factors affecting bike-sharing demand to help the company develop strategies to meet customer expectations and increase revenue.
- **Dataset Used**: The dataset, `day.csv`, contains 730 observations over two years (2018-2019) and includes information on weather, seasons, and bike rentals.

## Technologies Used
- Python 3.11
- Libraries:
  - pandas (version 1.5.3)
  - numpy (version 1.23.5)
  - scikit-learn (version 1.2.2)
  - matplotlib (version 3.7.1)
  - seaborn (version 0.12.2)

## Conclusions
- **Seasonality**: Bike rentals are highest during the summer and fall seasons, indicating a strong influence of weather on demand.
- **Weather Conditions**: Clear weather significantly increases bike rentals, while adverse conditions such as rain or snow reduce demand.
- **Temperature and Humidity**: Temperature positively correlates with demand, while higher humidity tends to lower rentals.
- **Working Days**: Weekdays have higher rentals compared to holidays and weekends, indicating a strong demand among commuters.

## Acknowledgements
- This project was inspired by the dataset used in the research paper:
  - Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge," Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.
- Special thanks to the creators of the dataset and the contributors of the libraries used in this analysis.

## Contact
Created by Akansha Yatta - feel free to contact me for further details!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

