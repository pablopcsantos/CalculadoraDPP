# Estimated Due Date Calculator (EDD) - Naegele's Rule

*Leia isto em outros idiomas: [Português](README.md)*

---

This project is an Estimated Due Date (EDD) Calculator based on the classic Naegele's Rule. It is an educational and interactive web tool that goes beyond providing the final date: it explains the calculation step by step (days, months, and years). The application presents the +9 Rule and the -3 Rule in a didactic way to support clinical learning.

## 🚀 Features

* **EDD Calculation:** Enter the Last Menstrual Period (LMP) date and automatically obtain the estimated due date.
* **Step-by-Step Explanation:** Detailed explanation of how the mathematical calculation was performed, dividing the logical process into Days, Months, and Years.
* **+9 Rule and -3 Rule:** Dynamic presentation of which rule to apply depending on the month of the LMP (January through March or April through December).
* **Edge Cases:** Real-time handling and explanation of month changes, year changes, and natural validation of leap years.
* **Responsive Design:** Clean healthcare-oriented interface (with a subtle medical visual pattern), fully adapted to mobile devices and desktops.
* **Quick Copy:** Utility button for quickly copying the entered date to the clipboard.

## 🛠️ Technologies Used

This is a *Single File* project with no external dependencies, ensuring high portability and speed.

* **HTML5:** Semantic page structure.
* **CSS3:** Styling with variables (Custom Properties), animations, and fully native responsive design.
* **JavaScript (Vanilla):** Core date-manipulation logic, didactic conditional algorithms, and dynamic rendering of explanations in the DOM.

## ⚙️ How to Use

1. Download the `CalculadoradeNagele.html` file.
2. Open the file in any web browser (Google Chrome, Firefox, Safari, Edge, etc.). *No installation or local server is required.*
3. Select the **Last Menstrual Period (LMP)** date using the picker or enter the date manually.
4. Click **Calculate EDD** (or press *Enter*).
5. The screen will display the projected final date and the complete demonstration of the applied calculation.

## 📖 About Naegele's Rule

Naegele's Rule is the classic mathematical formula standardized in obstetric practice for calculating the Estimated Due Date:

1. **Days:** Add 7 days to the day of the last menstrual period (LMP).
2. **Months/Years:**
   - **+9 Rule:** For months from January through March, add 9 months (the year of delivery remains the same).
   - **-3 Rule:** For months from April through December, subtract 3 months and add 1 year (to account for the calendar-year transition).

## 👤 Authorship and development

Educational micro-app independently developed by [**Pablo Phillipe Cândido dos Santos**](http://lattes.cnpq.br/9500873674712528), intended to support teaching and learning of Estimated Due Date calculation using Naegele's Rule.

Generative artificial intelligence tools were used as auxiliary resources during development, while responsibility for the application's conception, implementation, integration, and verification remained with the author.
