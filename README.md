
# Registration Form 

This is a simple registration form application built using Python's tkinter library. It allows users to enter their details such as name, email, date of birth (DOB), gender, contact number, and select a course. The entered data can be saved locally in both text (`.txt`) and comma-separated values (CSV) formats.

## Features

- **User Interface:** GUI designed with tkinter for easy data input and interaction.
- **Data Entry:** Fields for full name, email, DOB (via date selection), gender selection (via radio buttons), contact number, and course selection (via dropdown menu).
- **Validation:** Basic validation ensures required fields are filled before submission.
- **Data Export:** Saves entered data locally in text and CSV formats for record-keeping.

## Requirements

- Python 3.x
- tkinter (included in Python standard library)
- tkcalendar (for date entry widget, install using `pip install tkcalendar`)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Vaishnavi544/Registrationform.git
   cd Registrationform
   ```

2. **Install dependencies:**

   ```bash
   pip install tkcalendar
   ```

3. **Run the application:**

   ```bash
   python register.py
   ```

## Usage

1. Enter your details in the provided fields.
2. Select your gender using radio buttons.
3. Select a course from the dropdown menu.
4. Click **Submit** to save your information locally.
5. Click **Cancel** to exit the application.

## File Structure

- `register.py`: Contains the main application code using tkinter for GUI and handles data saving.
- `regdetails.txt`: Text file to store registration details in a formatted manner.
- `Regfile.csv`: CSV file to store registration details in a comma-separated format.

## Contributing

Contributions are welcome! If you have suggestions for improvements, found bugs, or want to add new features, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
![Screenshot 2024-07-11 002247](https://github.com/Vaishnavi544/Registrationform/assets/142041825/1a89d2a2-5b8d-4518-8ddf-c7f29c9fb539)

![image](https://github.com/Vaishnavi544/Registrationform/assets/142041825/9d315ca4-e029-46ad-be2d-3c84024e7cb8)
