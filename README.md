# Currency Converter (Java Console Application)

A lightweight, console-based Java application designed to handle currency initializations, store exchange matrices natively using HashMaps, and execute accurate currency conversions rounded to two decimal places.

---

## 🛠️ Features
* **Dynamic Data Storage:** Uses custom object mapping paired with `HashMap<String, Double>` collections to map real-time conversion rates across 6 global baseline currencies (USD, EUR, GBP, CHF, CNY, JPY).
* **Precision Arithmetic:** Embedded rounding engines guarantee that output conversions adhere strictly to the traditional $0.00$ decimal precision format.
* **Decoupled Architecture:** Separates the core object blueprint logic (`Currency.java`) from the executable process driver (`TestRunner.java`).

---

## 📂 File Architecture

Ensure your directory contains the following file composition layout inside your working environment directory (`C:\24afcse125\`):

```text
C:\24afcse125\
│
├── Currency.java      # The structural class holding currency profiles, getters/setters, and exchange matrices.
├── TestRunner.java    # The executable process containing the 'main' function to process conversions.
└── README.md          # Project documentation.

SAMPLE OUTCOME:
--- Currency Conversion Output ---
100.0 USD is equal to 93.0 EUR.
