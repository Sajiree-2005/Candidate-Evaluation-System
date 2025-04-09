Microsoft Candidate Evaluation Program
This C program evaluates a candidate's eligibility and interview results based on their academic performance, experience, certifications, and skills. The program is designed for a fictional Microsoft recruitment process and assigns a job role and package based on a series of evaluations.

Features
Candidate Information Collection:

The program collects basic information from the candidate, including:

Name

CGPA

Number of credits

Number of certifications

Number of referrals

Years of experience

Number of internships

Eligibility Check:

The candidate must meet the following minimum requirements to qualify for an interview:

CGPA >= 8.5

Credits >= 5

Certifications >= 2

Referrals >= 1

Internships >= 1

Interview Evaluation:

If the candidate qualifies, they are asked to rate themselves on the following parameters:

Technical knowledge

Coding skills

Innovation

Personality

Communication skills

The total score is calculated, and based on the total score and years of experience, the candidate is assigned a job role and salary package.

Job Role Assignment:

Based on the total interview marks and experience, the candidate may be assigned one of the following roles:

Project Manager (with a salary of 30 LPA if experience is >= 6 years)

Assistant Manager (with a salary of 25 LPA if experience is >= 4 years)

Software Engineer (with a salary of 20 LPA if experience is <= 3 years)

Software Developer (with a salary of 15 LPA if total marks >= 35)

Junior Software Engineer (with a salary of 10 LPA if total marks >= 30)

Intern Software Engineer (with a salary of 5 LPA if total marks >= 25)

If the candidate does not meet the minimum requirements, they are rejected.

Prerequisites
C Compiler (e.g., GCC or any standard C compiler)

A basic understanding of C programming

Compilation and Execution
Save the Code: Save the provided C code in a file named candidate_evaluation.c.

Compile the Program: Use the following command to compile the code:

nginx
Copy
gcc candidate_evaluation.c -o candidate_evaluation
Run the Program: After compilation, run the program with:

bash
Copy
./candidate_evaluation
Follow the Prompts: The program will prompt you to enter details such as your name, CGPA, credits, certifications, and more. Once the data is entered, the program will calculate and display your evaluation results.

Example Output
yaml
Copy
Enter your name:
John
Enter cgpa:
8.7
Enter number of credits:
6
Enter number of certifications:
3
Enter number of referals:
2
Enter number of years of experience:
5
Enter number of internships:
2
NAME:John
CGPA:8.700000
CREDITS:6
CERTIFICATIONS:3
REFERALS:2
YEARS OF EXPERIENCE:5
NUMBER OF INTERNSHIPS:2
THE CANDIDATE IS ACCEPTED FOR AN INTERVIEW IN MICROSOFT
IN THE INTERVIEW CANDIDATE WILL BE GIVEN MARKS OUT OF 10 FOR EVERY HIRING PARAMETER
THE EVALUATION OF CANDIDATE IN INTERVIEW IS AS FOLLOWS:
Enter marks for technical knowledge:
8
Enter marks for coding skills:
7
Enter marks for innovation:
6
Enter marks for personality:
9
Enter marks for communication skills:
7
TECHNICAL KNOWLEDGE:8
CODING SKILLS:7
INNOVATION:6
PERSONALITY:9
COMMUNICATION SKILLS:7
total marks=37
CANDIDATE HAS BEEN HIRED AS SOFTWARE DEVELOPER
CANDIDATE WILL RECEIVE PACKAGE OF 15 LPA
Conclusion
This program serves as a basic example of how a recruitment evaluation system could work based on a set of predefined criteria. It takes input from the user, performs checks, and provides an outcome based on the input data.

