# Smart-Exam-Scheduler-System
We have 10 exams {E1, E2, E3, …, E10} and the task is to assign a hall and a time slot for each exam. The set of available time slots is T = {t1, t2, t3, t4} and the set of available halls is {A, B, C,}. However, to provide correct assignments for the exams, we need to satisfy the following constraints:
•	The 1st exam should take place before the third exam
•	The 10th exam occurs after the 9th and 4th exams.
•	The 1st, 3rd, and 4th exams should take place in either Hall A or Hall C.
•	The 7th, 8th, 9th, and 10th exams should be in either Hall A or Hall B.
•	There are no two exams occur at the same place and time.
Please note the following:
•	The time slots are ordered chronologically based on the slot number. For example, the time slot t3 comes after t2, and so on. 
•	The above exam scheduling system can be modeled and solved as a constraint satisfaction problem CSP and you are supposed to provide a suitable assignment for the exams.
•	Your solution should assign a tuple composing of a time slot and a hall for each exam, e.g.,   E2  (t4, A)
