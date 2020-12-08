# Audiobook
A machine learning project for predicting custumer conversion on an fantasy Audiobook company.

The purpose of this project is the build and model a machine learning algorithm based on neural networks that is able to predict whether the customer will buy again an audiobook.
For that, we have gathered data on various aspects of the client behavior with the product, which will be contain on the file "Audiobooks_data.csv".

The data file contains the data of 14048 customers, each containing 12 aspects, them being:
  1 - Id of the customer
  
  2 - The overall book lenght of all audiobooks
  
  3 - The average book lenght by audiobook
  
  4 - The overall price paid on all audiobooks
  
  5 - The average price paid by audiobook
  
  6 - Whether the customer had review the audibook plataform (1 = left a review, 0 = didn't)
  
  7 - The measurement of the review given by the customer
  
  8 - The total overall minutes listened by the customer 
  
  9 - The completion of the overall audiobooks
  
  10 - The number of support requests
  
  11 - The number of days since the last time the customer interacted with the plataform and the purchase date
  
  12 - Whether the customer bought and audiobook again in the following 6 months
  
 Along with the raw dataset, will be the preprocessed datasets for training, validation and testing as "Audiobooks_training_data.npz", "Audiobooks_validation_data.npz" and "Audiobooks_test_data.npz", respectively.
 
 The code for preprocessing this datasets will also be available, as of right now, it is not optimized, and futher analysis is needed.
 
 Finally, the code for the machine learning model will be available.
