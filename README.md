# 📄 Invoice Extraction Automation — UiPath RPA Challenge

## 📌 Overview

This project automates the **Automation Challenge — Invoice Processing** using UiPath.

The workflow reads invoice entries from a dynamic web table, downloads corresponding invoice files, extracts required data fields, applies filtering logic based on due dates, and generates a structured CSV output file.

The solution demonstrates advanced RPA concepts including file handling, data extraction, conditional filtering, and dynamic web automation.

---

## 🚀 Features

* Automated interaction with dynamic web tables
* Invoice file downloading
* Structured data extraction from invoices:

  * Invoice Number
  * Invoice Date
  * Company Name
  * Total Due
* Date-based filtering logic:

  * Processes only invoices where Due Date ≤ current date
* CSV file generation
* End-to-end unattended automation workflow

---

## 🛠️ Technologies Used

* UiPath Studio
* UI Automation Activities
* File & Folder Automation
* DataTables
* PDF/Text Extraction
* CSV Handling

---

## 📂 Project Structure

```
/Main.xaml              -> Main automation workflow
/Data                   -> Input and output files
/Invoices               -> Downloaded invoice files
/Output/output.csv      -> Generated CSV result
/README.md              -> Project documentation
```

---

## ⚙️ Workflow Logic

1. Open Automation Challenge webpage.
2. Extract rows from invoice table.
3. Loop through each row:

   * Download invoice file.
   * Extract required data fields.
   * Check Due Date condition.
4. Store valid records in a DataTable.
5. Generate CSV file matching required format.
6. Upload CSV to complete challenge.

---

## ▶️ How to Run

1. Open project in UiPath Studio.
2. Enable browser extension if required.
3. Verify download folder paths.
4. Run `Main.xaml`.

---

## 🧠 Challenges Solved

* Handling paginated dynamic tables.
* Reliable selectors for download buttons.
* Automating file downloads and tracking completion.
* Extracting structured data from invoice documents.
* Applying date-based business rules.

---

## 👨‍💻 Author

Mohamed Sameh
Computer Science Student | RPA & Automation Enthusiast

---

## ⭐ Notes

This project was built for learning and portfolio purposes to demonstrate real-world RPA automation skills.
