# Hackathon : Healthcare Insurance Cost Analysis - Project 1


**Hackathon - Python ETL & Visualisation ** This project is designed to sharpen and show the steps to how ETL and visualisation works hand in hand. This is an opportunity to use data, project management and presenatation skills using this project.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* This dataset is about healthcare insurance and contains records including demographic and lifestyle factors that impact the costs of insurance. The dataset contains information on the relationship between personal attributes like: age, gender, BMI, family size, smoking habits, geoographic factors and their impact on medical insurance charges. This dataset helps anaylse fctors affecting healthcare costs and usuaeful for predictive modelling in the insurance industry. it also allows data visualisation to understand expense trends across different groups. The current size of the dataset is at 700,000 bytes.


## Business Requirements
* Understanding cost Drivers - Identifying key factors that are affecting healthcare insurance costs (Age, BMI, smoking status, Region, etc)

* Provide Actionable Insights - This enables insurance companies or individuals to have a better understanding on how lifestyle choices impact pricing.

* Improves Predictive Modelling - This can be used for more advanced data science techniques to develop models for estimating the future of insurance costs.

* Visualise Trends - This helps visualise trends effectively to generate clear charts and dashboards, highlighting cost patterns and correlations.

* ETL - Clean, transform and validate  the dataset to avoid misleading conclusions.


## Hypothesis and how to validate?

Hypotheses -
* Do I want to know age distributions or comparing insurance costs on smokers and non smokers?

* Smokers will have significantly higher insurance charges than non-smokers.

* BMI and insurance costs may be positively correlated (higher BMI → higher charges)

* Older individuals will generally have higher insurance costs compared to younger individuals.

* If children are counted in on this data, the number of children covered under a policy may influence total charges.

How to Validate These hypotheses? - 

 * calculate the average insurance charges for smokers vs non- smokers 

 * Compare 'mean' insurance costs across the age groups

 * deciding on the best visuals to represent the data; boxplots or bar charts?

 * Scatter plot in BMI vs Charges to check correlation strengths.

## Project Plan
I will break my project plan down into three sections:

**Steps Taken -** 
The best way to manage myself for this project was to take a step back and manage my expectations. I decided to spend most of Day 1, planning and sorting out the foundations of this project to make sure the basis was layed out. 

I started with arranging my Kanban board to reflect my project management section of this project, I then clone a respo designed with all the correct requirements and features I needed to be able to run this project on the VS Code. With that being said, I then set up my Jupyter Notebooks, README file and ran any codes that was needed to then have the Kernel set-up.

After the setting up process, then came the file extraction, which I had got from Kaggle. For the dataset I went ahead and used the Healthcare Insurance Costs Analysis. Here I then implemented the ETL method: Extract, Transform, Load and Validate. 

Once the data has been cleaned and transformed I had then moved onto upkeeping my README and updating my Kanban board.

Moving onto the visualisation, I then created a 3 plots, one being a bar chart, a histogram and an interactive scatter plot.

After this, I had updated my README and Kanban board as expected and finalised everything with a presentable presentation. 

**How was the data managed throughout the collection, processing, analysis and interpretation steps?**

1. Data Collection
The dataset was sourced from [Kaggle] and contains healthcare insurance records with attributes like age, BMI, smoker status, and insurance charges. Initial inspection was performed using df.info() and df.describe() to understand its structure, completeness, and distribution.

2. Data Processing
Cleaning Steps Taken:

Missing values in categorical columns (smoker, region) were filled using mode.

Numerical columns with missing values were replaced using mean.

Duplicates were checked and removed where necessary.

Transformations Applied:

Categorical Encoding: Converted "smoker" (yes/no → 1/0) and "region" into numerical values using .cat.codes.

Standardized Format: The cleaned dataset was stored using df.to_csv("processed_data.csv", index=False).

3. Data Analysis
Summary statistics (df.describe()) helped identify trends in insurance charges. Correlation checks (df.corr()) measured relationships between variables like BMI, age, and charges. Key hypotheses were validated through visualization techniques (histograms, bar charts, scatter plots).

4. Data Interpretation
Insights Generated:

Smoking status significantly impacts insurance costs.

Age plays a role in pricing but has varied trends across different age groups.

BMI showed weak correlation with charges, suggesting other factors may be stronger cost predictors.

**Why did you choose the research methodologies you used?**

Lets start with descriptive statistics: I chose this to better understand metrics like averages, distribution and trends. 


In terms of visualisations, I used this to show the patterns in the insurance and how it corresponds with BMI and age. My angle was to start with a more general view as apposed to focusing just on the smoker and non - smokers as it seemed quite narrow and wouldnt show the general issue of the data.

Lastly, I didnt take the predictive route as healthcare seems to require more exploratory analysis rather than prediction due to the nature of uncertain health conditions. 

## The rationale to map the business requirements to the Data Visualisations
* List your business requirements and a rationale to map them to the Data Visualisations

## Analysis techniques used
* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques. Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations
* Were there any data privacy, bias or fairness issues with the data?
* How did you overcome any legal or societal issues?


## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 


## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)
* NeilMc 
* Emma Lamont 
* John Rearden 
* Mark Briscoe 



