README.md
=========
The contents of run_analysis.R, define a function, run_analysis() which requires no arguments.

The function exports a final data frame, 'wmeandf' which is 180 rows by 32 columns. Each row contains an activity name, a user id (1 to 30), and the mean of observed means and standard deviations for that activity for that user.

Due to memory limitations of my PC, I inverted steps 1 and 2 as in the assignment. I completed subsetting of the test and train datasets, including initial labels, separately. Then I merged the two sets. Specifically:
