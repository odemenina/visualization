# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

I dowloaded the file from [Ontario’s Open Data Catalogue] with  url = 'https://data.ontario.ca/dataset/4edcd678-6f24-4064-970b-b7254fc6671e/resource/8f786bb5-01ac-4e7d-b89f-3437a601941b/download/mltsd_v0906_18_tab2qq.csv
This file includes the informatio about unemployemnt in Ontarion for the period 2021-2020 including the geography (by regions of ON), age groups and duration of the employment.

The diagram 'Number of Unemployed in Ontario by Age group for the period 2001-2020' eflected the number of unemployemnt people by age groups.


    > What software did you use to create your data visualization?
   To create my visualisation I use the following software and libraries:

Python: The programming language used for writing the code.
Pandas: A library for data manipulation and analysis.
Seaborn: A library for creating statistical graphics.
Matplotlib: A library for creating static, animated, and interactive visualizations.
Matplotlib's ticker module: Specifically used for customizing ticks on the plots.

    > Who is your intended audience? 
The intended audience for the "Number of Unemployed in Ontario by Age Group for the period 2001-2020" data would likely include:
1.Government and Employment Ministry: To analyze trends in unemployment and develop policies to address unemployment issues.
2.Economic Analysts and Researchers: To study economic trends and the labor market, and produce reports or research papers.
3.Employers: To understand the labor market and make informed hiring decisions or strategic plans.
4.Educational Institutions: To guide curriculum development and career counseling based on labor market trends.
5.Job Seekers: To understand the job market dynamics and identify opportunities or challenges.
6.Non-Profit Organizations: To design programs and initiatives to support unemployed individuals.
    
    > What information or message are you trying to convey with your visualization? 
The chart shows how the number of unemployed people in Ontario has changed over time from 2001 to 2020, broken down by different age groups.

    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
Here's how I followed to apply the design principles to my visualization:
Clarity: The chart clearly shows how the number of unemployed people in Ontario has changed over time from 2001 to 2020, specified by different age groups by colour.
Readability: Consistent use of colors for each age group and a dark grid background make it easy to read.
Visual Appeal: The chart is visually engaging with a labels, and a legend positioned outside the plot to avoid clutter.


    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
I am ensure the visualizations can be reproduced because 
1.I used the common tools like Pandas, Seaborn, and Matplotlib with standard libraries
2.I procided comment for the code with explanations.
3.I supply the url with initial file location

    
    > How did you ensure that your data visualization is accessible?  
I tryid to create the visialization that everyone can understand the chart:
1.Labels: Titles and labels explain what the chart shows.
2.Colors: Colors are easy to tell apart.
3.Fonts: Big, simple fonts for all text.
4.Grid Lines: Help to read the data points.
5.Legend: Legend is outside the plot to keep it neat.
    
    > Who are the individuals and communities who might be impacted by your visualization?  
 I thnk next groups  of people might be affected by this chart including:
1.Job Seekers: They can see trends in unemployment by age group.
2.Government: They can use this data to make policies to reduce unemployment.
3.Researchers: They can study the trends to make predictions and recommendations.
4.Employers: They can understand labor trends for better hiring decisions.
5.Educational Institutions: They can guide students based on job market trends.
6.Journalists: They can report on unemployment trends.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
 I included features that show trends in unemployment numbers, like date and age group. 
 I excluded unnecessary features like IDs, geography (since we're focusing only on Ontario), and detailed duration or gender specifics to keep the chart clear and straightforward.

    > What ‘underwater labour’ contributed to your final data visualization product?
I think some ‘underwater labour’ actually happened here and some behind-the-scenes tasks went into making the visualization:
1.Cleaning: and gathering the data and ensuring it's accurate, complete, and formatted correctly for analysis.
2.Converting columns to the right data types (e.g., changing date formats) and extracting relevant features (e.g., year).
3.Writing and debugging code to load data, process it, and create the visualization.
4.Choosing the right plot types, colors, labels, and styles to clearly communicate the message.
5.Adding comments and explanations to the code to make it understandable and reproducible.






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
* Submission Due Date: `23:59 - 09/03/2025`
* The branch name for your repo should be: `assignment-4`
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
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
