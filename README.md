# Mental Health Check-In
This code is a console-based mental health assessment tool written in C++. It interacts with the user through a series of questions to determine potential mental health disorders. Based on the user's responses, it provides an indication of possible disorders and recommends further consultation with a psychiatrist.

## Functions Overview
1. rating(int input, int questions): This function takes the total score of responses and the number of questions to calculate whether the user might be suffering from a particular disorder. It returns:
1 if the score indicates a positive diagnosis.
-1 if the score indicates no diagnosis.
0 if the score is inconclusive.

2. end_karwado(): This function gives the user an option to exit the test at any time. If the user decides to exit, it displays a thank-you message and a disclaimer recommending official consultation.
Specific Disorder Functions:

Each of these functions (drugsf(), alcoholf(), dementiaf(), delirium(), etc.) asks a series of questions related to a specific disorder. They collect responses, calculate the sum, and use the rating function to determine if the user shows symptoms of the disorder.
For example, drugsf() assesses symptoms related to drug use disorder, alcoholf() assesses alcohol use disorder, etc.

3. kessler_pysco_test(): This function is intended to measure the psychotic distress level of a person. However, it is not defined in the provided code.

## Mental Disorders Covered
1. Dementia
2. Delirium
3. Alcohol and Drug Use Disorders
4. Tobacco Use Disorders
5. Psychotic Disorders
6. Bipolar Disorder
7. Depression
8. Anxiety Disorders
9. Eating Disorders
10. Sleep Problems
11. Sexual Disorders
12. Mental Retardation
13. Attention Deficit Disorder
14. Conduct Disorder
15. Bereavement Disorders

