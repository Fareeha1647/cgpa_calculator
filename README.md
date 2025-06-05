# 🎓 CGPA Calculator in C++

This is a simple command-line program written in **C++** to calculate the **Cumulative Grade Point Average (CGPA)** for a student based on credit hours and grade points.

---

## ✨ Features

- Accepts number of subjects from the user
- Inputs credit hours and grade points for each subject
- Calculates the weighted average (CGPA)
- Displays the result rounded to two decimal places
- Basic error handling (e.g., zero credit hours)

---

## 🧮 Formula Used

\[
\text{CGPA} = \frac{\sum (\text{credit hours} \times \text{grade points})}{\sum \text{credit hours}}
\]

---

## 🛠️ Technologies Used

- Language: **C++**
- Libraries: `iostream`, `iomanip`

---

## 🧑‍💻 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Fareeha1647/cgpa_calculator.git
   cd cgpa_calculator
2. **compiled the code
g++ main.cpp -o cgpa_calculator
3. **Run the executable
./cgpa_calculator    # On Linux/Mac
cgpa_calculator.exe  # On Windows
📷 Example Output
Enter number of subjects
3
SUBJECT 1
Enter the credit_hours:
3
Enter grade_point:
3.5
SUBJECT 2
Enter the credit_hours:
4
Enter grade_point:
3.0
SUBJECT 3
Enter the credit_hours:
2
Enter grade_point:
4.0
Your CGPA is: 3.33
📄 License
This project is open-source and free to use under the MIT License.
