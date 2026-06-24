<!-- 21 June 2026 -->
<!-- Basic Analysis -->
student_id: Unique id for each student
age: his/her age
gender: his/her gender
school_type: public or private school
parent_education: eduacation of parent either educate(graduate or postgraduate, diplome, etc) or uneducated
study_hours: how many ours student study
attendance_percentage: his/her attendance in percentage
internet_access: have access to internet or not
travel_time: travel time (maybe college to home)
extra_activities: acquire extra activities
study_method: using what he/she studies (notes, online, grp stuies, textbook, coaching, etc)
math_score: score in maths
science_score: score in science
english_score: score in english
overall_score: overall score give performance
final_grade: performance grade

<!-- Business Insights -->
1. Overall Performance of Students?
2. Which subject need more support?
3. Impact of Extra curricular activites?
4. Which gender is leading?
5. Lowest Scoring Student?
6. Topers of our school?
7. Best performing subject?
9. Does Parent Education impact student performance?
9. Study hour and self study benefits?
10. Does attendance affect student performance?
11. Do students with internet access perform better?
12. Which study method produces the highest scores?
13. Which school type performs better?
14. Does travel time affect academic performance?


<!-- future use -->
<!-- Students who study more than 4 hours score significantly higher than those studying less than 2 hours.

or

Students with attendance below 70% are much more likely to receive grades D and F.

or

Mathematics has the lowest average score, indicating a need for additional support. -->

<!-- DATA IS CLEANED ALREADY -->

# Data Modeling + KPI Planning
# KPIS
1. Total Students   
2. Average Overall Score
3. Pass Percentage
4. Average Attendance
5. Average Study Hours
6. Top Performing Subject
7. Lowest Performing Subject

# CHARTS
# Section A — Overall Performance
1. Average score by subject (COLUMN CHART)
2. Grade distribution (COLUMN CHART)
3. Gender comparison (BAR CHART) (Average Overall Score by Gender or Pass % by Gender) ?
4. School type comparison (BAR)
# Section B — Factors Affecting Performance
5. Study hours vs overall score (SCATTER)
6. Attendance vs overall score (SCATTER)
7. Parent education vs performance (BAR)
8. Internet access vs performance (BAR)
9. Extra activities vs performance (BAR)
10. Best study methods (BAR)
# Section C — Student Insights
11. Top students (TABLE)
12. Lowest students (TABLE)

<!-- DASHBOARD -->
# PAGE 1
# STUDENT PERFORMANCE ANALYSIS
# KPIS
1. Total Students   2. Average Overall Score    3. Pass Percentage  4. Average Attendance
5. Average Study Hours  6. Top Performing Subject   7. Lowest Performing Subject

# CHARTS
# Section A — Overall Performance
1. Average score by subject (COLUMN CHART) 2. Grade distribution (COLUMN CHART)
3. Gender vs Average Overall Score (BAR CHART)  4. School type Average overall score (BAR)

This page answers:
How are students doing overall?
Which subject is strongest/weakest?
How are grades distributed?
Is there a difference by gender or school type?



# PAGE 2
# Section B — Factors Affecting Performance
5. Study hours vs overall score (SCATTER) 6. Attendance vs overall score (SCATTER)
7. Parent education vs performance (BAR) 8. Internet access vs performance (BAR)
9. Extra activities vs performance (BAR) 10. Best study methods (BAR)
# Section C — Student Insights
11. Top students (TABLE) 12. Lowest students (TABLE)


This page answers:

Why are some students doing better?
Which factors are associated with performance?
Which students deserve recognition?
Which students may need support?


# DAX
Total Students = DISTINCTCOUNT(student_id)
Average Overall Score = AVERAGE(overall_score)
Pass Percentage = AVERAGE(overall_score/3)
Average Attendance = AVERAGE(attendance_percentage)
Average Study Hours = AVERAGE(study_hours)
Top Performing Subject = MAX(AVERAGE(math_score), AVERAGE(science_score), AVERAGE(english_score))
Lowest Performing Subject = MIN(AVERAGE(math_score), AVERAGE(science_score), AVERAGE(english_score))