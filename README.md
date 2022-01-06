# masterthesis
Here you can find all the codes and actions used to create and calculate the master thesis. 
All calculations were performed in RStudio.
Thesis at VfB Stuttgart & University of Hohenheim: Data-based position profiles in youth development football.
Measured was the importance of different metrics and the influence on different outcomes like goals, wins and more. 

To calculate the intercorrelation coefficient, the Kappa Fleiss test was applied to the data in the file "Auswertung Fragebogen Kenny ICC".
For the analysis of variance the excel data of "Sosa relevant normiert", "LV u19 relevant normiert" and "Spielervergleich normierte Daten" was used.
To analyze the importance of the chosen metrics and their impact on a positive outcome of the game, a regression model is used. 
To compare both groups a T-Test and a Chi²-Test was performed.
Bootstrapping regression is performed with the boot() function from the car package with 1000 replications. 
The model selection includes the calculations for the AIC.

All preconditions were analyzed before and can be seen in the respective category.
All calculations were done by myself. Data was collected from Wyscout.

#packages needed:
irr; readxl; lawstat; car; dyplr; stats; ggplot
