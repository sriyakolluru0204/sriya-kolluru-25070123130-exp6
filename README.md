Title: Study of conditional statements in python
Aim:
To study and understand conditional statements in Python and implement various programs using decision-making structures such as if, elif, 
and else to solve real-world problems like number classification,
grading systems, salary calculation, leap year detection, tax calculation, and date validation

Introduction.
In this experiment, multiple Python programs were implemented using conditional statements to perform various decision-making tasks.
These included checking whether a number is positive, negative, or zero; determining if a number is even or odd; finding the largest of three numbers; assigning grades based on marks; 
checking leap years; identifying vowels and consonants; calculating gross salary and income tax; and validating dates. Each program used logical conditions and comparison operators 
to produce appropriate outputs based on user input,
demonstrating the practical use of conditional statements in solving different computational problems.


1.Algorithm: Check if a Number is Positive, Negative, or Zero
Start
Input a number num
If num > 0
→ Display "Positive number"
Else if num < 0
→ Display "Negative number"
Else
→ Display "Zero"
Stop

2.Algorithm: Check if a Number is Even or Odd
Start
Input a number num
If num % 2 == 0
→ Display "Even"
Else
→ Display "Odd"
Stop

3.Algorithm: Find the Largest of Three Numbers
Start
Input three numbers: A, B, and C
If A ≥ B and A ≥ C
→ Display "Largest = A"
Else if B ≥ A and B ≥ C
→ Display "Largest = B"
Else
→ Display "Largest = C"


4.Algorithm: To Find Grade Based on Marks**

1. Start the program.
2. Input the marks from the user.
3. Check if marks are greater than or equal to 90, then display "Grade A".
4. Else, check if marks are greater than or equal to 80, then display "Grade B".
5. Else, check if marks are greater than or equal to 60, then display "Grade C".
6. Else, check if marks are greater than or equal to 40, then display "Grade D".
7. Else, display "Fail".
8. Stop the program.

5.Algorithm: To Check Whether a Year is a Leap Year**

1. Start the program.
1)Start
2)Input year using year = int(input("Enter a year:"))
3)If (year % 4 == 0 and year % 100 != 0) or year % 400 == 0, print "Leap year"
4)Else, print "Not a leap year"
5)Stop    



6.Algorithm: Increment Date by Given Number of Days**

1. Start the program.
2. Input the initial date (YYYY-MM-DD) from the user.
3. Input the number of days to add.
4. Add the given number of days to the initial date.
5. Display the original date and the new date.
6. Stop the program.


7.Algorithm: To Check Whether a Character is Vowel or Consonant**

1. Start the program.
2. Input a character from the user.
3. Check if the character is in the set (a, e, i, o, u, A, E, I, O, U).
4. If yes, display "Vowel".
5. Otherwise, display "Consonant".
6. Stop the program.

8.Algorithm: To Calculate Gross Salary of an Employee**

1. Start the program.
2. Input the basic salary from the user.
3. If basic salary ≤ 10000, calculate:

   * HRA = 20% of basic
   * DA = 80% of basic
4. Else if basic salary ≤ 20000, calculate:

   * HRA = 25% of basic
   * DA = 90% of basic
5. Otherwise, calculate:

   * HRA = 30% of basic
   * DA = 95% of basic
6. Calculate Gross Salary = Basic + HRA + DA.
7. Display HRA, DA, and Gross Salary.
8. Stop the program.

9.Start
1)Input Date using Date = int(input("Enter a date:"))
2)Input Month using Month = int(input("Enter a month:"))
3)Input Year using Year = int(input("Enter a year:"))
4)If Month in (1,3,5,7,8,10,12)
5)If Date == 31 and Month == 12
     Year += 1
     Date = 1
     Month = 1
6)Else if Date < 31
     Date += 1
7)Else
     Date = 1
     Month += 1
8)Else if Month in (4,6,9,11)
9)If Date == 30
     Date = 1
     Month += 1
10)Else if Date < 30
     Date += 1
11)Else if Month == 2
12)If (year % 4 == 0 and year % 100 != 0) or year % 400 == 0
  If Date == 29
     Date = 1
     Month += 1
  Else if Date < 29
     Date += 1
  Else
     If Date == 28
     Date = 1
     Month += 1
13)Print Date,"/",Month,"/",Year
14)Stop   





10. Algorithm: To Calculate Income Tax Based on Annual Income**

1. Start the program.
2. Input the annual income from the user.
3. If income ≤ 2,50,000, set tax = 0.
4. Else if income ≤ 5,00,000, calculate tax = 5% of (income − 2,50,000).
5. Else if income ≤ 10,00,000, calculate tax = 5% of 2,50,000 + 20% of (income − 5,00,000).
6. Else, calculate tax = 5% of 2,50,000 + 20% of 5,00,000 + 30% of (income − 10,00,000).
7. Display the income tax.
8. Stop the program.

Conclusion.
experiment helped in understanding the concept and importance of conditional statements in Python. Through various practical examples, the use of if, elif, and else statements
was learned effectively. The experiment improved logical thinking, decision-making skills, and programming ability. It also demonstrated how conditional statements are used 
in real-world applications such as grading, financial calculations, and date validation. Overall, 
the experiment provided a strong foundation in implementing decision-making structures in Python programs.

