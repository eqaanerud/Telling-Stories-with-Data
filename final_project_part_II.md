*****Final Project Part II*****

Publicly Accessible Wireframe/Shorthand Draft: [Shorthand Presentation](https://carnegiemellon.shorthandstories.com/cashonhand/index.html)

**Gathering and Grouping the Data**
In developing Part II of my Final Project, I further refined the story I want to tell and the data that supports that story. I began gathering financial data from each organization’s audited financial statements in the New York Charities Bureau - Charities Search Tool. I gathered three sets of data: Operating Budget size, Cash Available, and Net Assets with Donor Restrictions over the course of five years 2016 to 2021. I ran into a few issues with missing financial data for a few organizations including New York Theatre Workshop, Repertorio Espanol, and Vineyard Theatre. I decided early on to eliminate these organizations from my list of theaters because I wouldn’t be giving a comprehensive scope of their cash-on-hand. 

![Screen Shot 2022-10-04 at 7 24 30 PM](https://user-images.githubusercontent.com/112351182/193948562-ddaa3a97-bf53-4805-b4f1-cb5605ca5330.jpg)


After doing my first round of analysis with this dataset, I came to two very important conclusions about how to move forward in the project: 

- It is very difficult to democratize a metric for Unrestricted Cash for nonprofit theaters that differ in size and scope. Each theater that I scraped data  from had a different way of allocating their Net Assets ,which factors into my Unrestricted Cash calculation. Many theaters weren’t up-to-date with the current Nonprofit Accounting standards in designated certain funds as “unrestricted” or “restricted.” These factors made calculating a consistent and universal Unrestricted Cash  metric nearly impossible across the breadth of theaters. 
My solution was to individualize each organization’s approach to determining their available cash based on the notes in their audit. Many audits have a “Liquidity and Availability of Cash'' section that details the organization’s unrestricted cash, minus any restricted reserves. For organizations without restricted/unrestricted categories in their statements, I used data from the Liquidity and Availability to get the most accurate picture of their available cash. 

- Months of Unrestricted Cash On Hand Cannot Stand Alone as a metric in measuring the financial health of theaters because it doesn’t reflect the wide discrepancies between these organizations in funding. When I generated my first visualization on the differences in months of cash-on-hand between theaters with an over $10 million operating budget and under a $10 million operating budget, I noticed a very peculiar trend: smaller theaters grew their unrestricted cash balances at a faster rate than larger theaters, especially during the height of the pandemic. I knew though, that stopping my presentation at that point would be an insufficient demonstration of the fiscal resources that many theaters have, and that I should include data on board reserves. 

<div class="flourish-embed flourish-chart" data-src="visualisation/11353308"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

For my second round of data analysis, I gathered board/cash reserve information and added it to a tab in my data collection spreadsheet. My final calculation for Months on Hand was the following: 

Months of Cash on Hand **(No Reserves)**:
(Cash - Net Assets with Donor Restrictions) 
(Operating Budget / 12) 

Months of Cash on Hand **(with Board Reserves)**:
(Cash - Net Assets with Donor Restrictions + Reserves)
(Operating Budget / 12) 

**Making Sense of the Data**

Producing the second calculation that was inclusive of Board Reserves in an organization’s cash balance told a much more in-depth story than had I just included the original calculation. This new data set demonstrated that these large NYC theater companies have multiple years worth of unrestricted cash or board reserves that they can dip into should they need it. It tells a story of the large discrepancy in resources between many of these organizations.

**Wireframing**

With that new information, I started to put together new visualizations on what I wanted to illustrate. For my setup, I created a new “Recommended Months of Cash on Hand” to compare with the “Months of Cash on Hand at Nonprofit Theaters.” In my user research, my participants commented on how easy it was to make a comparison to the two visualizations side-by-side. 

![Screen Shot 2022-10-04 at 7 31 01 PM](https://user-images.githubusercontent.com/112351182/193949103-cf1d9475-453a-4331-bb54-f8b4e48a7274.jpg)

I also wanted to add more contextual information behind the financial jargon and visualizations I had been building. I used the Shorthand Scrollpoints feature to analyze the parts of the Balance Sheet that contain Unrestricted cash and Board Reserves. 

![Screen Shot 2022-10-04 at 7 31 50 PM](https://user-images.githubusercontent.com/112351182/193949179-8ca0442d-de10-45f7-a9cc-6a17a6b1c3f6.jpg)

I crafted three visualization in Flourish: 

Line graph that shows how smaller theater companies have grown their unrestricted cash on hand faster than larger theaters over the past five years. 

<div class="flourish-embed flourish-chart" data-src="visualisation/11362644"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Line graph shows how with board reserves factored in, larger theater companies have actually grown their unrestricted cash on hand and reserves and have more fiscal health than smaller companies. This chart exists in comparison to the first chart in that the lines are the opposite. 

<div class="flourish-embed flourish-chart" data-src="visualisation/11362819"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

A racing line graph that shows the specific theater companies with the largest board reserves and how they have grown since 2016, measured through months of cash on hand. 

<div class="flourish-embed flourish-chart" data-src="visualisation/11360368"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

I also wanted to improve the narrative structure of my Shorthand wireframing, so I inserted transition elements to describe the main points. My favorite one is where I build tension (one of the narrative guidelines in Good Charts) by saying “but that isn’t the whole story. Board designated reserves set more organizations apart in the long term.” 

**User Research and Interviews**
***User Research Protocol***

***Target Audience:*** NYC theatre executives, financers,  and other administratives that are trying gauge where their organization falls across the industry standard for operating cash. 

***Identifying Representative Individuals:*** I used fellow Master of Arts Management students at Heinz College to view the data, as they have taken courses such as Financial Statements and Nonprofit Financial Statements & Analysis, which provides the general background information needed to understand the metrics (Cash-On-Hand) used in the visualizations. 
If I were to venture outside of Heinz College, I would post the website in Arts Management Facebook groups and online forums to gain different perspectives from working professionals. I would also send it to working individuals at Theater Communications Group and SMU Data Arts.

***Interview Script:***
Do you feel like the information was sufficiently set up? Enough context was given?

What is your understanding of the information that is being presented on each graph? 

What is the main idea of the information presented so far? 

***Interview Findings:***

**Do you feel like the information was sufficiently set up? Enough context was given?**

Public Policy/Class Peer: “I think so. I like that you defined what the things were. I did feel like someone who has no financial expertise might want to know the actual risk of not having cash, or not having reserves. “

Arts Management student: “I would have appreciated more background information about what unrestricted cash is. Also it was unclear about the source of the nonprofit theaters that have only one month of expenses. ” 

(This was before I had added the definitions on Cash-on-Hand)

Arts Management student #2: “I would’ve liked to see the theaters that you were pulling financial data for.” 

**What is your understanding of the information that is being presented on each graph?**

Public Policy/Class Peer: “The Balance Sheet is very blurry and difficult to read.” 

Public Policy/Class Peer: “Tying the pandemic into the presentation creates a universal picture, and the use of bold text is a very helpful visual.”

Public Policy/Class Peer: “It might be better to have more theatre pictures instead of tech-y pictures on the ‘but that’s not the full story’ slide.” 

**What is the main idea of the information presented so far?** 

Arts Management student: “The presentation is about NYC based theaters but it could be for other urban locations. The goal is to explain why it’s important to have cash or board reserve funds. “

Public Policy/Class Peer: “You should move the Cash-On-Hand definition to a later section, close to the visualization about how board reserves make things different. Also try to use an icon in the Cash-on-Hand definition to show that it is a metric and the Board Reserve is a lump sum of money.” 

***Other Comments***
- Go with the green and yellow, remove any blue from the Shorthand presentation. 
- The green is confusing on the visualization because it signals “good” - think about using a different color. 
- Link to a saving strategy site for nonprofits. 
- Put in a closing message also!
- Show the calculation for Months of Cash-On-Hand!

**Changes that I Will Make**
- Add one or two visualizations (dot plot or lollipop chart) of the specific theater organizations and how their Months of Cash-On-Hand differ. 
- Figure out a way to add a non blurry picture of a Balance Sheet
- Change the colors on each Flourish visualization so they do not include Green
- Streamline the typography and colors of all text in Shorthand
- Move definition of Cash-On-Hand metric to further in the presentation and include the calculation spelled out
- Add a collage of the theater logos that I pulled financial data from to introduce the data set I was working with. 
- Add more theatre/performance-specific images to the presentation
- Add a closing thought or idea!
