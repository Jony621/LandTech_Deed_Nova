# JomiSafe — Land Risk & Deed Assistance

**A bilingual prototype for land-risk screening, inheritance estimation, and property registration cost calculation in Bangladesh.**

JomiSafe is a lightweight web application designed to help people understand some of the key considerations involved in land transactions. It brings three useful tools into one interface: a land-risk checklist, an inheritance calculator, and a deed registration cost estimator.

The application supports **Bangla and English**, making its interface more accessible to users who prefer either language.

> **Important:** JomiSafe is a demonstration prototype. Its sample land records are not verified against official government databases, and its inheritance calculations and registration rates are illustrative. It must not be used as a substitute for legal advice or official land-record verification.

## ✨ Features

### 1. Land Risk Screening
- Check sample land records using the information available in the demonstration dataset.
- Display potential risk indicators and a risk score.
- Help users identify issues that may need further investigation before a transaction.
- Clearly distinguish demo-record results from verified government information.

### 2. Inheritance Calculator
- Estimate land distribution using a simplified set of supported heir categories.
- Accept land-area information and the heirs included in the calculation.
- Display an illustrative distribution to help users understand the concept of inheritance shares.
- Include safeguards and warnings about omitted heirs and other factors that can affect actual distribution.

**Scope limitation:** The calculator does not cover every possible heir or legal circumstance. Debts, funeral expenses, valid bequests, applicable personal law, and other relevant facts may affect the result. Its output is not a legal determination.

### 3. Deed Registration Cost Estimator
- Estimate potential deed registration costs from a property value and configured rates.
- Display a breakdown of estimated charges and the total.
- Validate inputs to reject malformed values, negative amounts, and invalid rates.
- Support Bangla and English number input where implemented.

The rates are configurable demonstration values. Actual charges may depend on the property location, transaction type, applicable rules, and current government schedules.

### 4. Bangla and English Interface
- Switch between Bangla and English.
- Translate interface labels, tabs, messages, warnings, and generated results.
- Retain the selected language while navigating between the application's tools.

## 🛠️ Technology

JomiSafe is built as a lightweight web prototype using:

- **HTML** — application structure
- **CSS** — layout and styling
- **JavaScript** — interactive tools, calculations, input validation, and language switching

The application is designed to run in a modern web browser. It does not require a frontend framework or a build step.

## 🚀 Getting Started

### Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/Jony621/LandTech_Deed_Nova.git
   ```

2. Open the project folder:

   ```bash
   cd LandTech_Deed_Nova
   ```

3. Open `JomiSafe_fixed.html` in a modern web browser.

If you rename the main HTML file to `index.html`, you can open it directly or serve the folder using a simple local HTTP server.

### Run with a local server (optional)

If Python is installed, run:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

Make sure the main HTML file is named `index.html` if you want the server root to open the application automatically. Otherwise, navigate to the HTML filename.

## 📂 Project Structure

A minimal deployment can use the following structure:

```text
LandTech_Deed_Nova/
├── index.html          # Main JomiSafe application
└── README.md           # Project documentation
```

If your repository uses a different HTML filename or separates CSS and JavaScript into additional files, update this structure to match the actual repository.

## 🧪 Demonstration and Testing

The prototype has been exercised through representative browser interactions, including:

- Switching between Bangla and English
- Navigating between the three tools
- Looking up records in the sample dataset
- Entering invalid registration-cost values
- Changing inheritance inputs
- Checking generated results and warning messages

These checks do not constitute exhaustive testing, legal validation, or verification against official land databases.

## 🔒 Data, Accuracy, and Limitations

- **Sample data only:** Land-risk results use the application's demonstration records.
- **No official verification:** A record not found in the sample dataset does not mean the property is free of disputes, mortgages, ownership problems, or other encumbrances.
- **Illustrative inheritance:** The calculator supports a simplified set of heirs and does not cover every legal scenario.
- **Estimated costs:** Configured rates may not reflect current official charges.
- **No legal guarantee:** Users should consult the relevant land office and qualified legal professionals before making property decisions.

## 🗺️ Future Improvements

Potential next steps include:

- Integrating authorized, official land-record verification services where available.
- Adding clearer sources and effective dates for registration rates.
- Expanding inheritance calculations with legal review and more comprehensive heir scenarios.
- Adding automated unit and browser regression tests.
- Supporting downloadable reports and checklists.
- Improving accessibility, mobile usability, and data privacy.
- Adding secure storage for user-created checklists, with appropriate consent and safeguards.

## 🎯 Project Goal

JomiSafe aims to make common land-transaction questions easier to understand through a single, accessible interface. By combining risk awareness, inheritance estimation, and cost planning, the prototype demonstrates how digital tools can help users prepare better questions and take more informed next steps.

## ⚖️ Disclaimer

JomiSafe is provided for educational and demonstration purposes only. It is not an official government service and does not provide legal, financial, or property-title certification. Always verify property information through appropriate official channels and seek qualified professional advice before completing a land transaction.

## 📄 License

No license has been specified yet. 
