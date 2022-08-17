# Ratings-Prediction-NLP
This NLP model is trained to predict the rating of a review on the scale of  1 to 3 (1 being the worst &amp; 3 being the good review)


## Description : 
This model was trained using a dataset containing 20,491 reviews & respective ratings on scale of 1 to 5 (1 = worst, 5 = best) given on TripAdvisor 
website for various hotels given by different visitors. 

Models were struggling to differentiate between raings (1,2) & (4,5) hence during model building the ratings (1 & 2) were merged & labelled as 1, 
rating of 2 was labelled as 2, & ratings (4,5) were merged & labelled as 3.

Hence, Final predictions made by model are on a scale of 1 to 3.
