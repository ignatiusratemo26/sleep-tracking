# SleepScope Data Analysis Project

Welcome to the SleepScope Data Analysis Project! This repository contains a data science project aimed at uncovering insights into sleep quality based on various lifestyle and demographic factors. The analysis was performed using a dataset provided by SleepInc, featuring anonymized sleep and lifestyle metrics for 374 individuals over the past six months.

## Project Overview

In this project, we explore the relationships between exercise, gender, occupation, BMI category, and sleep quality. The main objectives are:
1. Identify which occupation has the lowest average sleep duration.
2. Determine which occupation has the lowest average sleep quality.
3. Analyze if the occupation with the lowest sleep duration also has the lowest sleep quality.
4. Examine the effect of BMI category on sleep disorder rates, particularly focusing on insomnia.

## Key Findings

- **Occupation with Lowest Sleep Duration**: `lowest_sleep_occ`
- **Occupation with Lowest Sleep Quality**: `lowest_sleep_quality_occ`
- **Same Occupation for Both Lowest Sleep Duration and Quality?**: `same_occ`

### BMI Category and Insomnia Rates

We also investigated how BMI categories affect the rates of insomnia. The resulting dictionary, `bmi_insomnia_ratios`, contains the ratio of people diagnosed with insomnia for each BMI category.

## Dataset

The dataset, `sleep_health_data.csv`, includes 13 columns:

| Column                        | Description                                                    |
|-------------------------------|----------------------------------------------------------------|
| Person ID                     | An identifier for each individual                              |
| Gender                        | The gender of the person (Male/Female)                         |
| Age                           | The age of the person in years                                 |
| Occupation                    | The occupation or profession of the person                     |
| Sleep Duration (hours)        | The average number of hours the person sleeps per day          |
| Quality of Sleep (scale: 1-10)| A subjective rating of the quality of sleep (1 to 10)          |
| Physical Activity Level (min/day) | The average number of minutes the person engages in physical activity daily |
| Stress Level (scale: 1-10)    | A subjective rating of the stress level experienced (1 to 10)  |
| BMI Category                  | The BMI category of the person (e.g., Underweight, Normal, Overweight) |
| Blood Pressure (systolic/diastolic) | The average blood pressure measurement (systolic/diastolic) |
| Heart Rate (bpm)              | The average resting heart rate in beats per minute             |
| Daily Steps                   | The average number of steps taken per day                      |
| Sleep Disorder                | The presence or absence of a sleep disorder (None, Insomnia, Sleep Apnea) |

## Analysis and Results

### Occupation Analysis

- **Lowest Average Sleep Duration**: The occupation with the lowest average sleep duration is stored in the variable `lowest_sleep_occ`.
- **Lowest Average Sleep Quality**: The occupation with the lowest average sleep quality is stored in the variable `lowest_sleep_quality_occ`.
- **Comparison of Sleep Duration and Quality**: The variable `same_occ` indicates whether the occupation with the lowest sleep duration also has the lowest sleep quality (`True` if it is the same, `False` otherwise).

### BMI Category and Sleep Disorders

The dictionary `bmi_insomnia_ratios` contains the ratio of people diagnosed with insomnia for each BMI category, rounded to two decimal places.

## How to Use This Repository

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Pandas

### Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/ignatiusratemo26/sleepscope-data-analysis.git
   cd sleepscope-data-analysis
