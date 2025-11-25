# Black Box Test Cases - Online Examination System

1. Valid Login  
Input: student01 / 12345  
Output: User logged in successfully

2. Empty Login Fields  
Input: blank / blank  
Output: Error message displayed

3. Invalid Password  
Input: student01 / wrong  
Output: Login failed

4. Valid Exam Selection  
Input: Select "Math Exam"  
Output: Questions displayed

5. No Exam Selected  
Input: Click Start without selection  
Output: Please select an exam

6. Submit without answers  
Input: Click Submit directly  
Output: Please answer all questions

7. Partial Answers  
Input: Answer only Q1  
Output: Incomplete exam message

8. Full Submission  
Input: Answer all questions  
Output: Exam submitted successfully
