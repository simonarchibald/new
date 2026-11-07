**November 6, 2026**

R notebook
- Opened the archaeo-stats-in-R notebook in Google Colab and saved a copy to my Drive.
- Pressed "Run all." The first cell seemed stuck, but it was actually installing archdata and RcmdrMisc plus about 35 other packages that RcmdrMisc depends on (lme4, Hmisc, car, etc.). It took about 6 minutes. "Run all" made it look broken because every other cell was waiting behind it.
- Fixed the last cell (graveyard data from past students), where the code had been squashed onto one line, by splitting it into separate lines. After that it loaded.
- Loaded the DartPoints data. The notebook points out that the cross-tabulation of point type against blade shape only counted 89 points, even though the dataset has 91 rows, because some blade shapes were never recorded. Adding addNA() brought the missing ones back in.
- Ran chi-square tests on the pithouse data and on the EWBurials data (grave goods vs. group).

Chi-square
- Chi-square walkthrough (Google Sheets)
