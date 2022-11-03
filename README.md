# Description of project

In this project, an A/B test was running to evaluate whether to introduce a change to the trial process (additional window after a click on the button "Start free trial") to reduce the number of people who don't buy a subscription after the trial.

<b> Stages of the experiment </b>

Experiment Design
1) Experiment overview and hypothesis formulation
2) Choosing unit of diversion
3) Choosing invariant metrics (for sanity check)
   - Number of cookies: number of unique cookies to view the course overview page;
   - Number of clicks: number of unique cookies to click the "Start free trial" button (which happens before the free trial screener is trigger);
   - Click-through-probability (CTP): number of unique cookies to click the "Start free trial" button divided by number of unique cookies to view the course overview page. 
5) Choosing evaluation metrics
   - Gross conversion: number of user-ids to complete checkout and enroll in the free trial divided by number of unique cookies to click the "Start free trial" button;
   - Retention: number of user-ids to remain enrolled past the 14-day boundary (and thus make at least one payment) divided by number of user-ids to complete checkout;
   - Net conversion: number of user-ids to remain enrolled past the 14-day boundary (and thus make at least one payment) divided by the number of unique cookies to click the "Start free trial" button.
7) Measuring Variability (based on standard deviation)
8) Calculating sample size
9) Choosing Duration of experiment

Experimental Analysis
1) Sanity Checks for invariant metrics
2) Effective Size Test for evaluation metrics 
3) Sign Test for evaluation metrics 

<b> Recommendation </b>

The A/B test results showed that the number of people who sign up for the trial period with these changes does decrease, but it doesn't affect the number of people who sign up for a paid subscription after the trial period ends. So we have only achieved a decrease that does not affect our sales. Consequently, a recommendation is not to introduce this change, as there is no noticeable business benefit.
