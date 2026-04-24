# student_analysis.py
Python project for analyzing student performance, including average calculation, topper identification, and pass/fail analysis.
# Student Data Analysis Project

students = {
    "Arun": 85,
    "Bala": 72,
    "Charan": 90,
    "Divya": 65,
    "Esha": 78
}

# Calculate average marks
total = sum(students.values())
average = total / len(students)

print("Average Marks:", average)

# Find Topper
topper = max(students, key=students.get)
print("Topper:", topper, "-", students[topper])

# Pass/Fail
print("\nStudent Results:")
for name, marks in students.items():
    if marks >= 40:
        print(name, ":", "Pass")
    else:
        print(name, ":", "Fail")
        ## Python Project: Student Data Analysis

- Calculated average marks
- Identified top-performing student
- Checked pass/fail status using conditions
