## Challenge: Evaluate an experiment analysis
 
### Now it's time to flex your critical evaluation skills. Read the following descriptions of an experiment and its analysis, identify the flaws in each, and describe what you would do to correct them.

1. The Sith Lords are concerned that their recruiting slogan, "Give In to Your Anger," isn't very effective. Darth Vader develops an alternative slogan, "Together We Can Rule the Galaxy." They compare the slogans on two groups of 50 captured droids each. In one group, Emperor Palpatine delivers the "Anger" slogan. In the other, Darth Vader presents the "Together" slogan. 20 droids convert to the Dark Side after hearing Palpatine's slogan, while only 5 droids convert after hearing Vader's. The Sith's data scientist concludes that "Anger" is a more effective slogan and should continue to be used.
```
The sampling size of 50 is too small.  The experiment should be extended and include a larger population of droids.

The experiment should also eliminate contextual bias by having delivering the slogans by a non-partial 3rd party.
Having the author of the slogan deliver the reading ot the droids will introduce Observer Bias.
```
1. In the past, the Jedi have had difficulty with public relations. They send two envoys, Jar Jar Binks and Mace Windu, to four friendly and four unfriendly planets respectively, with the goal of promoting favorable feelings toward the Jedi. Upon their return, the envoys learn that Jar Jar was much more effective than Windu: Over 75% of the people surveyed said their attitudes had become more favorable after speaking with Jar Jar, while only 65% said their attitudes had become more favorable after speaking with Windu. This makes Windu angry, because he is sure that he had a better success rate than Jar Jar on every planet. The Jedi choose Jar Jar to be their representative in the future.
```
The experiment has a design flaw in that Windu was sent to only unfriendly planets will JarJar was only sent to friendly planets.

The experiment does not describe the sampling of the populations on each planet.
The sampling-bias can be corrected by creating 2 groups for each planet that represent the general population.
```
1. A company with work sites in five different countries has sent you data on employee satisfaction rates for workers in Human Resources and workers in Information Technology. Most HR workers are concentrated in three of the countries, while IT workers are equally distributed across worksites. The company requests a report on satisfaction for each job type. You calculate average job satisfaction for HR and for IT and present the report.
```
The survey or questionaire used for each country may have bias if they are not normalized for culture and work-type.  A normalized survey should be created that can be used for any job-type and country.

This experiement will be susceptible to sampling bias because HR workers are heavily concentrated in only 3 countries.
```
1. When people install the Happy Days Fitness Tracker app, they are asked to "opt in" to a data collection scheme where their level of physical activity data is automatically sent to the company for product research purposes. During your interview with the company, they tell you that the app is very effective because after installing the app, the data show that people's activity levels rise steadily.
```
The data collected needs to be for a longer period.  The immediate feedback after installation will be very skewed.  

The data collected should be segmented across sex/location/and other demographics in order to control for the general popluation.

There may be sampling bias because the people who download the app may be more generally active than the normal population.
```
1. To prevent cheating, a teacher writes three versions of a test. She stacks the three versions together, first all copies of Version A, then all copies of Version B, then all copies of Version C. As students arrive for the exam, each student takes a test. When grading the test, the teacher finds that students who took Version B scored higher than students who took either Version A or Version C. She concludes from this that Version B is easier, and discards it.
```
There needs to be a control group established for each version of the test and also the length of time that the test versions are in circulation needs to be given to a larger sample size.  Also, removing version-B after 1-experiment is too soon.  She should allow the test to be administered across several school session or semesters to gather enough data to compare.

In the experiment, it is not stated how students took the test.  Knowing this, we can design a better experiment and decide what sampling is appropriate.

There are no details about the format of the test.  Is it multiple choice or free-form answer ?  There may be an observer bias since she wrote the test and is also grading the test.  If the was a multiple-choice test this is less of a problem.  If it's free-form answer test and she is the one grading it she will bias the test score and results.
```
