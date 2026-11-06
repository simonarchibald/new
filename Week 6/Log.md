**November 6, 2026**

R notebook
- Opened the archaeo-stats-in-R notebook in Google Colab and saved a copy to my Drive.
- Pressed "Run all." The first cell (installing the archdata and RcmdrMisc packages) seemed to get stuck and nothing else ran.
- Looked at the output and saw it wasn't actually frozen. It was installing archdata and RcmdrMisc, plus a long list of other packages that RcmdrMisc depends on (fracdiff, lme4, Hmisc, car, and about 30 more).
- So one line of code was really installing dozens of packages, which is why it took so long. "Run all" made it look broken because every other cell was waiting behind the first one.
- Also noticed that in the last cell (graveyard data from past students) the code looked like it was all on one line, which would probably give an error.

Chi-square
- Read through the chi-square walkthrough Dr. Graham posted.
