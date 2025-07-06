# Airbnb Business Use Prediction

Airbnb has become a dominant force in the short‐term rental market, offering travelers unique accommodation options that vary widely in price, location, property type, and host interaction. While it has historically catered to leisure travelers seeking authentic local experiences, Airbnb has also seen a rising number of business travelers, prompting listings to cater specifically to corporate needs—often emphasizing convenience, reliability, and proximity to key commercial areas. Recent studies have underscored these shifts: Jang et al. (2019) show that factors like location and smooth booking processes are critical to business guests, whereas Kirchner and Pohl (2024) highlight the increasing “professionalization” of Airbnb, with hosts operating multiple properties more like a formal business.

Against this backdrop, our central research question is:

“Can we predict whether an Airbnb listing is for business purposes based on its features?”

This question will be addressed using a dataset of Airbnb listings from Amsterdam, Athens, and Berlin—three European cities representing different regulatory, cultural, and tourism environments. The dataset includes a range of variables (e.g., price, room type, cleanliness rating, distance from city center), as well as indicators like “biz” (a flag for business‐designated listings). By examining these features, we aim to:

Identify which listing characteristics are most predictive of “business use.”
Assess the importance of location‐based and service‐based factors that may shape business travelers’ preferences.
In the sections that follow, we detail the methodology used to develop a predictive model, present results on the key features driving business listing classification, and discuss implications for hosts, platform operators, and urban policymakers.

The dataset will be divided into training and testing set, the training set will be used for regularization (LASSO - binomial) which is applied to select the predictors among 20 variables, and the testing set will be used to test the accuracy of correctly predicting Airbnb listings for business purposes. This question is significant as it not only helps hosts understand the target market for businesses in terms of Airbnb choices, but it also helps business travellers by filtering business-friendly Airbnb rentals based on features like price and location.

## Acknowledgements
- As Jang et al. (2019) illustrate, business travelers’ priorities differ from leisure guests, suggesting distinct listing attributes may be relevant for predicting business use.
- Kirchner and Pohl (2024) add that Airbnb is becoming increasingly commercial, especially in major urban centers, underscoring the timeliness of examining “business‐oriented” listings in Amsterdam, Athens, and Berlin.
- Soni, Arman. (2025) Assignment 2. UBC
Data source: Kaggle (https://www.kaggle.com/datasets/thedevastator/airbnb-prices-in-european-cities)
