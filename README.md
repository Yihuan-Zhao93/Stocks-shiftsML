# About Stocks-shiftsML
A new ML method for predicting Stocks shifts of fluorescent molecules based only on structural descriptors and the LightGBM algorithm
Based on 15,987 sets Stokes shift data processed with molecular fingerprints, we utilized an ensemble learning approach LightGBM algorithm to construct ML models for the prediction of the Stokes shift. The squared correlation coefficient (R2), the mean absolute error (MAE), and the root mean squared error (RMSE) of the independent test set were found to be 0.86, 12.27 nm and 19.16 nm for optimal model.

# Requirements:
* Python 3.9.12
* Scikit-learn
* Pandas

The files STy.xlsx, STKSAy.xlsx and STKSEy.xlsx correspond to the outputs of the models constructed for Stokes shift, absorption wavelength, and emission wavelength respectively.
File STx.rar serves as the input for the ML model construction.
Unseencases.xlsx contains detailed information on 70 recently reported fluorescent organic compounds.

# Notification of commercial use
Commercialization of this product is prohibited without our permission.
