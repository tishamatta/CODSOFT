# CODSOFT

1. It starts by importing the java.util package to use the Scanner class for input.
2. In the 'main' method:

   It initializes a 'Scanner' object named 'sc' to read input from the user.
   It declares an integer variable 'n' to store the total number of subjects.
   It prompts the user to enter the total number of subjects and reads this value into 'n' using 'sc.nextInt()'.

3. It creates an integer array named 'arr' of size 'n' to store the marks obtained in each subject.
4. It uses a 'for' loop to iterate through each subject, prompting the user to enter the marks for each subject and storing them in the 'arr' array.
5. It calculates the total marks by summing up all the marks in the 'arr' array.
6. It calculates the average marks by dividing the total marks by the number of subjects. Note that it assigns the result to a 'float' variable 'average' to ensure the average is represented with decimal places.
7. It determines the grade based on the calculated average marks:

   If the average is greater than or equal to 90, it assigns the grade 'A'.
   If the average is between 80 (inclusive) and 90 (exclusive), it assigns the grade 'B'.
   If the average is between 70 (inclusive) and 80 (exclusive), it assigns the grade 'C'.
   If the average is between 60 (inclusive) and 70 (exclusive), it assigns the grade 'D'.
   Otherwise, it assigns the grade 'E'.

8.  Finally, it displays the following information:

    The total marks obtained.
    The average marks with a percentage sign.
    The assigned grade.
