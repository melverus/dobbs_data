# dobbs_data
Project: Did overturning Roe make racial disparities in maternal mortality worse?

Analysis of maternal mortality and other adverse outcomes since the overturning of *Roe v. Wade* (Dobbs v. Jackson Women's Health Organization, June 2022)

## Data Sources
 
- **CDC WONDER** — [wonder.cdc.gov](https://wonder.cdc.gov)
  - *Natality* dataset: live births by state, race/ethnicity, and year *(natality_2016-2024.csv)*
  - *Underlying Cause of Death* dataset: maternal deaths by state, race/ethnicity, and year *(Cause_of_Death_2018-2024.csv)*
  - Years used: 2018–2024 (pre- and post-Dobbs)
- **KFF's Abortion in the United States Dashboard** — [kff.org]([https://states.guttmacher.org/policies/](https://www.kff.org/womens-health-policy/abortion-in-the-u-s-dashboard/))
  - State-level abortion policy classifications, used to group states into "restrictive" vs. "protective" buckets
  - Year used: 2026
 
## Future Direction

- **State Level Abortion Policy Data**:
  - The current structure of this project compares a snapshot from March 9, 2026 of state level policy to CDC mortality data from 2018-2023
  - A future step for this project is to create a comparison of policy changes over time spanning from at least 2018-2026

- **Supplementary/contextual sources** (qualitative section only):
  - Reporting from NPR, Texas Tribune, and the Women's Refugee Commission on pregnant unaccompanied minors in federal custody
  - KFF and advocacy-organization reporting on structural barriers to reproductive healthcare access by race and by trans status
