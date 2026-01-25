# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
    Good Chart Example - Pictorgram Chart
    Link: https://jscharting.com/examples/chart-types/pictogram/percent-multiple-value-typography-pictogram/
    
    Substantive
    - This chart is highly substantive because it presents data with complete transparency.
    - Because each icon represents a specific unit, the data is easy to verify by simply counting the symbols.
    - Unlike 3D graphs, there are no overlapping layers or perspective shifts to hide or exaggerate the numbers, ensuring an honest representation of all 365 days

    Perceptual
    - The chart excels at being perceptual by using a "language" that is universal.
    - By using recognizable icons like suns and rain clouds, the message is clear even without reading the labels.
    - A viewer can instantly see that NYC is mostly cloudy because the blue cloud icons occupy the largest area of the grid, making the main takeaway obvious at a glance.

    Aesthetic
    - The visualization is aesthetic because its beauty comes from its organized and functional design.
    - The chart avoids "chartjunk"—unnecessary decorations or distracting effects that don't add value to the data.
    - The icons serve as both the "ink" and the information; the clean layout makes the chart look professional while keeping the focus entirely on the weather patterns.
    


      
    Bad Chart Example - 3D Bar Chart
      Link: https://www.mathworks.com/matlabcentral/fileexchange/35274-matlab-plot-gallery-bar-graph-3d?focused=6793108&tab=example

      Substantive
      - The chart fails the substantive requirement because the 3D perspective distorts the data.
      - The bars in the "front" (like those for the year 2000) physically block the viewer's ability to see the exact height of the bars in the "back" (earlier years).
      -Because of the slanted 3D angle, it’s super hard to line up the top of a bar with the temperature numbers on the left. You end up just guessing the value, which means the chart isn't being honest or accurate with the numbers.

      Perceptual
      - The perceptual quality is bad because the 3D design is just too messy to understand the actual "story".
      - The viewer should be able to easily see if Boston is getting warmer over the century. However, your eye has to jump over "valleys" and "peaks" across a diagonal plane, making it much harder to detect a trend than a simple 2D line graph would.
      - Instead of quickly understanding the temperature message, the brain has to spend extra effort decoding 3D space and depth.

      Aesthetic
      - While the chart may be considered "pleasing" by some due to its use of color gradients and 3D shapes, this actually works against the visualization.
      - he "cool factor" of the 3D bars is prioritized over the clarity of the information. In professional data visualization, an aesthetic that interferes with the truth (the substantive quality) is considered a failure in design.
  

      ```
    - How could this data visualization have been improved?  
      ```
    Improvement for Good Chart
    - Direct Correlation with Temperature. Use a color gradient on the icons themselves (e.g., a dark red sun for a "Hot Sunny Day" vs. a light yellow sun for a "Cold Sunny Day"). This provides a multivariate view. You are no longer just seeing the type of weather, but also the intensity of the temperature associated with that weather, all in one clean graphic.

     ![text](assignment_2.md)


    Improvement for Bad Chart 
      - Switch from 3D Bars to a 2D Heatmap
      - Put the Months on the x-axis and the Years on the y-axis. Use colors (e.g., blue for cold, red for hot) to represent the temperature.
      - We can see every single data point at once without anything being hidden (no occlusion). It makes it very easy to spot if specific months are getting "redder" (hotter) as the years go by.
      - it meets the requirements of substansive, perceptual and asthethic






      
      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 10/26/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
