# Hailey Wolfe - Data Analyst Portfolio
Welcome! This repository serves as my portfolio to showcase skills, share projects, and track my progress in Data Analytics. Inside, you’ll find projects demonstrating proficiency in Python, SQL, Tableau, and Excel, with a focus on transforming raw data into strategic solutions.

## About
Hi, I'm Hailey!

My background is in mathematics and education. After graduating from Drury University, I spent 5 years as a high school math teacher, where I developed a deep passion for using data to uncover meaningful insights and solve complex problems. I am excited to pivot my technical foundations, structured problem-solving, and analytical skills into a role as an entry-level Data Analyst.

I thrive on the thrill of discovering hidden patterns in data and translating those findings into actionable, strategic solutions. Whether working independently or collaborating with a team, I am constantly expanding my technical toolkit and exploring new data analysis tools to drive impactful decision-making.

My Resume [pdf](https://drive.google.com/file/d/1fAqO8q3wYzrEVYtQYT37omCQZeqKyFXK/view?usp=sharing).




## The Joplin Training Crisis
**File:** [Excel](https://docs.google.com/spreadsheets/d/1ORxnEXegySIN_Pi-a5LdiLItZJeU-mGtRoUGLrewDgI/edit?usp=sharing)

**Goal:** Analyze and interpret training compliance data for a new Customer Service Training Module by merging disjointed HR and LMS datasets.

**Description:** I built a simulated L&D pipeline in Excel using Power Query to merge an HR roster with LMS training data for a new Customer Service training module. Utilizing AI to generate a realistic dataset, I constructed Pivot Tables to calculate completions, track training compliance, and analyze performance gaps. In this project, I acted as a Learning and Development Analyst who was tasked with interpreting the data to deliver actionable insights and strategic recommendations.

**Skills:** data cleaning, data analysis, data visualization

**Technology:** Mircosoft Excel, Power Query (Data modeling & merging), AI Generation (Dataset simulation), Pivot Tables (Aggregation)

**Results:** While regional training compliance for the new Customer Service Module is strong across the board (averaging over 85%), the Joplin district is experiencing a severe completion deficit, currently sitting at just 33%. Data indicates this is primarily a local implementation or communication issue rather than a staffing constraint.

### Key Data Insights:
Springfield & Branson Leading: Springfield (86%) and Branson (85%) have successfully integrated the training. Notably, Branson achieved an 85% completion rate despite having a smaller total headcount than Joplin, indicating that current store staffing levels are sufficient to allow for training time.
The Joplin Stagnation: Joplin currently has 45 employees stuck "In Progress" and 35 who have "Not Started." This high volume of incomplete statuses suggests a gap in local management prioritization or a lack of structured, dedicated floor time for employees to finish the modules.

**Recommended Actions:**
Targeted Management Alignment: Partner with the Joplin District Manager this week to communicate the operational importance of this module and establish dedicated, uninterrupted computer blocks for the 45 "In Progress" employees.
Establish a Compliance Deadline: Implement a firm two-week completion deadline for the district to bring Joplin in line with the corporate benchmark of 80% minimum compliance.
Longitudinal Follow-up: Re-run the Power Query pipeline on [Insert Date - 2 weeks out] to measure growth velocity and report progress back to leadership.

**Visualizations:**
The Scatter Plot Story: The scatter plot shows a general upward-sloping trend, confirming that employees who spent more time generally scored higher. However, it also exposes key exceptions. There is a dense cluster of "highly efficient learners" who spent only 25 to 35 minutes but achieved perfect scores of $100\%$. Crucially, you can see a small group of isolated dots in the bottom-left corner—users who rushed through the test in under 20 minutes and scored below 60%. This proves that low scores are strongly correlated with low time investment.
The Histogram Story: The histogram shows a heavily right-skewed (negatively skewed) distribution. The tallest bars are clustered tightly between 85% and 100%, showing that the vast majority of the company understood the material perfectly. This visual tells the VP that the training program is highly effective for about 90% of the workforce, and that the 88% average isn't a fake metric driven by widespread guessing—it represents genuine master-level performance from most employees.




## Evaluating the Financial Impact of a Training Program
**File:** [Excel](https://docs.google.com/spreadsheets/d/1oBVcIsIJUAF0cUen84owDYgzx2uzYaYTcTBHfdHZsRQ/edit?usp=sharing)

**Goal:** Evaluate the financial effectiveness of a newly launched Advanced Commercial Sales Training program and determine if the initiative drove meaningful revenue growth or if observed increases were merely the result of standard seasonal variance.

**Description:** In this project, I simulated a common corporate Learning & Development challenge: proving the business value of a training program. Using separate datasets from the HR training roster and point-of-sale (POS) financial records, I built an automated data pipeline to merge the datasets, clean the records, and isolate performance metrics. To keep the data honest, I used a Control Group of stores that didn't get the training. This gave me a clear baseline for the seasonal market lift, so I could separate standard seasonal growth from the actual revenue spike driven by the training program.

**Skills:** data cleaning, data analysis, data visualization

**Technology:** Mircosoft Excel, Power Query (Data trasnformation & merging), AI Generation (Dataset simulation), Pivot Tables (Aggregation), Data Visualization (Conditional formatting and charts)

**Results:** While it's true the market experienced seasonal variance, the Control group proves that this was minimal. The stores that participated in the training program outpaced the seasonal variance by significant amount, a 23% increase from 3.5%. The Trained stores grew by an average of $12,500/month, while the Control stores only grew by an average of $1,500/month. 

### Key Data Insights:
The Training Premium: Stores that participated in the training program achieved an average monthly sales growth of 26.5% (an average increase of $12,500 per store). 
Disproving Market Seasonality: The Control Group (no training) only experienced a natural market lift of 3.5% (an average increase of $1,500 per store).
The Net Delta: The trained stores outpaced the standard market growth by a net 23%, proving a strong causal relationship between the L&D curriculum and increased commercial sales.

**Recommended Actions:**
Full Regional Rollout: Based on the pilot success, I would recommend expanding the Advanced Commercial Sales Training to all 300 stores within the region.
Revenue Projection: Scaling this program across the 300-store region projects a total regional performance lift of $3,750,000 per month.
Opportunity Cost Mitigation: If leadership opts out of the training rollout and relies solely on natural market lift, the region is projected to capture only $450,000 in growth. We would miss out on an estimated $3.3 million in monthly revenue growth just by relying on standard seasonal variance.

**Visualizations:**
Strategic Color-Coding: Used conditional formatting to draw the eye directly to the revenue growth outliers and establish an instant visual hierarchy.
Executive Charts: Created clear charts that isolated the training group's growth curve against the control group, making the program's financial return obvious in seconds.

