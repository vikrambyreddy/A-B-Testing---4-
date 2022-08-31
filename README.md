# A-B-Testing-4


What is A/B Testing ?
A/B Testing is a tried-and-true method commonly performed using a traditional statistical inference approach grounded in a hypothesis test (e.g. t-test, z-score, chi-squared test). In plain English, 2 tests are run in parallel:

Treatment Group (Group A) - This group is exposed to the new web page, popup form, etc.

Control Group (Group B) - This group experiences no change from the current setup.

The goal of the A/B is then to compare the conversion rates of the two groups using statistical inference.

The problem is that the world is not a vacuum involving only the experiment (treatment vs control group) and effect. The situation is vastly more complex and dynamic. Consider these situations:

Users have different characteristics: Different ages, genders, new vs returning, etc

Users spend different amounts of time on the website: Some hit the page right away, others spend more time on the site

Users are find your website differently: Some come from email or newsletters, others from web searches, others from social media

Users take different paths: Users take actions on the website going to different pages prior to being confronted with the event and goal

Business Statment
In the experiment, Udacity tested a change where if the student clicked “start free trial”, they were asked how much time they had available to devote to the course.

If the student indicated 5 or more hours per week, they would be taken through the checkout process as usual. If they indicated fewer than 5 hours per week, a message would appear indicating that Udacity courses usually require a greater time commitment for successful completion.

![image](https://user-images.githubusercontent.com/63223960/187780462-a0ddfdb3-655d-4cf4-ba9c-0a8eed8c6742.png)


The goal with this popup was that this might set clearer expectations for students upfront, thus reducing the number of frustrated students who left the free trial because they didn’t have enough time.

However, what Udacity wants to avoid is “significantly” reducing the number of students that continue past the free trial and eventually complete the course.

Goal
In this analysis, we will investigate which features are contributing enrollments and determine if there is an impact on enrollments from the new “Setting Expectations” form.

The users that experience the form will be denoted as “Experiment = 1” The control group (users that don’t see the form) will be denoted as “Experiment = 0”.
