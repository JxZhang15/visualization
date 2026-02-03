# Data Visualization

## Assignment 3: Final Project


- For each visualization, describe and justify: 

    > What software did you use to create your data visualization?
    
    Answer: I used Python with the Pandas library for data manipulation, and Matplotlib and Seaborn for generating the bar chart.

    > Who is your intended audience? 
   
    Answer: The intended audience includes Toronto city planners, municipal service staff, and local wedding industry stakeholders (venues, florists, and photographers) who need to allocate resources based on seasonal demand.

    > What information or message are you trying to convey with your visualization? 
   
    Answer: The chart highlights the extreme seasonality of marriage licenses in Toronto. By averaging data from 2011–2024, it clearly shows that demand peaks significantly in the summer months (July and August) and reaches its lowest point in January and February.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    
    Answer: I chose a bar chart to make categorical comparisons between months intuitive. I applied the "Viridis" color palette for a professional look and added direct numerical labels on top of each bar so the exact average is immediately visible without needing to check the Y-axis.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

    Answer: The visualization is fully reproducible through a Python script. The code handles every step from loading the raw CSV to filtering years and calculating averages, ensuring anyone with the dataset can regenerate the exact same chart.
    
    > How did you ensure that your data visualization is accessible?  
    
    Answer: I used a color-blind friendly palette (Viridis) and included bold data labels on top of every bar. This ensures the information is accessible to users who may have difficulty distinguishing colors or reading fine-print axis scales.

    > Who are the individuals and communities who might be impacted by your visualization?  
    
    Answer: Small business owners in the hospitality sector are impacted as they use this data for seasonal staffing. Additionally, couples are impacted as the data reveals when competition for city services and wedding dates is highest.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    
    Answer: I included the MARRIAGE_LICENSES and TIME_PERIOD (converted to month names) to focus on the seasonality story. I excluded the _id and the individual CIVIC_CENTRE names to focus on a unified, city-wide average that is easier for a general audience to digest.

    > What ‘underwater labour’ contributed to your final data visualization product?

    Answer: The 'underwater labour' involved cleaning the date strings, summing data from four different civic centers to get city-wide totals, and performing a multi-step aggregation to calculate the mean for each month across a 14-year period.


- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
