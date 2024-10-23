
<h3 align="center">Importance List Calculator</h3>

## Description

This project, named "Importance List Calculator," is designed to help university students manage their busy course schedules efficiently. It calculates a coefficient for each course based on its AKTS (European Credit Transfer and Accumulation System) value, the percentage of the course within its department, and the number of days remaining until the deadlines for various assessments (such as Midterm, Final, Project, or Quiz). By computing this coefficient for all courses and their respective departments, the program provides a general percentage to determine the importance and priority of each department's courses.

The project consists of the following files:
- `Empty-Excell`: This file serves as a template for users to input the required data.
- `exam.ipynb`: This Jupyter Notebook contains the main algorithms of the program.
- `Example-Excell`: This file demonstrates how to populate the Empty-Excell file with data.
- `myList.csv`: This CSV file is a data format alternative to Example-Excell and is essential for the program's execution.
- `Sample-Result-Example.pdf`: This file provides an example of how the program works without the need for any data input, allowing users to understand its functionality.

## How to Run the Program

To run the program, follow these steps:

1. Examine the `Example-Excell` file to understand how to fill out the `Empty-Excell` file.

2. Fill out the `Empty-Excell` file as per the example in `Example-Excell`. Note that entering date information is optional; the program will assign default dates if none are provided. If any department is not subject to grading through any of the assessment types (e.g., no quizzes), you can leave those fields empty.

3. Convert the `Empty-Excell` file to CSV format by visiting [this link](https://cloudconvert.com/xlsx-to-csv) and download it as `myList.csv`. Ensure that this CSV file is in the same directory as the project files.

4. Run the `exam.ipynb` Jupyter Notebook by selecting "Run All Cells."

The program will calculate coefficients for each course and display the general percentage indicating the importance and priority of each department's courses.

## Additional Information

For further details on how the program operates and sample results, refer to the `Sample-Result-Example.pdf` file.

Feel free to reach out for any questions or assistance.

## Dependencies

Before running this project, make sure you have the following dependencies installed:

- [scikit-learn](https://scikit-learn.org/stable/index.html)
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [tkinter](https://docs.python.org/3/library/tkinter.html)

You can install these dependencies using the following commands:

```bash
pip install scikit-learn
pip install pandas
pip install numpy
```
## Contact
For any inquiries or questions, please feel free to contact me at kadirqokdeniz@hotmail.com.
