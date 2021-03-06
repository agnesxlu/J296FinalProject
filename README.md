# Rent relief application ended for Richmond tenants: what's next?
_The COVID-19 Rent Relief Program applications in California ended on March 31, meaning that the Richmond tenants who struggle to pay rent are again facing the risk of getting evicted. What happened since then and what will happen? Read full story here:_ </br>

#### By Xueer Lu

March 31 marked the end of COVID-19 Rent Relief Program applications in California, shoving the Richmond tenants who struggle to pay rent back into the risk of eviction. 

The eviction moratorium in California, which was designed to protect renters who failed to pay rent from eviction, has expired by the end of last September. But the state's rent relief program, which operated between March 2021 through March 2022, continued to shield tenants from eviction, helping 2,358 households and gave each household an average assistance of $11,628.

For those who have applied for it and received funds, the rent relief is a life-changer. Charlene Cornelious, a long-time Richmond resident, is one of them.

As someone who has been struggling with the Crohn’s disease, she was unable to work and her only source of income was $368 per month from California’s State Disability Insurance program, less than half of her monthly rent of $960. 

Cornelious submitted her application last August and received the approval at the beginning of last October. But the approval was only the start of a five-month wait for the money to actually arrive.

"It was a long wait, a stressful wait," said Cornelious, whose apartment has received the $4,000 fund from the rent relief program in March. 

Now that Cornelious is physically feeling better from her Crohn's disease, she is back to work as a certified nursing assistant at Vale Healthcare Center in San Pablo. With the fund she received from the rent relief program and her job, she is gradually getting back on her feet. 

