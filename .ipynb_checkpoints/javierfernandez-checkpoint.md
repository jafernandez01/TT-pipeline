# Semester project

**Name:** Javier Fernandez <br/>
**Semester:** Spring 2019 <br/>
**Project area:** Agronomy

## 1. Background and rationale

Calculations of growing degree days (GDD) are important in models simulating crop growth. The most widely used approach, and often precise, is assuming a linear relationship on the rate with the temperature above a base temperature. It calculates the DTT (daily thermal time) using the average daily value. A second method propose considering the alternation of diurnal and nightly temperatures by using the HTT (hourly thermal time). So far, for grain filling in maize it has not been thoroughly studied whether there is an improvement in models accuracy between these approaches.

I hope that this code will help me to save time when searching for thermal time units (instead of doing it manually) for past and future experiments. In addition, in the future I might be able to quickly retrieve data on multiple weather stations to extend my analysis to other locations through modelling.

## 2. Objective

The objective is to create a code that can determine and calculate the HTT (Hourly Thermal Time) and DTT (Daily Thermal Time) using Kansas Mesonet database for grain filling samples when flowering and sampling date is given by each data point.

## 3. Outcomes:

The main outcome of this code should be a .csv file with three columns: 
   - An ID column identifying each samples (_based on the input file with the data points and dates_) 
   - A second and third columns with the calculated HTT and DTT respectively.
 
## 4. Sketch
<img src="project_sketch.jpg" alt="sketch_image" width="600"/>

## 5. References

1. Bannayan, M., Hoogenboom, G., & Crout, N. M. J. (2004). Photothermal impact on maize performance: a simulation approach. Ecological Modelling, 180(2-3), 277-290.

2. McMaster, G. S., & Wilhelm, W. W. (1997). Growing degree-days: one equation, two interpretations. Agricultural and forest meteorology, 87(4), 291-300.

3. Zhou, G., & Wang, Q. (2018). A new nonlinear method for calculating growing degree days. Scientific reports, 8(1), 10149.