# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: SAT & ACT Analysis

### Overview

This project examines aggregate SAT and ACT scores and participation rates from each state in the United States to identify trends in our data. Combining data analysis with online research, I've explored likely factors influencing participation rates and scores in various states.

Problem Statement:
> What can we do to increase SAT participation rates across the US?

---

### Summary of Findings & Recommendations

Summary of Findings:
- Participation rates are heavily influenced by state contracts.
- Participation rates between SAT and ACT are negatively correlated. High participation rates in one test usually means low participation in the other i.e. students usually choose either test.
- Participation rates are negatively correlated to test scores. The higher the participation rates, the lower the scores and vice versa.
- SAT is generally more popular along the coast than in inland states.

Recommendations:
- Partnering with states to make SAT mandatory (like in the case of Colorado and Illinois).
- Target states with no mandatory ACT testing AND low SAT participation rates.
- Reducing barriers for SAT e.g. making it more accessible to low income groups by providing fee waivers, free online test practice material, SAT school day as part of school curriculum.

---

### Datasets

- [2017 SAT Scores](./data/sat_2017.csv)
- [2017 ACT Scores](./data/act_2017.csv)
- [2018 SAT Scores](./data/sat_2018.csv)
- [2018 ACT Scores](./data/act_2018_updated.csv)

#### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|index|final|Names of the 50 US States and District of Columbia| 
|sat_participation_2017|float|final|SAT participation rate in 2017| 
|sat_erw_2017|float|final|Average SAT Evidence-Based Reading and Writing score in 2017 (Max score of 800)| 
|sat_math_2017|float|final|Average SAT Math score in 2017 (Max score of 800)| 
|sat_total_2017|float|final|Average SAT Total score in 2017 (Max score of 1600)| 
|act_participation_2017|float|final|ACT participation rate in 2017| 
|act_english_2017|float|final|Average ACT English score in 2017 (Max score of 36)| 
|act_math_2017|float|final|Average ACT Math score in 2017 (Max score of 36)| 
|act_reading_2017|float|final|Average ACT Reading score in 2017 (Max score of 36)| 
|act_science_2017|float|final|Average ACT Science score in 2017 (Max score of 36)| 
|act_composite_2017|float|final|Average ACT Composite score in 2017 (Max score of 36)| 
|sat_participation_2018|float|final|SAT participation rate in 2018| 
|sat_erw_2018|float|final|Average SAT Evidence-Based Reading and Writing score in 2018 (Max score of 800)|
|sat_math_2018|float|final|Average SAT Math score in 2018 (Max score of 800)| 
|sat_total_2018|float|final|Average SAT Total score in 2018 (Max score of 1600)| 
|act_participation_2018|float|final|ACT participation rate in 2018|
|act_composite_2018|float|final|Average ACT Composite score in 2018 (Max score of 36)| 
|act_english_2018|float|final|Average ACT English score in 2018 (Max score of 36)| 
|act_math_2018|float|final|Average ACT Math score in 2018 (Max score of 36)| 
|act_reading_2018|float|final|Average ACT Reading score in 2018 (Max score of 36)| 
|act_science_2018|float|final|Average ACT Science score in 2018 (Max score of 36)| 
|sat_part_change|float|final|Difference between 2018 & 2017 SAT Participation Rates| 
|act_part_change|float|final|Difference between 2018 & 2017 ACT Participation Rates| 
|sat_act_part_diff_2017|final|Final|Difference between 2017 SAT & ACT Participation Rates| 
|sat_act_part_diff_2018|final|Final|Difference between 2018 SAT & ACT Participation Rates| 
