# DVC-Circadian-Phenotyping
Data supporting the scientific publication "Evaluation of the Digital Ventilated Cage System for Circadian Phenotyping" by S. Tir, R.G. Foster, and S.N. Peirson.

The complete metadata of the animals used in this study is provided in **DVC_animals.xslx**.
The complete timeline of the circadian screen is provided in **DVC_CP_timeline.xslx**.
The complete timeline of the Cry-deficient study is provided in **DVC_CRY_timeline.xslx**.

Files used to compute the overall actograms of the circadian screen are provided as follows:
1. **DVC_CP_raw.csv**: raw data for all 12 animals for the complete duration of the experiment in 1 min bins, dowloaded from the DVC Analytics platform.
2. **DVC_CP_clean.csv**: a cleaned version of the previous file is provided to compute actograms and activity onsets in ActogramJ. Only data of interest was selected (columns for time and activity counts), and columns were renamed for clarity. Start/End times were refined to exclude habituation period and termination of the experiment. A 30 min running average was applied to account for missing values (daily checks) in R Studio.
3. **DVC_CP_actograms.pdf**: actograms of the full circadian screen for each of the 12 animals.

To compute circadian disruption measures for the circadian screen, the following 7 days of raw data were used, respectively:
1. DD: March 20-26, 2022. It should be noted that F3 has missing data from 7am on March 26, 2022.
2. LD: April 4-10, 2022.
3. LL: April 25-May 1, 2022.

Files used to compute the Cry-deficient (CRY KO) vs wild-type (WT) actograms are provided as follows:
1. **DVC_CRY_raw.csv**: raw data for all 12 animals for the complete duration of the experiment in 1 min bins, dowloaded from the DVC Analytics platform.
2. **DVC_CRY_clean.csv**: a cleaned version of the previous file is provided to compute actograms and activity onsets in ActogramJ. Only data of interest was selected (columns for time and activity counts), and columns were renamed for clarity. Start/End times were refined to exclude habituation period and termination of the experiment. A 30 min running average was applied to account for missing values (daily checks) in R Studio.
3. **DVC_CRY_actograms.pdf**: actograms of the full Cry-deficient study for each of the 12 animals.

To compute circadian disruption measures for the circadian screen, the following 7 days of raw data were used, respectively:
1. LD: July 19-26, 2023.
2. DD: July 31-August 6, 2023.
