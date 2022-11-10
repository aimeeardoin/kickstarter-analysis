# kickstarter-analysis
Performed analysis on kickstarter data to identify trends
# Kickstarting with Excel


## Overview of Project
This project uses quantitative and qualitative data collected from multiple types of artistic performances and describes duration and financial measures such as success based on initial and final funding.

    ### Purpose
    The purpose of this project is to display outcomes of theater productions shown against their launch dates and against their initial goals. 

## Analysis and Challenges
Data provided by Louise's research was manipulated with a pivot table to isolate theater productions, their qualification as canceled, failed, or successful, with respect to their launch dates.  Then, a specific subset of theater events called plays were shown as success or failure with respect to their original financial goal amount.

    ### Analysis of Outcomes Based on Launch Date
    "C:\Users\aimee\OneDrive\Desktop\Analysis Projects\Crowdfunding Analysis\Resources\Theater_Outcomes_vs_Launch.png"
    The chart titled "Theater Outcomes Based on Launch Date" shows that May, June, and July are months where success is more likely compared to failure because that is where the spread between the two lines on the chart is widest. Conversely, in December, when the lines for successes and failures converge, it is shown that a launch has the least likelihood for success. Changes to the number of canceled events appear no more or less frequent based on the launch date.


    ### Analysis of Outcomes Based on Goals
    "C:\Users\aimee\OneDrive\Desktop\Analysis Projects\Crowdfunding Analysis\Resources\Outcomes_vs_Goals.png" The chart titled "Outcomes Based on Goal" shows the complementary percentages of specific theater subset "plays" as successes  and failures based on their original monetary goals.  The chart appears to show the most divergence at very small goals <5000, where sucess is most likely,  but notably at very large goals of >45000 where failure seems probable. An important reference to the data set is more informative than the chart in this case.  Because the data sample is skewed left, the data significantly indicate that success is more likely than failure with goals set below 10000.

    ### Challenges and Difficulties Encountered
    Challenges of this exercise were working with unfamiliar formulas and a dataset that was provided without reservation.  When producing the requested outcomes based on goal, there was a null value for all cancellations of plays.  This was a potential red flag, along with realizing that the stratifications requested for the goals were skewed hard left.

## Results

- Theater productions should be launched in May, June,  or July.  They should not be launched in December.

- The outcomes of plays which have goals set below 10000 are most likely to be successful.Furthermore, outcomes of plays which have goals over 40000 are very likely to fail.

- Limitations of this dataset are that outliers have not been evaluated for reasonableness. Significance of launch months is limited to only 2015-2017.  Success and Failure definitions applied were one-dimensional, and the datapoint "goal" seems deceptive.

- Other visuals that could be meaningful might be to chart the Average donation with respect to type of production. More insight could be gained across the dataset using bar charts to indicate frequencies along with goals and success.

