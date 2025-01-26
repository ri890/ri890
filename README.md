- 👋 Hi, I’m @ri890
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---Obrolan Kopilot
Python script for dataset analysis with Pandas
Tulis skrip Python yang menganalisis himpunan data menggunakan Pandas.
Tentu! Berikut ini adalah contoh skrip Python yang menunjukkan cara menganalisis kumpulan data menggunakan pustaka Pandas. Untuk contoh ini, saya akan menggunakan kumpulan data CSV sederhana yang berisi informasi tentang karyawan, seperti ID, nama, departemen, dan gaji.

Pastikan Anda telah menginstal pustaka Pandas. Anda dapat menginstalnya menggunakan:

dia
pip install pandas
Berikut skripnya:

Ular piton
import pandas as pd

# Load the dataset
df = pd.read_csv('employees.csv')

# Display the first few rows of the dataset
print("First few rows of the dataset:")
print(df.head())

# Display basic statistics about the dataset
print("\nBasic statistics about the dataset:")
print(df.describe())

# Calculate the average salary
average_salary = df['Salary'].mean()
print(f"\nAverage salary: {average_salary}")

# Find the number of employees in each department
department_counts = df['Department'].value_counts()
print("\nNumber of employees in each department:")
print(department_counts)

# Find the employee with the highest salary
highest_salary_employee = df.loc[df['Salary'].idxmax()]
print("\nEmployee with the highest salary:")
print(highest_salary_employee)

# Group by department and calculate the average salary for each department
average_salary_by_department = df.groupby('Department')['Salary'].mean()
print("\nAverage salary by department:")
print(average_salary_by_department)

# Save the summary statistics to a new CSV file
summary_statistics = df.describe()
summary_statistics.to_csv('summary_statistics.csv')
print("\nSummary statistics saved to 'summary_statistics.csv'")

# Save the average salary by department to a new CSV file
average_salary_by_department.to_csv('average_salary_by_department.csv')
print("Average salary by department saved to 'average_sa
ri890/ri890 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
