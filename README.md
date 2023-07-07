Hello!

I have created these files using primarily the pandas documentation @ https://pandas.pydata.org/docs/reference/api/pandas.Series.html and https://pandas.pydata.org/docs/reference/frame.html
The regex $ replacement for the categorization of student budgets was taken from https://stackoverflow.com/questions/32464280/converting-currency-with-to-numbers-in-python-pandas

All other code is my own work.

I am attaching the Analysis here for convenience!

The entire dataset contains 15 different schools with a total of 39170 different students. On average, most students pass, with 65% passing both their math and reading requirements.

School budgets vary, but all fall within similar ranges in cost per student, though the passing rates vary wldly and do not correlate to budget nor budget per student.

All charter schools SIGNIFICANTLY outperform their district schoool counterparts, with a staggering 34 percentage point difference between the weakest charter and strongest district school (89.23 to 54.64 respectively). There is not significant deviation within category and all charter / district schools fall within +/-3% of the average school within the categories.

There does not appear to be significant variation in scores divided by grade, with averages only changing between schools, not significantly correlating with grade.

Strangely, overall passing rate seems inversely correlated to budget per student, however I believe this is the case due to the fact that all Charter schools fall on the lower end of the budgets per student, though this itself is quite noteworthy.

Small and Medium schools do not significantly vary, but large schools drop off significantly with the lowest overall passing average at 58.28%. I believe this is once more due to the differences in charter vs district, with only one Charter school falling into the large category, joined by every district school, with none falling into the medium or small categories.