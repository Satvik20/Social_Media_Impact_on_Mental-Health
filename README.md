[README.md](https://github.com/user-attachments/files/32799240/README.md)
# Social_Media_Impact_on_Mental-Health# YRBS 2023 – Social Media & Wellbeing (cleaned subset)

**Source:** CDC, 2023 National Youth Risk Behavior Survey (YRBS), https://www.cdc.gov/yrbs/data/index.html
**Who:** 20,103 US high school students (grades 9–12), nationally representative, surveyed in spring 2023. One row = one student.
**Files used:** `XXH2023_YRBS_Data.dat` + `2023XXH-SAS-Input-Program.sas` (column positions). Converted with `convert_yrbs.py`.

## Checks against CDC's published figures (weighted)
- Used social media several times a day or more: 77.0% (CDC: 77.0%)
- Used it more than once an hour: 29.5% (CDC: 29.5%)
- Frequent use among females: 81.8% (CDC: 81.8%)
- Felt sad or hopeless: 39.7% (CDC: ~40%)

## Columns
| Column | Meaning |
|---|---|
| student_id | Row number (added) |
| age | 12 = "12 or younger", 18 = "18 or older" |
| sex, grade, race_ethnicity | Demographics |
| social_media_use / social_media_level | How often they use social media (1 = don't use … 8 = more than once an hour) |
| frequent_social_media | Yes = several times a day or more (CDC definition) |
| sad_hopeless | Felt sad or hopeless almost every day for 2+ weeks in the past year |
| mental_health_not_good / _level | How often mental health was not good in past 30 days (1 = Never … 5 = Always) |
| difficulty_concentrating | Serious difficulty concentrating, remembering or deciding |
| sleep_hours / sleep_8plus | Sleep on an average school night (4 = "4 or less", 10 = "10 or more") |
| grades / grades_mostly_A_or_B | Self-reported grades in past 12 months |
| bullied_at_school, bullied_electronically | Bullied in past 12 months |
| active_days_per_week | Days with 60+ minutes of physical activity (0–7) |
| sports_teams | Number of sports teams (3 = "3 or more") |
| breakfast_days_per_week | Days ate breakfast (0–7) |
| feel_close_to_school | Feel close to people at school |
| parental_monitoring | Parents know where they are / who with |
| survey_weight, stratum, psu | CDC survey design variables |
