## Handling of `parental_education_level` Column

During analysis, I made the decision to remove the `parental_education_level` column.  
Although it may show some correlation with student performance, deeper reflection and research showed that:

> **Both educated and uneducated parents can be pushers.**  
> Pressure from any parent — regardless of background — can negatively affect a student’s habits, emotions, and autonomy.

This column also contained around **9% missing values**, which would require assumptions or dropping rows — both of which could damage data integrity.

Most importantly, **parental personality, care, and presence** are what truly shape a student,  
and those cannot be captured by a single education label.

I chose to remove this column not just for technical reasons,  
but to make sure this project remains fair, respectful, and focused on the student — not on stereotypes.

Student Exam Score Prediction
Overview
This project builds a linear regression model to predict student exam scores based on their habits and lifestyle features.

The goal is to understand which factors influence exam performance and how strong those influences are.

Key Findings
Study hours, attendance, exercise frequency, and mental health rating have a strong positive effect on exam scores.

Social media hours, Netflix hours, and internet quality show a negative correlation with exam performance.

Having a part-time job is linked to a slight decrease in exam scores, possibly due to less study time.

Students with a combination of the “good” habits score significantly higher (average 93.82) than others (average 69.48).

Features like diet score were found to have minimal impact and were excluded from the final model for simplicity.
