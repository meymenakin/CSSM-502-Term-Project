# CSSM-502-Term-Project
‘This Music Crept by Me Upon the Waters’ : the Effect of Economic Activity on Listening Habits

This project is conducted for the 'CSSM 502: Advance Data Analysis in Python' course at Koç University.

Created by: Mahmut Eymen Akın. 

Submitted to: Mehmet Fuat Kına.

Below is a rundown for the files in the repository. The core files are (1)-(5):

  1. **CSSM 502 Project makin16.tex** - This is the .tex file where the project's report was transcribed.
  2. **CSSM 502 Project makin16.pdf** - This is the output of compiling the .tex file into a .pdf.
  3. **Part1 - Data Prep and Panel OLS.ipynb** - The first code part. Involves scraping song data, pulling valence scores from Spotify's Public API, merging and preparing final dataset, and running Panel OLS regressions.
  4. **Part 2 - Bayesian & Updating.ipynb** - The second code part. Involves running Bayesian analysis. Initially with no prior. Then with normally distributed priors, uniformly distributed priors, and triangularly distributed priors.
  5. **finaldata.csv** - This is the final merged data which is ready for analysis.
  6. **cssm502 makin16 prelim presentation.pptx** - A presentation of the preliminary results.
  7. convergence.png - This is a figure used in the .tex file and therefore was added. It is a summary version of Part 2 output.
  8. pipeline.png -  This is a figure used in the .tex file and therefore was added. It describes the project's pipeline.
  9. song.csv - This is the output of initial scraping. It contains the song names, countries, weeks, artist names, etc.
  10. song.xlsx - Same output in a different format.
  11. valencerecord.csv - This is the intermediate file where valence scores are written over. Since the same Spotify API request code was run from different accounts and different devices, this file was required to store information.
  12. valencerecord final.csv - This is the final file which includes all valence scores for Top 10 songs for all countries and weeks.
  13. gdp.xlsx - OECD Weekly Economic Activity Tracker data. Machine-readable version, snipped to fit into the timespan of this project.
  14. finaldata.xlsx - Same final data in an alternative format.
