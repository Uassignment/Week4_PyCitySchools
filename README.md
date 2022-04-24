# Week4_PyCitySchools

# Overview of the school district analysis

The purpose of our analysis is to find the overall passing percentages of the students as well as the overall integrity of the test data. The analysis identified missing test scores for 9th graders at Thomas High School. To avoid calculation errors all missing results for reading and math scores from Thomas High School have been replaced with NaNs.

# Results

There was significant difference in the school summary data, when recalculated with the missing test scores removed from the data. 

per_school_summary_df - with missing data

![THS result with 9th grader score](https://user-images.githubusercontent.com/102333060/164983651-25f6f5ff-01a0-4e29-aed9-7748f7506bb6.png)

Per_school_summary_df - after replacing the overall passing percentage for Thomas High School

![Replace the overall passing percentage for Thomas High School](https://user-images.githubusercontent.com/102333060/164983687-2c57e10c-4b64-4ce7-8196-33c60c57a4e2.png)


Replacing the data didn’t affect the other high schools, however for a person who is reviewing the school’s data, data will show as null.

![NaN 9th grade test score](https://user-images.githubusercontent.com/102333060/164983756-12ea307c-e0eb-48b9-a30f-ea82d902973a.png)

The numbers stay nearly identical since the 9th graders are nullified from the statistics. Overall passing percentage does not change. Scores by school type are not altered at all.

# Conclusion

The analysis was able to identify and resolve issue to avoid possible calculation error on the overall analysis outcomes. Missing the 9th grader score hasn’t affect either the school or the district significantly.
