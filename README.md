Here's a detailed project description you can use for your GitHub repository:

---

# SGPA and CGPA Calculator

This Python-based project is an academic grading system calculator designed to compute SGPA (Semester Grade Point Average) and CGPA (Cumulative Grade Point Average) for students. It takes the marks of theory, practical, and external subjects as input, calculates corresponding grades, and outputs the SGPA for each semester and the final CGPA.

## Features

- **SGPA Calculation**: Users can calculate the SGPA for a semester based on the marks of theory, practical, and external subjects.
- **CGPA Calculation**: Users can calculate the CGPA after multiple semesters.
- **Grade Calculation**: The project automatically converts marks into grades based on predefined ranges.
- **Credit Points**: Credit points are assigned to theory, practical, and external subjects, which are used to compute the weighted grade points.
- **Dynamic Input**: Users can enter the number of subjects for each type (theory, practical, external) per semester.

## Input and Output

### Input
1. **Number of Theory Subjects**: The number of theory subjects for the semester.
2. **Theory Subject Marks**: Marks for each theory subject (out of 100).
3. **Number of Practical Subjects**: The number of practical subjects for the semester.
4. **Practical Subject Marks**: Marks for each practical subject (out of 50).
5. **External Subjects (Optional)**: If external subjects exist, input the number of external subjects and their marks (out of 50).

### Output
- **SGPA Report**: A detailed breakdown of the subjects, grades, credits, grade points, and the SGPA for that semester.
- **CGPA Report**: The CGPA across multiple semesters, calculated from the SGPA values.

## Example Usage

```python
# After running the script, you will be prompted to choose:
Enter Your Choice:
1 : SGPA
2 : CGPA
3 : Exit

# If SGPA is chosen:
Enter the number of theory subjects: 3
Enter theory subject marks: 85, 78, 92
Enter the number of practical subjects: 2
Enter practical subject marks: 45, 39
Do you have external subjects? (yes/no): yes
Enter the number of external subjects: 1
Enter external subject marks: 47

# The script will then calculate and display the SGPA:
SGPA for the semester: 8.45

# If CGPA is chosen after entering multiple semesters:
CGPA across all semesters: 8.25
```

## How it Works

1. **Mark Input**: The user inputs the marks for theory, practical, and external subjects.
2. **Grade Calculation**: Marks are converted into grades based on predefined ranges:
   - O (90-100 for theory, 45-50 for practical/external)
   - A+ (80-90 for theory, 40-45 for practical/external)
   - A, B+, B, C, and F for further ranges.
3. **Credit Points**: Each subject is assigned a credit point (4 credits for theory and 1.5/2 credits for practical/external subjects).
4. **SGPA Calculation**: The SGPA is calculated as the sum of all grade points multiplied by their corresponding credit points, divided by the total credit points.
5. **CGPA Calculation**: After multiple semesters, the CGPA is calculated as the average of all semester SGPAs.

## Requirements

- Python 3.x

No external libraries are required as the project only uses built-in Python functions.

## Future Improvements

- Add a GUI for easier user interaction.
- Implement data storage to save previous semester results.
- Add error handling for invalid inputs.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributions

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.

---

This description is designed to provide a comprehensive overview of your project, explain how it works, and invite others to contribute. You can adjust the details as needed for your specific use case.
