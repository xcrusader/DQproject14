# DQproject14
Jeopardy is a popular American Television show wherein contestants are provided clues and must answer back with questions associated to those clues.

In this project we explore the possibility of winning Jeopardy based on predicting what clues are likely to come up on the Jeopardy board by analyzing clues from previous games.

The dataset of all the clues and their relative questions from the last 30 years are available on line thanks to a group of long standing fans who have maintained the dataset.

Using the concept of hypothesis testing, we hope to identify words that are most likely to occur for repeated questions from over the years and thus get to know what questions are likely to be asked. It must be noted that we failed to run the chi-squared test on the entire dataset because of the sheer volume and the time it takes to process. Instead we simply selected the top 10 most common words in the entire dataset and ran the Chi-squared test against them.
