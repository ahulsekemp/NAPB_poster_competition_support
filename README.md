# NAPB_poster_competition_support
This repository includes files in support of the Education Committee of the National Association of Plant Breeders annual poster competition.

## NAPB+Poster+Competition+-+Judging+Scoresheet+-+2021_August+18,+2021_17.29_testexample.csv
Includes an example of how the Poster Presenter information should be formatted as input through the shell script.

## ScoresToStudents_NAPB_2021.sh 
Is a shell script designed to automatedly send out the Presenter Scores and Feedback from the poster competition. Some comments are included in the script to ensure it works correctly.

* It is highly suggested to test an initial run with a *.csv file to yourself to make sure that the script is indeeding sending information to all presenters.
* Line 32 in this file can be customized for any messaged you'd like to go out to the Presenters; but was made generic to support future competitions.
* Line 40 should be updated if the scoring categories or rubrics are changed in future competitions.
