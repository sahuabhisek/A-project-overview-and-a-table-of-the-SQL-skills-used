# A-project-overview-and-a-table-of-the-SQL-skills-used
The table structure (CREATE TABLE and the COPY import) All 10 business questions, each with a one-line explanation and its SQL Key learnings, plus a thank-you line to Sathish Dhawale Sir, Founder of Skill Course I corrected some queries from your original file. Several of them would give wrong answers, so the PDF shows the fixed versions.
It contains:
A project overview and a table of the SQL skills used
The table structure (CREATE TABLE and the COPY import)
All 10 business questions, each with a one-line explanation and its SQL
Key learnings, plus a thank-you line to Sathish Dhawale Sir, Founder of Skill Course
I corrected some queries from your original file. Several of them would give wrong answers, so the PDF shows the fixed versions. Please check them against your own results before you post.
Q1: COUNT(*) only counts rows, so I used SUM(Patients_Count) for the real patient total.
Q2: COUNT(*) counts records, so I used AVG(Doctors_Count) for the average number of doctors.
Q3 and Q9: These now group by department and sum the patients. Your version grouped by hospital as well, and counted rows.
Q4: I added LIMIT 1 so it returns only the single top hospital.
Q5: This now divides the expense by the number of days stayed, to get the daily average.
Q6: Your query had a missing comma and referenced age, which isn’t in your table. It now returns the one record with the longest stay.
Q7: This now sums patients per city.
Q8: This now averages the stay in days, Discharge_Date - Admission_Date.
If you want to keep your original queries in the PDF, tell me and I’ll swap them in.
For LinkedIn, you can attach the PDF as a document post and add a caption such as: “Completed a Hospital Patient Data Analysis project in SQL, covering aggregates, GROUP BY, date functions and Top-N queries. Thank you Sathish Dhawale Sir and Skill Course for the guidance. #SQL #DataAnalytics #PostgreSQL”.
