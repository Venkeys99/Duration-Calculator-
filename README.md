# Duration-Calculator-
# Age Duration Calculator

## Project Objective
The objective of this project is to calculate the duration of how long a person has lived based on their age in different time units such as months, weeks, days, hours, minutes, and seconds.

## Features
- Input: Age of a person in years.
- Input: Desired time unit for the duration calculation (months, weeks, days, hours, minutes, seconds).
- Output: Duration in the specified time unit.



## How to Run the Project
1. Clone the repository or download the project files.
2. Open a terminal and navigate to the project directory.
3. Run the Python script:
   ```bash
   python age_duration_calculator.py
   ```
4. Enter the age of the person in years when prompted.
5. Enter the desired time unit (months, weeks, days, hours, minutes, seconds) when prompted.
6. The script will output the duration the person has lived in the specified time unit.

## Example
```bash
$ python age_duration_calculator.py
Enter the age of the person in years: 25
Enter the time unit (months, weeks, days, hours, minutes, seconds): days
The person has lived for 9131.25 days.
```

## Code Explanation
- The `calculate_duration` function takes two parameters: `age_years` and `unit`.
  - `age_years`: The age of the person in years.
  - `unit`: The time unit for which the duration should be calculated. Supported units are 'months', 'weeks', 'days', 'hours', 'minutes', 'seconds'.
- The function uses a dictionary `units_per_year` to store the number of each unit in one year.
- It checks if the provided `unit` is valid. If not, it raises a `ValueError`.
- It calculates the duration by multiplying the age in years by the number of units per year for the specified unit.
- The `if __name__ == "__main__":` block handles user input and prints the calculated duration.
