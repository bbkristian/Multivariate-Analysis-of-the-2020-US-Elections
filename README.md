# Multivariate-Analysis-of-the-2020-US-Elections
This study aimed to investigate factors influencing voting patterns in the 2020 United States presidential elections, specifically focusing on the percentage of votes received by the Democratic Party's candidates for each state. To understand potential influences, a dataset containing information on votes received by each political party and various socio-economic variables for each state was used. The dataset was cleaned and parsed to ensure usability, and a multilinear regression model was applied to identify significant variables affecting the Democratic Party's vote percentages. Selection models were then used to exclude non-informative variables and validate the final model. The dataset included 50 data points for each variable, representing all US states, but data from the District of Columbia was excluded due to its unique status and significantly different data compared to other states. This study's findings should be interpreted cautiously due to dataset limitations, which only includes information from the 2020 presidential election and does not consider all relevant variables for understanding political behavior in the United States. The study focused on the Democratic Party and did not analyze other types of elections. Despite limitations, **results suggest that higher education levels, smaller gender wage gaps, lower unemployment rates, and higher SARS-CoV-2 vaccination rates may be correlated with a higher percentage of votes for the Democratic Party.**

Libraries Used

caret
car
caTools
crayon
dplyr
effects
forcats
ggplot2
glmnet
graphics
grDevices
grid
gridExtra
lattice
latticeExtra
methods
Matrix
MASS
miscTools
nortest
olsrr
purrr
rcompanion
readxl
Rcmdr
RcmdrMisc
sandwich
stats
stringr
splines
tidyr
tidyverse
tibble
utils
Overview of the Analysis

Load the dataset and explore its structure.
Create a map of the U.S. with the percentage of votes for the Democratic party.
Perform a multilinear regression analysis with all the variables.
Use step-up and step-down methods to find the best model.
Perform a second multilinear regression analysis with the selected variables.
Analyze the residuals and check for multicollinearity.
Perform a cross-validation of the model.
Create appendix plots for each variable against the percentage of Democratic votes.
The project code includes data loading, preprocessing, model training, evaluation, and visualization. The final output consists of several plots showing the relationships between various factors and the percentage of votes for the Democratic party.

You can find the R code and the final analysis for this project in the repository under the prediction_us_votes folder.
