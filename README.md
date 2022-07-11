# Clustering Countries Basis of Developement and need of Help

The following dataset has been provided by the 'HELP Orgainization'(an international humanitarian NGO) which contains all the Socio-Economic and Health Standards information of all the countries in the world.
'Country-data.csv' has features like country , exports, imports, health, gdpp, life expectancy and many more. 'data-dictionary.csv' files contains the description of the dataset.

## MAIN OBJECTIVE : 
Our primary goal is to develop a model that helps in clustering of countries so as to easily classify countries with respect to their development and which countries need help.

The overview of the steps to perform:
1) Data Visualization
2) Data Cleaning A) Eliminate NA/Null Data Records B) Feature Engineering . 
3) Tranforming and Scaling of Data
4) Run Unsupervised Models
5) Optimize the best model
6) Predict Results and Best Model
7) Conclusions

## DATASET : 
Data columns (total 10 columns):<br><br>
 &nbsp; **#**  &nbsp;&nbsp;    **Column**    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    **Dtype** <br>
 --- &nbsp;  --------    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    ------<br>
0  &nbsp;&nbsp;&nbsp;&nbsp;       country   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;     object <br>
1  &nbsp;&nbsp;&nbsp;&nbsp;      child_mort &nbsp;&nbsp;   float64<br>
2  &nbsp;&nbsp;&nbsp;&nbsp;       exports   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    float64<br>
3  &nbsp;&nbsp;&nbsp;&nbsp;      health    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   float64<br>
4  &nbsp;&nbsp;&nbsp;&nbsp;    imports     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; float64<br>
5  &nbsp;&nbsp;&nbsp;&nbsp;     income     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   int64<br>
6  &nbsp;&nbsp;&nbsp;&nbsp;     inflation  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  float64<br>
7  &nbsp;&nbsp;&nbsp;&nbsp;     life_expec &nbsp;&nbsp;&nbsp;&nbsp;   float64<br>
8  &nbsp;&nbsp;&nbsp;&nbsp;     total_fer &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   float64   <br>
9  &nbsp;&nbsp;&nbsp;&nbsp;      gdpp      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   int64<br>


## CONCLUSION
I have successfully classified all the countries into 'Needs Help' , 'Might Need Help' and 'Do Not Need Help'.
1. Most of the American and European Countries may not need help.
2. Most of the African countries and Middle Eastern countries like Iraq, Yemen , or countries like Afghanisthan , Pakisthan require help.
3. Most of the remaining Asian Countries Might require help, lying in between the two classes.

Thus, this completes our analysis with a KMeans Model of K=3 having distortion (15.22) for classifying our Country.csv dataset.

