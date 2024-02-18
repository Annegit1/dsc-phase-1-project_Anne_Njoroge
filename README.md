**Microsoft Movie Studio Investment**

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/a81fecb5-375f-42a8-a543-47c0c6cf5921)

Written by **Anne Njoroge**

**Overview**

This repository aims to help understand how genres, production budget, worldwide gross, trend across years, and runtime inter-relate with each other and what theis may mean for the MicroSoft Company for their project investment. 

**Business Problem**

Microsoft would like to engag in the ovie industry just as other movie producers have done. However, there is a problem since they are not aware of how to create movies or produce them. They have thus shared a brief on their problem and objectives for a report that would help them understand the movie industry. From exploring different types of movies, the findings are to be transformed to snackable insights that would create a leeway for Microsoft to venture in the industry.

**Questions to Consider**
- What genres have a high worldwide gross that MicroSoft can venture in?
- Does there exist a profit in movie production
- How does ROI vary based on the runtime minutes of a movie?
- How does budget and gross correlate?
- Why are these questions important from a business perspective?
ROI is important to decide which movie making ventures make sense to fund vs. using the money in other Microsoft projects.

**Data Understanding**

In the folder zippedData in the associated GitHub repository are movie datasets from:

Box Office Mojo

IMDB

Rotten Tomatoes

TheMovieDB.org


**Questions to consider:**

Where did the data come from, and how do they relate to the data analysis questions?
Data was retrieved from the ZippedData given which contains different movies libraries. 
It helps in analysis to come up with actionable insights according to Microsoft's brief.

What do the data represent? Who is in the sample and what variables are included?
The data represents stored movies in the movie industry platforms and variables include production budget, worldwide gross, title, year, runtime minutes, genres, profit margins, and ROI.

What is the target variable?
ROI, profit.



**Data Preparation**

Group data from diffent resource to 'cleaned_data' which have title, production budget, worldwide gross, year, and runtime minutes.

**Questions to consider:**

Were there variables you dropped or created?
There are variables that were dropped during data cleaning since they were not relevant for the analysis. Kept data was production budget, worldwide gross, title, year, runtime minutes, and genres.
Other variables were added to make visualization much simpler and realistic while provide meaningful insights. They include profit margins and ROI, and were based on the production budget and worldwide gross.

How did you address missing values or outliers?
I excluded some outliers, and I only analyzed rows which had no missing values.

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/7ecbbf05-a5ce-45ea-968b-c70815048f0f)

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/c5bdc123-1448-4157-99b4-7e325a5b446c)

Data was then stored for use for visualization.

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/bc1fee19-2e62-46ad-94b3-a5c8e8d977e7)

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/e94b8eef-9d83-44c5-8181-f5e906c5855e)

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/8794100e-621d-4c5e-88c5-ae17364471f7)

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/6efedf52-9357-4374-9b46-8b4eb2f120d9)

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/34153d91-44e5-4a13-8275-b92296df499c)

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/4a9ad361-acaf-4ff6-931e-6a5dbcaf1ee8)

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/a3b366f2-4f2d-4fd6-8a38-eae997bb8bd7)

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/b3673aa2-03bf-481b-b63b-8c98288e4ecb)

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/8b5294df-902a-4136-849b-15b9af7e6546)

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/682fe709-fbda-4c37-b278-3d775cd9b704)

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/f5b7f9ef-24f2-4759-87b9-8096b59113b5)

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/653e2615-3a9e-478c-bded-034fbbaa2c33)

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/ad36b0ce-70de-4a38-b26f-b1221a85da99)

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/1a07cd6e-c20a-4daa-82f8-be906a745d2f)

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/82fbf746-2322-4650-91be-e3556e55b6ac)

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/422f97e5-bc28-4ba0-8e29-35b59bfc5f15)

![image](https://github.com/Annegit1/dsc-phase-1-project_Anne_Njoroge/assets/151770828/632fa011-1c99-46ce-900b-1df19e7b5756)

**Data Modeling**

Data was analyzed through performing regressions on production budget and worldwide gross. 

Correlation matrices were also performed to visualize how production budget and worldwide gross inter-related and other metrics were applied to help generate a recommendation of the type of genres and movies to create. An examination of many different parts of the data and visualizations was conducted to come up with significant results. data cleaning and to mitigate quality issues resulted in an impactful analysis process.

Microsoft has a lot of capital, but also lots of other expenses. The latter was induced into the analysis of the data with multiple target variables to assist Microsoft in make data driven decisions in the movie industry investment.

**Evaluation**

Types of genres that would be ideal for investment and relating positively with key metrics were identified for Microsoft to venture into. Summary statistics indicate that the recommendations should increase expected profit and ROI when making a generic movie.

**Conclusions and recommendations**

From the analysis, the following are advised.

I recommend making a film that has a runtime between 80-120 mins. For a low budget movie, it should be a short one while for a high budget movie, it should be long.

Microsoft can proceed to venture int the industry as trend of profit shows a positive increase from a period of year analysis. However, some circumstances may cause a sgnificant drop in production and a risk analysis should be further investigated.

Microsoft should choose to start film production in any of the genres Mystery, Crime and Sci-Fi films as they have greater ROIs.






