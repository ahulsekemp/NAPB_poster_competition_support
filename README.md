# NAPB_poster_competition_support
This repository includes files in support of the Education Committee of the National Association of Plant Breeders annual poster competition.

## NAPB+Poster+Competition+-+Judging+Scoresheet+-+2021_August+18,+2021_17.29_testexample.csv
Includes an example of how the Poster Presenter information should be formatted as input through the shell script.
The first 3 column headers need to EXACTLY match the example to work correctly.

## ScoresToStudents_NAPB_2021.sh 
Is a shell script designed to automatedly send out the Presenter Scores and Feedback from the poster competition; through a high performance cluster (HPC). Some comments are included in the script to ensure it works correctly.

* It is highly suggested to test an initial run with a *.csv file to yourself to make sure that the script is indeeding sending information to all presenters.
* Line 32 in this file can be customized for any messaged you'd like to go out to the Presenters; but was made generic to support future competitions.
* Line 38 should be updated if the scoring categories or rubrics are changed in future competitions.

Again - The shell script (.sh) NEEDS to be updated each year if the rubric changes.

To run ScoresToStudents_NAPB_2021.sh interactively change the file to executable using > chmod +x ScoresToStudents_NAPB_2021.sh then you can run on the command line ./ScoresToStudents_NAPB_2021.sh when place in it's own directory with the NAPB+Poster+Competition+-+Judging+Scoresheet+-+2021_August+18,+2021_17.29_testexample.csv it will work automatically. (This is true on servers that have the email function set up.)
