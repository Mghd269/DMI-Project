### DMI Advanced HR Analytics
**Magdalena Pietrzak, Hubert Domagała, Michał Głąb**

#### Results Analysis

The following image presents the Spearman correlation matrix, which is a graphical representation of Spearman rank correlation coefficients between different variables. The matrix is square, and both axes are labeled with various competencies such as Python, R, SQL, Excel, and others. 

The colors on the heatmap represent different values of the correlation coefficient. Dark blue indicates a correlation coefficient close to -1, suggesting a strong negative correlation between two competencies. This means that when one competency is rated highly, the other is usually rated low and vice versa. Green color represents little or no correlation, indicating that the rankings of two competencies are not related. Dark yellow indicates a correlation coefficient close to 1, suggesting a strong positive correlation, meaning that two competencies are usually rated similarly – when one is rated highly, the other is also usually rated highly.

![Spearman correlation matrix](https://github.com/Mghd269/DMI-Project/blob/main/figures/img1.png)

Analyzing the matrix, some interesting relationships can be observed. For example, Python and R competencies appear to be strongly correlated, which makes sense since both are popular programming languages used in data analysis. On the other hand, Python and Excel seem to have a weak correlation, which may result from Excel being used more for simpler data analysis tasks, while Python is preferred for more complex analyses.

The highest correlations are observed in four clustered groups of competencies:
- Fintech, Heatech, Fashiontech, Ecomemerance, Sportech, NonProfit, Cybersecurity, and HR;
- UEWadmin, Funding, ScientistRelations, BusinessRelations, GraphicDesign;
- ProjectManager, ComputerVision, NLP, ClassicalML;
- Python, Bash, Git, Docker, CLI.

In the image below, the colors on the matrix range from blue to red; blue indicates a negative correlation, and red indicates a positive correlation. All languages have a perfect correlation of 100 with each other, which is standard for any correlation matrix as everything is perfectly correlated with itself.

![Correlation matrix](https://github.com/Mghd269/DMI-Project/blob/main/figures/img2.png)

#### Correlation Matrix Analysis

The correlation matrix presents the following relationships between different tools and programming languages:

- **R**: Has a moderate positive correlation (0.19) with Python and weak positive correlations with Bash (0.16), GIT (0.03), and CLI (0.16). There is no correlation between R and Frontend (0.00).
- **Python**: Shows weak positive correlations with Bash (0.16) and CLI (0.16), but no significant correlation with GIT (-0.03) or Frontend (-0.08).
- **Bash**: Does not show significant correlations with GIT (-0.03) or Frontend (-0.08).
- **GIT**: Has a moderate negative correlation (-0.4) with CLI but no significant correlation with Frontend (-0.00).
- **CLI**: Has a strong negative correlation (-0.8) with Frontend.

The correlation matrix also presents relationships between different fields in machine learning:

![Machine learning correlation matrix](https://github.com/Mghd269/DMI-Project/blob/main/figures/img3.png)

- **Docker**: Has a weak positive correlation (0.56) with TimeSeries, a moderate positive correlation (0.61) with ClassicalML, a moderate positive correlation (0.73) with NLP, and a moderate positive correlation (0.69) with ComputerVision.
- **TimeSeries**: Has a moderate positive correlation (0.90) with ClassicalML, a moderate positive correlation (0.85) with NLP, and a moderate positive correlation (0.80) with ComputerVision.
- **ClassicalML**: Has a moderate positive correlation (0.75) with NLP and a moderate positive correlation (0.70) with ComputerVision.
- **NLP**: Has a moderate positive correlation (0.65) with ComputerVision.

The correlation matrix below shows the following relationships between different databases and tools:

![Databases and tools correlation matrix](https://github.com/Mghd269/DMI-Project/blob/main/figures/img4.png)

- **SQL**: Has a moderate positive correlation (0.29) with NoSQL, a weak positive correlation (0.21) with Azure, a weak positive correlation (0.06) with AWS, no correlation (-0.06) with GPC, a moderate positive correlation (0.34) with PowerBI, and a weak positive correlation (0.19) with Tableau.
- **NoSQL**: Has a moderate negative correlation (-0.80) with Azure, AWS, GPC, PowerBI, and Tableau.
- **Azure**: Has a moderate positive correlation (0.60) with AWS, GPC, PowerBI, and Tableau.
- **AWS**: Has a moderate negative correlation (-0.40) with GPC, PowerBI, and Tableau.
- **GPC**: Has a weak negative correlation (-0.20) with PowerBI and Tableau.
- **PowerBI**: Has no correlation (0.00) with Tableau.

The correlation matrix shows the following relationships between different soft skills and professional roles:

![Soft skills and professional roles correlation matrix](https://github.com/Mghd269/DMI-Project/blob/main/figures/img5.png)

- **ProjectManagement**: Has a moderate positive correlation (0.50) with SocialMedia, a moderate positive correlation (0.37) with UxUi, a moderate positive correlation (0.57) with GraphicDesign, a moderate positive correlation (0.45) with BusinessRelations, a moderate positive correlation (0.57) with ScientistRelations, and a moderate positive correlation (0.50) with UEWAdmin.
- **SocialMedia**: Has a moderate negative correlation (-0.90) with UxUi, GraphicDesign, BusinessRelations, ScientistRelations, and UEWAdmin.
- **UxUi**: Has a moderate positive correlation (0.80) with GraphicDesign, BusinessRelations, ScientistRelations, and UEWAdmin.
- **GraphicDesign**: Has a moderate negative correlation (-0.70) with BusinessRelations, ScientistRelations, and UEWAdmin.
- **BusinessRelations**: Has a moderate negative correlation (-0.60) with ScientistRelations and UEWAdmin.
- **ScientistRelations**: Has a moderate negative correlation (-0.50) with UEWAdmin.

The correlation matrix shows the following relationships between different industry branches:

![Industry branches correlation matrix](https://github.com/Mghd269/DMI-Project/blob/main/figures/img6.png)

- **FinTech**: Has a moderate positive correlation (0.57) with HealthTech, a moderate positive correlation (0.55) with FashionTech, a moderate positive correlation (0.45) with Ecommerce, a moderate positive correlation (0.50) with SportTech, a strong positive correlation (0.72) with NonProfit, a moderate positive correlation (0.55) with Cybersecurity, and a moderate positive correlation (0.49) with HR.
- **HealthTech**: Has a moderate negative correlation (-0.90) with FashionTech, Ecommerce, SportTech, NonProfit, Cybersecurity, and HR.
- **FashionTech**: Has a moderate positive correlation (0.80) with Ecommerce, SportTech, NonProfit, Cybersecurity, and HR.
- **Ecommerce**: Has a moderate negative correlation (-0.70) with SportTech, NonProfit, Cybersecurity, and HR.
- **SportTech**: Has a moderate negative correlation (-0.60) with NonProfit, Cybersecurity, and HR.
- **NonProfit**: Has a moderate negative correlation (-0.50) with Cybersecurity and HR.
- **Cybersecurity**: Has a moderate positive correlation (0.30) with HR.

#### Survey Results

The next question in the survey asked how participants would like to be involved in the Data Community:

![Survey results](https://github.com/Mghd269/DMI-Project/blob/main/figures/img7.png)

- 59.3% of respondents would like to participate in a data project.
- 40.7% intend to actively participate in the community.

#### Programming Skills Bar Chart

![Programming skills bar chart](https://github.com/Mghd269/DMI-Project/blob/main/figures/img8.png)

The diagram presents a vertical bar chart of programming skill ratings. The chart shows various programming skills on the horizontal axis such as "Java," "C++," "Python," and several others. Each skill has five colored bars corresponding to different ratings indicated in the legend on the right side of the chart. The colors represent different levels of proficiency: purple for 'No Knowledge,' blue for 'Beginner,' green for 'Intermediate,' yellow for 'Advanced,' and dark blue for 'Mentor.' The vertical axis represents the number of ratings ranging from 0 to 60.

Based on the chart, the highest values are:
- ‘Unaware’: Timeseries, NLP, Docker, ComputerVision, Bash, and ClassicalML.
- ‘Interested’: AWS, Azure, PowerBI, and NoSQL.
- ‘Competent’: Python, SQL, PowerBI, BusinessRelations, and Fintech.
- ‘Mentor’: SQL, GIT, PropTech, and Python.
- ‘Not Interested’: UxUi, UEWAdmin, HR, Graphic Design, and SocialMedia.

#### Trends in Programming and Technologies

![Trends in programming and technologies](https://github.com/Mghd269/DMI-Project/blob/main/figures/img9.png)

Based on the submitted image, which contains six bar charts representing various programming languages and

 technologies (R, Python, Bash, Git, CLI, and FrontEnd), the following trends can be observed:
- The majority of respondents indicated interest in R, Python, GIT, CLI, and FrontEnd. Bash is a language that most people are unaware of.
- The fewest respondents declared themselves mentors in R, Bash, CLI, and FrontEnd. In Python and GIT, the highest number of respondents are ‘Not Interested.’

#### Programming Skills Analysis

![Programming skills analysis](https://github.com/Mghd269/DMI-Project/blob/main/figures/img10.png)

Based on the submitted image containing five bar charts representing various categories (‘Doctor,’ ‘TimeSeries,’ ‘ClassicalML,’ ‘NLP,’ and ‘Comparison’), the following extreme values can be observed:
- Most people are interested in Docker, ClassicalML, NLP, and ComputerVision. It is worth noting that in all cases, there is a significant group of people unaware of these fields. For TimeSeries, the majority are unaware.
- The fewest votes were cast for being a mentor in Docker, TimeSeries, NLP, and ComputerVision. In ClassicalML, the fewest people indicated they are ‘Not Interested.’

#### Database and Tools Analysis

![Database and tools analysis](https://github.com/Mghd269/DMI-Project/blob/main/figures/img11.png)

Based on the submitted image containing seven bar charts representing various technologies or platforms (SQL, NoSQL, Azure, AWS, GCP, PowerBI, and Tableau), the following detailed observations can be made:
- The vast majority of votes were cast for the ‘Interested’ option in NoSQL, Azure, AWS, GCP, PowerBI, and Tableau. For SQL, the majority of people are competent.
- NoSQL, Azure, AWS, GCP, and Tableau have the fewest declared mentors. In SQL, the fewest respondents marked ‘Not Interested.’ The fewest votes in PowerBI were cast for the ‘Unaware’ option.

#### Branches Columns Overview

![Branches columns overview](https://github.com/Mghd269/DMI-Project/blob/main/figures/img12.png)

Based on the submitted image containing a series of bar charts titled “Branches Columns Overview” representing various categories such as ProjectManagement, SocialMedia, GraphicDesign, BusinessStories, ScientistRelations, Funding, and LEWAdmin, the following detailed observations can be made:
- Most people are not interested in SocialMedia, UxUi, GraphicDesign, Funding, and UEWAdmin. For ProjectManagement, BusinessRelations, and ScientistRelations, the majority of votes were cast for the ‘Interested’ option.
- The fewest people declared themselves mentors in ProjectManagement, SocialMedia, UxUi, GraphicDesign, BusinessRelations, ScientistRelations, Funding, and UEWAdmin.

#### FinTech, HealthTech, and Other Tech Branches

![Tech branches overview](https://github.com/Mghd269/DMI-Project/blob/main/figures/img13.png)

Based on the submitted image containing a series of bar charts titled “Branches Columns Overview” representing various categories such as FinTech, HealthTech, FashionTech, Ecommerance, SportTech, NonProfit, PropTech, Cybersecurity, and HR, the following detailed observations can be made:
- The majority of people marked the ‘Interested’ option in FinTech, HealthTech, Ecommerance, SportTech, NonProfit, PropTech, Cybersecurity. In HR, the number of people not interested exceeds. In FashionTech, the majority of people are unaware.
- The fewest people declared themselves mentors in FinTech, HealthTech, FashionTech, Ecommerance, SportTech, NonProfit, PropTech, Cybersecurity, HR.

#### Median Skill Ratings

![Median skill ratings](https://github.com/Mghd269/DMI-Project/blob/main/figures/img14.png)

The submitted image shows a bar chart titled “Median Skill Ratings.” The chart represents six different programming skills: R, Python, Bash, Git, CLI, and Frontend. Each skill has a corresponding bar indicating its median ratings: R has a rating of 3.00, Python 2.00, Bash 1.00, Git 2.00, CLI 2.00, and Frontend 1.00.


