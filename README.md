# Survival Duration Calculator

## Overview

The Survival Duration Calculator is a Python program that calculates the duration a person has
lived based on their age in various time units including Months, Weeks, Days, Hours, Minutes, and
Seconds. This project reads the user's age from a file, prompts the user to select a time unit,
performs the calculation, and writes the result to a file.

## Features

- Reads age input from a file.
- Supports calculation of duration in the following units:
  - Months
  - Weeks
  - Days
  - Hours
  - Minutes
  - Seconds
- Handles invalid inputs gracefully.
- Outputs the result to a file.

## Usage

**Create an `age.txt` file**:
    - Add your age in the `age.txt` file. For example:
      ```txt
      25
      ```

**Run the program**:
    ```bash
    python survival_duration_calculator.py
    ```

**Follow the prompts**:
    - The program will ask you to choose a time unit. You can write the first letter or the full name of the time unit (e.g., `Months`, `m`, `Weeks`, `w`, etc.).

**Check the result**:
    - The calculated duration will be printed on the screen and written to the `duration.txt` file.

## Example

1. **age.txt**:
    ```txt
    30
    ```

2. **Running the program**:
    ```bash
    python survival_duration_calculator.py
    ```

3. **User input**:
    ```
    Please choose time unit: Months, Weeks, Days, Hours, Minutes, Seconds.
    Note: You can write the first letter or the full name of the time unit.
    m
    ```

4. **Output**:
    - Console: `You lived for 360 Months`
    - `duration.txt`: `You lived for 360 Months`

## Requirements

- Python 3.x


