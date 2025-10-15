# Age Calculator GUI

A simple and interactive **Age Calculator** desktop application built using **Python** and **Tkinter**. This application calculates a person's age based on their date of birth and displays the result in a user-friendly GUI.

---

## **Features**

- User-friendly GUI with **Tkinter**
- Input fields for **Name, Year, Month, and Day**
- **Validation checks** for:
  - Name (only alphabets allowed)
  - Year (cannot be in the future)
  - Month (1–12)
  - Day (1–31)
- Calculates **age accurately**, accounting for month and day
- Displays errors or invalid inputs clearly
- Simple **one-click calculation** with a "Calculate age" button

---

## **Screenshots**

![Screenshot of Age Calculator GUI](screenshot.png)

---

## **Installation**

1. Make sure you have **Python 3.x** installed.
2. Clone this repository:

```bash
git clone https://github.com/hackerbytez/Age_GUI_Calculator.git
cd age-calculator-gui
````

3. Run the application:

```bash
python age_calculator.py
```

---

## **Usage**

1. Enter your **Name**.
2. Enter your **Birth Year, Month, and Day**.
3. Click on **"Calculate age"**.
4. Your age will be displayed below the button. Invalid inputs will show clear error messages.

---

## **Dependencies**

* Python 3.x
* Tkinter (usually comes pre-installed with Python)

---

## **How It Works**

1. The program opens a Tkinter GUI window.
2. Users input their **name and birth date**.
3. The program validates the inputs:

   * Name must contain only letters.
   * Year cannot be in the future.
   * Month must be between 1–12.
   * Day must be between 1–31.
4. If valid, the program calculates age based on the current date and displays it.
5. If invalid, it shows **user-friendly error messages**.

---

## **Project Structure**

```
age-calculator-gui/
│
├── age_calculator.py       # Main Python script
├── README.md               # Project documentation
└── screenshot.png          # Optional screenshot of the GUI
```

---
 

## **Author**

**Uday Raut**

```
