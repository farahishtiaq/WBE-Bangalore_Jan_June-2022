# WBE-Bangalore_Jan_June-2022

We sampled influent wastewater from 28 sewage treatment plants (STPs) in Bangalore. Grab Ssamples were collected once a week from each STP (January-June 2022) The normalised temporal trend of SARS-CoV-2 RNA in wastewater and new positive cases in Bangalore city from January-June 2022. By investigating viral RNA concentrations in the wastewater and correlating it with community testing data on a weekly basis, we generated an early and real-time map of COVID-19 infection dynamics in the city. We conducted two main analyses using the raw and normalised viral load. At the citywide level, we calculated the daily viral load, VL (copies/d) for SARS-CoV-2, by normalizing C (copies/mL) to the average daily STP flow, Q(L/d) using equation 1) and P is the population of inhabitants the catchment of the respective sewershed.

VL=(C×Q×(10)^3)/P                          equation (1)

(i) 	Spatial and temporal dynamics in viral load copies by STPs and at the citywide level

To understand spatial and temporal changes in viral load, we used an Exponentially Weighted Moving Average (EWMA) as the monitoring algorithm to detect moderate and persistent shifts in cases. 

(ii) Estimation of infected individuals by STP and citywide

We estimated the number of infected individuals by each STP and citywide. The prevalence of SARS-CoV-2 infection within the catchment of each STP was estimated using the total number of viral RNA copies in wastewater each day, as measured in wastewater by RT-qPCR, and the number of SARS-CoV-2 RNA copies shed in stool by an infected following Ahmed et al. equation 2

![image](https://user-images.githubusercontent.com/117061166/198938822-479a0ce5-97bb-4320-afb7-ffe79faaf929.png)    equation (2)

The daily flow rate of wastewater was calculated for each sewershed using the product of the population of each catchment area and the observed average per capita wastewater rate of 100L/person/day. The daily stool mass of 128 g was used as per Rose et al. (2015) and one person sheds SARS-CoV-2 RNA 107copies/g of feces as per Foladori et al. (2020). 

