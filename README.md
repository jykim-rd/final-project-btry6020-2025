# final-project-btry6020-2025
This is my final project for the course BTRY 6020 (Spring 2025).

# Student Final Exam Score Prediction

## Project Overview
The goal of this analysis is to examine the extent to which demographic, lifestyle, academic, and environmental factors jointly relate to final exam scores among students. using multiple linear regression. 

The dataset for this project is from: https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance?resource=download (see also /Data folder)

It includes records from 1,000 students and contains the following variables:

* age: age in years
* gender: female, male, or other
* study_hours_per_day: daily study time in hours
* social_media_hours: daily social media usage in hours
* netflix_hours: daily Netflix usage in hours
* part_time_job: if the student holds a part time job (Yes or No)
* attendance_percentage: percentage student attended school
* sleep_hours: daily sleep time in hours
* diet_quality: diet quality (Poor, Fair, or Good)
* exercise_frequency: frequency of exercise per week (0-6 days per week)
* parental_education_level: highest level of education student's parents have attained (None, High School, Bachelor, Master)
* internet_quality: quality of student's Internet (Poor, Average, Good)
* mental_health_rating: rating of student's mental health on a scale of 1-10
* extracurricular_participation: if the student participates in extracurricular activities (Yes or No)
* exam_score: final exam score on a scale of 0-100

## Modeling Approach
Two regression models were developed and evaluated:
* Untransformed model: optimized for predictive accuracy
* Transformed model: optimized for meeting all assumptions of linear regression

## How to View Results
Results are documented in the full .rmd file or .htlml gile under the "Results" section. Results are summarized and interpreted under the "Discussion" and "Conclusion" sections.

## How to Run the Analysis
1. Download or clone this repository.
2. Open the provided analysis.Rmd file in RStudio.
3. Run all the code or click "Knit" to generate the full report (HTML or PDF).
