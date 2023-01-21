---
weight: 1
title: "When To Use"
date: 2022-02-17T00:26:01-05:00
draft: false
---

{{< toc-tree >}}


Monte Carlo Methods can be used on almost **every stage** of the project lifecycle. There are three main methods to forecast estimates with the Monte Carlo Simulation. Which one you use depends on the input data you have available.

# Pre-Scoping and Scoping Phases
This step can be considered as prerequisite in the project lifecycle. At this stage, project details are mostly unknown. 
There are 2 ways to use the Monte Carlo Simulation at this phase:
## 1. Confidence Simulation ##
In order to generate an unbiased selection, we need to let the simulation to evolve randomly. 
For this approach, the team should roughly estimate at least 3 different suggestions of how long they think the project will take. For each of these 3 estimations provide a corresponding confidence level, where the sum of these values equals 100%.

{{< hint  >}}
*Example:* 

The team thinks that this project should take somewhere between 3 and 6 months to complete. They reveal their confidence level regarding the suggested range:

3 months -> 30% confidence *(best case scenario)*  
4 months -> 40% confidence  *(most likely)*  
6 months -> 30% confidence  *(worst case scenario)*  

{{< /hint >}}

## 2. Monte Carlo Historical Simulation ##

##### Input : At least 5 completed projects; new project's rough estimate #####

This Monte Carlo Simulation method is based on generating a forecast based on the historical data. To be able to proceed with this approach, the team needs to have a history of at least 5 completed project as the model will use these projects as the data source.  

The best time to use this method is when you already have a very rough estimate and you need to find out the risk of the delay. After analyzing original estimate and the final cost of the previous projects, the model will reveal a potential deviation from your new rough estimate. 


## Technical Design Phase

During the technical design phase, all of the above methods can be used as well, especially if more clarity is provided. In case the project is ticketed out and we are trying to find a more realistic end date for the project, `Confidence Simulation` can be used for each ticket as a bulk simulation. 

If the team tends to 


## Project is in Progress

