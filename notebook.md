#Thoughts
* Need to decide what function to make driver lifetime value in order to make SL algo
* Initial idea: multiply ride distance by ride duration
* Looking at the charts on the notebook, the best driver would be the one who can cover the most distance in the least amounnt of time, in conjunction with being the one who drives the most often (number of rides) with as many rides as possible being prime time rides.
* Lyft essentially wants there to be a greater supply of drivers than riders, since the drivers only get paid when there are riders. So, the > the amt of riders, the better Lyft does and we need to make the riders happy by havin gthe shortest rides. 
# Where I am leaving off (9/5 Early Morning)
* Make histogram to see how the number of rides varies per driver, along with duration of drives, and distance of drives. These should be normally distributed. Prime Time should also be looked at, that is interesting to lo0ok at as well. 
* Finish the value function definition of what ideal driver would be

#Thoughts that occured to me when trying to sleep
* We can use k-means clustering or gmm to visualize the different drivers
* We would need to look at each driver and average stats for each ride for them, or we could just plot rides at first
* It might be complicatd since we leave out the number of riddes a driver does, which would make them more valuable 

# Questions to Answer

1.Recommend a Driver's Lifetime Value (i.e., the value of a driver to Lyft over the entire projected lifetime of a driver).
2. Please answer the following questions:
a. What are the main factors that affect a driver's lifetime value?
b. What is the average projected lifetime of a driver? That is, once a driver is onboarded, how long do they typically continue driving with Lyft?
c. Do all drivers act alike? Are there specific segments of drivers that generate more value for Lyft than the average driver?
d. What actionable recommendations are there for the business?
* Hire us
3. Prepare and submit a writeup of your findings for consumption by a cross-functional
audience.
