# IMF2WorldBank
Financial Inclusion method performing multi-layer weighting for association between the IMF FAS data (outreach indicators) and the World Bank Global Findex data (usage indicators).

Byunggu Yu, Ph.D. and Vincent Tanoe

April 6, 2020

This Colab notebook uses the International Monetary Fund’s Financial Access Survey (IMF-FAS) data (www.data.imf.org) to measure the outreach of financial inclusion; the World Bank Global Findex data https://globalfindex.worldbank.org/ for the usage of formal financial services.

For predictive modeling, we leveraged a modern gradient descent method to derive multi-layer weighting for association between the IMF data (outreach indicators) and the World Bank data (usage indicators).
Unlike the factor analysis methods, our neural network model uses all given financial inclusion dimensions (lossless data intake), and performs deep multi-layer weighting to model the association between the outreach (as input to the model) and the usage (as output from the model).

This provides key advantages over other reported indices: (1) assessing countries’ financial inclusion in the native data space without manual data selection or weighting processes; (2) estimating or predicting a specific unknown data of a certain country in the World Bank database through a deep learning; (3) being an effective predictor for policy making or development planning in financial inclusion.
