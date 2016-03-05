School Timetable Generator
--------------------------
There are so many schools in India which spent first few weeks of each academic year
preparing their timetables. I am having a thought - can't we automate it ?

### Major Requirements
 
1. There are L levels
2. Each level has D divisions
3. S = [s1, s2, s3 ... sn] subject are taught at each L = [l1, l2, l3 ... ln]
4. S subjects are being taught by T teachers
5. There are C = L X D classes
6. In a week each class C has P periods
7. Each subject (S) has X lectures in a week per class 
8. A teacher (T) should get a break of 1 period (P) after max 3 coninuous lectures
9. Each class C has a class teacher T (In most cases T will take first period of the day)
10. Subjects belong to categories & subjects from same category should not be taught in consecutive periods
E.g. Sciene, Maths should not be consecutive, two languages should not fall one after another.
