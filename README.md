# Stellar-classification
                                         To Identify Giants and Dwarfs Stars using Machine Learning

Introduction to star classification
- Stellar Classification uses the spectral data of stars to categorize them into different categories. 
- A giant star is a star with substantially larger radius 
- A dwarf star is a star of relatively small size eg. Sun.
- Absolute Magnitude - measure of the luminosity of object if it were viewed from a distance of exactly 10 parsecs (32.6 light-years). 
- B-V Color Index - using two different filters; one a blue (B) filter and a visual (V) filter for green-yellow band.Hot stars appear bluer than cooler stars. Cooler stars are redder than hotter stars. 
- Blue is the hottest color of stars, red is the coolest color they can have. 

Methodology-
- Feature selection, correlation
- ML model - fit Logistic regression(Classification) 

Data includes - 
#TargetClass - Whether the Star is Dwarf (0) or Giant (1); 
#B-V - B-V color index; 
#Amag - Absolute Magnitude of the Star; 
#Plx - Distance Between the Star and the Earth;
#e_Plx - Standard Error of Plx; 
#SpType - Spectral type. 
