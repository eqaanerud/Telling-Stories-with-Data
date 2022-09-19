## Critique by Design: Simplfying CUNA

Original Visualization: 

<img width="785" alt="Screen Shot 2022-09-17 at 6 54 32 PM" src="https://user-images.githubusercontent.com/112351182/190933475-59de11d0-d652-49bd-aff9-4535e7987a8a.png">

Source: Theater Communications Group, Theatres at the Crossroads: Overcoming Downtrends & Protecting Your Organization Through Future Downturns

## My First Thoughts After Seeing this Visualization
This is a declarative and data-driven visualization, otherwise known as an “everyday data visualization." The designers are trying to illustrate how the 2008-2009 recession affected the bottom line of many theatres, otherwise known as “CUNA” (Cumulated Unrestricted Net Assets). 

The most prevalent feeling I have about this data visualization is that I don’t want to take the time to review and digest all the information it is throwing at me. I’m reminded of the Good Charts principle that we only see a few things at once. I think that the graph is asking too much of the viewer, especially to make connections between the six different colors and all the percentages. What immediately stands out to me is how the percentages are displayed, and how each vertical line intersects those percentages and makes them indistinguishable. 

Just like in one of our very first visualization exercises, the data rainbow here is aesthetically appealing at the outset, but ultimately overwhelming and confusing. Each color represents six different categorizations of CUNA, if the CUNA was positive, negative, or break-even, and what percentage the CUNA was of the organization’s budget. 

Additionally, the designers utilize percentages to represent both the theatres in each CUNA category, and CUNA as a percent of the budget. Without reading the title, I initially thought that the percentages in the center of the visualization represented what percentage CUNA was of the budget, which is wrong. When I work on redesigning this visualization, I will prioritize limiting the number of CUNA categories in the legend and the use of percentages. 

The number of percentages also brings me to reflect on the sheer amount of data this visualization is presenting. The title indicates that we should be focusing on the recession and the “extent of deficits and surpluses over time.” The breadth of theater data being represented from 2004 to 2017 conflates the graph’s usefulness, because we should really be focusing on the 2008 to 2009 period. The “negative CUNA greater than 20% of the budget” variance is very minimal in the years other than during the Great Recession. This graph needs significantly less information being presented. 

The graph does successfully illustrate the change in CUNA during the Great Recession. Although the black color and composition of the black box to highlight the Great Recession period is a bit difficult to differentiate from the graph, it does provide clarity about where to focus attention. I also think that the choice of red to indicate the largest amount of negative CUNA is a smart convention– red signals alarm.  

## The Primary Audience
The primary audience of the visualization and broader article is individuals who run nonprofit theatres across the country. These are Executive Directors, Managing Directors, Artistic Directors, and Directors of Finance. For some theatre executives, the term “CUNA” is a new way to convey the organization’s bottom line, any net assets left net of expenses. Theatre executives who are simultaneously learning the term “CUNA” while also trying to interpret this visualization may be very confused. I don’t think this visualization is effective to reach that audience because it is asking them to visually map the trend of something they may not completely understand in the first place. 

Not only that, but the audience will expect to learn about organizations at a crossroads facing a downturn, as per the article of the piece, “Overcoming Downtrends & Protecting Your Organization Through Future Downturns.” Over half of the data being presented (the blue, dark blue, and green sections of the layer map) represents organizations that have break-even or positive CUNA. Considering that this visualization is meant to display the negative effects of the recession on theater CUNA, this extra data is simply not necessary and can interfere with the main message. 

## Final Thoughts
Using Tableau’s Visual Vocabulary, I looked at the different ways to represent changing trends besides an area chart. I’m most interested in a Slope graph because they are best for illustrating 2 or 3 points in a series of data, and I want to focus on the years around the Great Recession. If redesigning the type of visualization was my strategy, I would also want to significantly scale back the amount of information being conveyed in the graph. I would eliminate the percentages in each column for the years 2004 to 2006 and 2010 to 2017 to give the visualization room to breathe. 

With the primary audience of theatre executives in mind, I believe that the visualization is missing an effective explanation of what CUNA is, which could be given in the simplest of terms. This would be most easily changed in the title. “Negative CUNA (deficits) peaked for theaters during the Great Recession,” is a title change that might suffice. It articulates the focus of the graph. 

Even as I experimented with a Slope graph, I noticed how in the original Area chart that the yellow area for “Negative CUNA less than 10% of the budget” appears to increase dramatically from 2008 to 2009, but the increase in the percentage of theatres is only by 2%. The format of the Area chart manipulates some of these data points to make it seem like there are significant changes when those shifts are minimal at best.  

## What is CUNA?
When I started redesigning, I had to breakdown what the different elements of the original visualization. Any viewer who may not be familiar with Theater Communications Group’s classification of net assets will be confused by the CUNA categories. CUNA is the Change in Unrestricted Net Assets of an organization, or the annual bottom line (see below). 

<img width="692" alt="Screen Shot 2022-09-18 at 8 10 26 PM" src="https://user-images.githubusercontent.com/112351182/190933996-168e07f5-f1c0-4589-8bf6-c6f9dd74c7df.png">
Source: Theater Communcations Group, Theatre Facts 2020

There are two basic categories of CUNA: positive and negative. Positive CUNA is good (a surplus), and negative CUNA is not good (a deficit). After that basic distinction, there are varying levels of how large that CUNA is as a percentage of the organization’s budget. Some CUNA is greater than 20% of the budget, some is between 10% and 20%, and some CUNA is less than 10% of the organization’s budget. 

## Wireframes
The original area graph is confusing because we can't immediately see what the lines are supposed to be telling us. The lines represent the **percentage of theaters with that specified CUNA level.**

![4](https://user-images.githubusercontent.com/112351182/190934110-182948d5-ab2f-42cb-a402-76003a1a0d46.jpg)

We're also getting mixed messages about composition in the original area graph. There are two different elements of composition: 
- CUNA as a percentage of the organization's budget
- theaters with negative or positive CUNA

![5](https://user-images.githubusercontent.com/112351182/190934177-919acfb7-a8bc-4438-8b7a-e0598ea4af00.jpg)

### The 
