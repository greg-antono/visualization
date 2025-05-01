# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like!

      ```The examples I’ve chosen are from various articles from Kontinentalist, a company that publishes data-driven, public-oriented stories from all parts of Asia. ``` 

      Positive example: ‘The leading cause of death is workplace-related.‘
      https://kontinentalist.com/stories/migrant-labour-face-safety-risks-in-singapore

      Negative example: ‘Western tourist arrivals to former colonies (2003)’
      https://kontinentalist.com/stories/is-indigenous-tourism-a-form-of-colonial-exploitation

- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      Positive example: Migrant labour / death map

This example is a little grim: it is a pictorial unit chart that visualizes the cause of death amongst 450 migrant workers in Singapore, over a span or 20 years. The dataset, also provided, is a table that lists each individual’s case. The visualization sorts the cause of death into different categories. It is not perfect (more below), but I think it meets the three important qualities: it is aesthetically pleasing, it is substantive (in presenting each individual’s case), and it is perceptual (i.e., clearly the goal here is to highlight each individual’s circumstance). It is clear from the visualization that workplace incidents are the leading cause of death. The chart allows us to compare across categories, but also subcategories (e.g., within workplace incidents, the causes of death can be further classified into different categories), and does so by following Gestalt principles like enclosure (e.g. subcategories having a faded boundary). The chart also has an added functionality of a pop-up when the mouse rolls over each dot (i.e., individual), giving more information about the individual (e.g., name; gender; classification; more details). The legend on top is clearly colour coded, and I appreciate the added functionality of filtering the viz based on gender.  

Note: in the 4th slide deck for this module (“Choosing the right visualization”, slide 18), we went through an exercise comparing two types of visualization: one with two circles, and one with a bar chart. We talked about how the bar chart was a better visualization in showing that A was bigger. In this map, however, I do think that the dots are effective, particularly because they represent each individual. Had this been a bar chart instead, the visualization would be less effective, as it bleaches out information about each individual. In this particular medium (a narrative) and intended audience (general audience; casual readers), this visualization is impactful and informative. 

      Negative example: ‘Western tourist arrivals to former colonies (2003)’

This visualization aims to represent Western tourist arrivals to former colonies, classifying them based on (a) nationality of the Western tourist and (b) the former colony. This relies on a proportional area chart. I’ve chosen this as a negative example, connecting back to the same exercise mentioned above. As discussed in our course, the circles are effective at first glance in showing differences in proportion, but this particular visualization falters in that the multiple subcategories, especially when these subcategories (e.g., nationalities of tourists) are repeated across different regions, make the information a little cluttered and muddled. In an attempt to be minimalist, the legend is a little small, with some colours a little too similar to one another (e.g., for the French and German colours). Additionally, it is unclear what the top-most circle represents (it says it is the legend, but it is unclear what the numbers like 1971 represent). The visualization deeply falters in the discriminability factor, as the legend is positioned from the charts farther down on the page. The numbers included are also ineffective: they are provided either within each circular area, or indicated with an arrow, but it is in fact unclear whether these numbers are taken from a span of time or in a given year. Overall, it is unclear what the goal is from this visualization: if proportions are the take-away (e.g., Americans form the largest group of tourist arrivals in the Caribbean versus American presence in Southeast Asia), this visualization hides this comparison in its current design and lay out. 
      ```
    - How could this data visualization have been improved?  
      ```
      Positive example: Migrant labour / death map

An issue I have with the visualization is the fact that numbers are missing entirely (without hovering over the data points). For instance, from the chart alone, it is not clear that the total number of datapoints is 450, nor the fact that this is over 20 years. The total count should be visible, as should the count for each category (e.g., within each coloured circle).

      Negative example: ‘Western tourist arrivals to former colonies (2003)’

For this visualization, I would change the entire design to a stacked bar chart, such that each bar would represent each region (e.g. 4 bars: Caribbean, Southeast Asia, Indian Ocean and South Pacific). Within each bar, we can then separate by colour, based on the nationality of Western tourists. Putting these bars next to each other allows us to compare the distributions across each region more effectively. Alternatively, a researcher might want to convert these numbers into proportions before plotting them (so that all the bars would be out of the same total). This would allow readers to visualize the proportional differences by region. 
      
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
* Submission Due Date: `23:59 - 30/04/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [X] Create a branch called `assignment-2`.
- [X] Ensure that the repository is public.
- [X] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [X] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
