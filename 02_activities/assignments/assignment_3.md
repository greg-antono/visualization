# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?

    > Who is your intended audience? 
    
    > What information or message are you trying to convey with your visualization? 
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
    > How did you ensure that your data visualization is accessible?  
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    
    > What ‘underwater labour’ contributed to your final data visualization product?

Response: (883 words)

The dataset I’ve chosen is the TTC Subway Delay dataset from the City of Toronto, specifically from 2024 (https://open.toronto.ca/dataset/ttc-subway-delay-data/). My goal was to plot the top 20 causes of TTC subway delays. I pre-processed the data first, by focusing on the column with delays, and filtering out all lines where the delay was 0min (therefore those that were clearly not a delay). In the dataset, each line represents a TTC delay, and has information on which line the delay occurred on, and when it occurred. I added an extra column, such that the description of each delay code was also included in the dataset. My decision to choose the top 20 (even though the TTC has a grand total of 170 different codes for delays), is because I wanted to highlight that passenger-related causes are driving the delays: we can observe the exponential difference just by observing the top (largest) frequency (SUDP: Disorderly Patron) and the 20th cause (PUSAC; signal issues). 

For my first visualization, I created two dynamic/interactive barplots (Viz 1a and 1b) on Python, with the idea that this was to be communicated to a general audience. With (1a), my intention was to convey that the bulk of delays (i.e., majority of the top 10) causes of TTC delays are in fact passenger-related. When hovering over each bar of (1a), we can see the number of delays, and cause of delay in a separate textbox. I had chosen this feature, as opposed to making the cause of delay description as labels on the x-axis, as it would be too cluttered. Additionally, I wanted to stay faithful to the original dataset. The visualization is accessible in that the red and blue bars are high in contrast. However, I acknowledge that a legend is missing in (1a), which is something that could be encoded in the dataset (discerning between passenger-related causes vs. TTC/other-related causes). 

(1b) depicts the same dataset, but I wanted to break down each cause further by each TTC line (with its corresponding colour in the world: Yonge-University being yellow, Bloor-Danforth green, and Sheppard red). This viz features stacked bars, ordered by magnitude (e.g., the line which had the most delays were at the bottom). For this particular viz, I wanted to highlight that the bulk of delays come from Line 1 – which is unsurprising because it is the longest subway line out of the three. This particular viz, however, does not highlight what (1a) does, which is that passenger-related causes are driving these delays. I made sure that this data visualization is reproducible by producing this code on Python and commenting out the edits, and making sure that it was working through testing on Jupyter notebook. In terms of impact of this viz, I think the general public, as well as policy makers in Toronto, might want to come to terms with the fact that our city’s transit issues are largely social ones. In terms of ‘underwater labour’, this includes the TTC workers who tirelessly log and report each delay contributed to this dataset, and anyone like myself who has to process the data (and decode what each delay code means from a separate document). 

The goal of this particular visualization was to depict a different facet of the TTC delays, by situating it in the city. I created Viz 2 on Excel, by first creating a pivot table that sorted counts of TTC delays by station. The static chart depicts the top 30 stations where delays occurred in 2024, and is again categorized into the subway line (yellow for Line 1, green for Line 2). Again, I chose to limit the data on the x-axis because I wanted to draw attention to where the most delays occur (and thus, the multitude of stations where only 1 delay occurred during the entirety of 2024 is not particularly informative). I’ve attempted to make it accessible in terms of the colour coding, but I acknowledge that the x-axis might be hard to discern since there are 30 entries. Additionally, since the graph was generated on a program like Excel, however, it is not reproducible in that one cannot examine the code that generated it. In retrospect, it might have been more informative to also code for which stations are loci for subway transfers or streetcar transfers when I was pre-processing the data. This might be useful in determining whether the delays are correlated with these being hotspots for a lot of traffic. I think that again, this visualization would be helpful for anyone invested in the infrastructure of our city’s public transit. 

In sum and upon reflection: the graphs I’ve created ultimately still have room for improvement: in terms of design, (1a) is lacking a legend, while both (1a) and (1b) might appear confusing because of the x-axis labels. I further believe that a snapshot from one year (2024) isn’t particularly informative when we’re interested in trends. Generating these plots and making comparisons over a period of 5 years (which is doable, considering all the data is available) would be more helpful. I like the dynamic feature of the visuzalizations I’ve created on Python, as it enables us to pack more information in to them without compromising telling a story at first glance. 


- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 09/05/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [X] Create a branch called `assignment-3`.
- [X] Ensure that the repository is public.
- [X] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [X] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
