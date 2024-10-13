# StudentGradeTracker


This project is designed to help a teacher manage and analyze student grades. It allows the teacher to input multiple grades, store them in a dynamic list (using an ArrayList), and then calculate key statistics like the average, highest, and lowest grades. Here's a breakdown of the core elements:

1. Data Storage with ArrayList:
An ArrayList is used to store the grades because it allows dynamic resizing. This means the teacher can input as many grades as needed, and the list will grow accordingly.
2. User Input:
The program prompts the teacher to enter grades one by one using the console.
The teacher can stop entering grades by inputting -1, which signals the end of input.
3. Core Calculations:
Average: The sum of all grades is divided by the total number of grades to calculate the average.
Highest Grade: As the grades are entered, the program keeps track of the highest grade.
Lowest Grade: Similarly, the program keeps track of the lowest grade as the teacher enters the data.
4. Displaying Results:
Once all grades are entered, the program prints out the calculated average, highest, and lowest grades.
5. Scanner Class for Input:
The Scanner class is used to read input from the user. This makes it interactive and user-friendly as the teacher can directly input data from the console.
Benefits of the Project:
Dynamic Input Handling: Teachers can input any number of grades without worrying about fixed array sizes.
Statistical Insights: It helps teachers quickly find important statistics like average, highest, and lowest grades, which can be useful for grading assessments or student performance analysis.
Easy to Use: The user interface is simple and straightforward, allowing even non-technical users to operate it with ease.
Potential Enhancements:
Input validation (e.g., ensuring the grades are within a valid range).
Option to update or remove grades.
A graphical user interface (GUI) for easier interaction.
This project is a practical tool for any teacher needing a simple way to manage and analyze student grades.






