# Hospital-Management-Analysis---2

*Project Description:-

The primary objective of this project is to develop a comprehensive and efficient Hospital Management System (HMS) using SQL to streamline and enhance the management of hospital operations. The system aims to: Enhance Data Management and Accessibility, Improve Patient Care and Experience, Streamline Administrative Processes, Ensure Data Security and Privacy, Enable Effective Reporting and Analytics. By achieving these objectives, the project aims to enhance the overall efficiency, effectiveness, and quality of hospital management ultimately leading to improved patient satisfaction and operational excellence.

*Tool Used:-

MySQL

*Tables Used:-

1.patients

2.doctors

3.admissions

4.province_names

*Queries of the Project:-

Q1: Show unique birth years from patients and order them by ascending.

Q2: Show unique first names from the patients table which only occurs once in the list. 
For example, if two or more people are named 'John' in the first_name column then don't include their name in the output list. If only 1 person is named 'Leo' then include them in the output.

Q3: Show patient_id and first_name from patients where their first_name start and ends with 's' and is at least 6 characters long.

Q4: Show the total amount of male patients and the total amount of female patients in the patients table.Display the two results in the same row. 

Q5: Show patient_id, first_name, last_name from patients whos diagnosis is 'Dementia'.Primary diagnosis is stored in the admissions table.Q6: 

Q6: Show first and last name, allergies from patients which have allergies to either 'Penicillin' or 'Morphine'. Show results ordered ascending by allergies then by first_name then by last_name.

Q7: Show patient_id, diagnosis from admissions. Find patients admitted multiple times for the same diagnosis.

Q8: Show the city and the total number of patients in the city.Order from most to least patients and then by city name ascending.

Q9: Show first name, last name and role of every person that is either patient or doctor.The roles are either "Patient" or "Doctor"

Q10: Show all allergies ordered by popularity. Remove NULL values from query.

Q11: Show all patient's first_name, last_name, and birth_date who were born in the 1970s decade. Sort the list starting from the earliest birth_date.

Q12: We want to display each patient's full name in a single column. Their last_name in all upper letters must appear first, then first_name in all lower case letters. Separate the last_name and first_name with a comma. Order the list by the first_name in decending order. EX: SMITH,jane

*Insights:-

1. Congestive Heart Failure is the most frequent diagnosis.
2. Dr. Claude has the highest no. of the patients.
3. Patients diagnosed with major depression have more days of stay.
4. A spike in admissions during the winter season.
5. Most patients are from the Province of Ontario.

