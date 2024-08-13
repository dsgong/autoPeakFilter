# Auto Peak Filter
Some jupyter notebook experiments involving automatic filter generation to match the magnitude and phase response of a speaker's impedance. 

## BilinearTest.ipynb 
Generate digital filter to model impedance by applying the bilinear transform to an analog filter created from the equivalent circuit.

## Farina.ipynb
Measure a speaker's impedance response with an exponential sine sweep using the Farina method. Write the impedance numbers to a text file.

## RegressionTest.ipynb
Perform least squares regression to improve the digital filter matching to a speaker's impedance response. 