Katrina Vizinau, senior housing counselor at the [Community Housing Development Corporation](https://communityhdc.org/), a non-profit based in the bay area that helped tenants with their applications, thinks that the rent relief program has been very helpful for people who didn't have other financial support and the program was their only support to find some financial relief and maintain their house and stability. 

However, since the applications for the rent relief also ended, what will happen to the Richmond tenants who have trouble paying rent? 

A [bill](https://leginfo.legislature.ca.gov/faces/billTextClient.xhtml?bill_id=202120220AB2179) passed on the same day as the rent relief application portal closed. The bill, authored by District 14 Assemblymember Tim Grayson and District 15 Assemblymember Buffy Wicks, moved the date when landlords can start eviction proceedings from April 1 to July 1, giving a grace period specifically for tenants who have applied for the rent relief but are still waiting for the fund. 

But this is only a temporary breathing time for those waiting for the fund. "For the tenants unable to pay rent after this new law passed, I think that they're in a completely different boat, definitely more vulnerable now," said Nicolas Traylor, executive director of the [Richmond Rent Program](http://www.ci.richmond.ca.us/3364/Richmond-Rent-Program). 

In Richmond, a city only 20% Black, the pandemic has made it particularly hard for the Black community, as reflected in the racial composition of the rent relief applicants. 

![Racial composition of rent relief program applicants in Richmond](/race.png)

In addition, according to the statistics offered on the dashboard of Housing Is Key, most applicants have low income and more than half of the applicants are middle-aged, from 31 to 50. 

For those unable to pay rent after April 1, Traylor said the Rent Program provides a mediation for landlords and tenants to come up with an update of each other's situation and set up possible payment plans. 

But the end of rent relief does not mean the end of all sources of financial assistance. 

Luckily in Richmond, for both landlords and tenants, a new way of financial aid can also give a helping hand. The [Richmond Rapid Response Fund](https://www.richmondresponsefund.org/), also known as R3F, is a city-level funding. 

R3F is joined by parties both from the Richmond community and local government, including the City of Richmond, The RYSE Center, The Ed Fund, Richmond Promise, and Building Blocks for Kids.

According to Vizinau from CHDC, the successful rate of applications for R3F is as high as 98%. Unlike the state rent relief program which takes a long time to process and given based on area median income (AM1), R3F has no particular income guideline and is a self-attested fund. 

Since the end of moratorium by the end of September 2021, there has been slight spike in surge of total filings, according to the data obtained from the Rent Program through public record request. Through the middle of 2020 to February 2022, nonpayment of rent still accounts for the biggest cause of fillings. 

![Eviction data in Richmond](/evictiondata.png)

Traylor expected that with the rent relief program expired, it is more likely to see California's covid state of emergency going away. That said, Traylor also pointed out it could result in the City of Richmond Urgency Ordinance, also known as the city moratorium, going away as well, approximately 60 days after the state of emergency lifts. Right now, Traylor and his team are preparing for a significant uptick of eviction filings in Richmond. 

" I think if the virus infection rates continue to decrease, the various moratoria will likely go away," said Traylor, "And with that, we're expecting a significant increase and notices being served on tenants."


## Data Diary
### Data Source
In this project, I'm using **two sources of data**.
#### 1. The monthly eviction data of the city of Richmond
The data was obtained through public record request from the [Richmond Rent Program](http://www.ci.richmond.ca.us/3364/Richmond-Rent-Program). The data include months from July 2020 to February 2022 in the form of two pdf spreadsheet. I also conducted two interviews with [Nicolas Traylor](https://www.ci.richmond.ca.us/directory.aspx?EID=1342), the Executive Director of the Richmond Rent Program, and [Cynthia Shaw](https://www.ci.richmond.ca.us/directory.aspx?EID=1386), the program's Assistant Administrative Analyst, to explain how they collected the data and what each row and column of in the spreadsheet represent, in case of any confusion. 
#### 2. The California Rent Relief Program application data of the city of Richmond.
This part of data was collected from the [California Rent Relief Program Dashboard](https://housing.ca.gov/covid_rr/dashboard.html) on the website of Housing Is Key, a rent assistance program established by the State of California. The dashboard covers data including complete household applications, total household served, average assistance, demographcis of applicants, and total funds paid by the program. 
### Data Cleaning
![OriginalData1](/OriginalData1.jpg)
![OriginalData2](/OriginalData2.jpg)
Above are the original formats of the two datasets, therefore I manually put the numbers I need into a google spreadsheet. 
#### Dataset 1: monthly eviction data
The data given by the Rent Program only pertains to July 2020 to February 2022. The data was given in a large image-based pdf file. So I need to manually put the numbers I need into my google spreadsheet like this. 
![data cleaning 1](/dataclean1.png)
But according to my article, especially my data visualization, I need to focus on the numbers of total filings and nonpayment of rent. So I put these two variables in a seperate tab like this. 
![data cleaning 2](/dataclean2.png)
#### Dataset 2: Rent Relief Program application data
This is a similar situation of my first dataset. I had to manually put all the data from the dashboard into my googlesheet. It looks like this for the racial percentage, which is the data visualization chart I made. I also included AMI and age group. 
![data cleaning 3](/dataclean3.png)

### Data Analysis - Questions and Answers
#### 1. What is general trend of the total eviction filing numbers (by month) and numbers of filings whose cause is nonpayment of rent (by month)? 
The analysis is in the article, but what I need for this part is a line chart, consist of two lines. One line displays the trend of the numbers of the total filings and the other line shows the trend of the filings whose cause if non-payment of rent. This question can be answered through the data visualization hence I did not use any formula or pivot tables to analyze it. 
#### 2. Is nonpayment of rent actually the most frequent cause for most of the months?
* Freeze and bold the first row and the first column in second tab "nonpayment of rent" (which is the nonpaymentofrent.csv file).
* In cell B4, use fomnula =B3/B2 and change the number format into %.
* autofill the rest of the row. 
* For most of the months since July 2020, the percentage of the evictin filing cause of nonpayment of rent is higher than 50%, except for six months when the moratorium was in effect. 
#### 3. What is the percentage of different races for all the applicants for rent relief in Richmond?
* Freeze and bold the first row in the third tab "race" (which is the race.csv file).
* Sort from Z to A. 
* It shows that "Black or African Americans" takes up the biggest ratio, up to 43.6%.
#### 4. What is the percentage of different AMI (average median income) for all the applicants for rent relief in Richmond?
* Freeze and bold the first row in the fourth tab ÄMI" ((which is the AMI.csv file).
* Sort from Z to A. 
* It shows that up to about 66% of the people have an AMI no more than 30%, which means they have extremely low income. And the second largest group is AMI > 30% - 50%, which represents people with very low income. 
#### 5. What age group submitted the most applications for rent relief in Richmond? 
* Freeze and bold the first row in the fifth tab "age" (which is the age.csv file).
* Sort from Z to A. 
* It shows that people aged 31 to 40 filed the most applications, accouting for about 30.6% of total applications. Age group 41 - 50 came second, taking up 21.31%. 

### Data Visualization - links
I used Flourish to make the two charts for my story. 
1. line chart link: https://public.flourish.studio/visualisation/9784139/
2. Bar chart link: https://public.flourish.studio/visualisation/9786524/
