Invoice Categorization Automation (UiPath)
📌 Project Overview

This UiPath automation streamlines invoice tracking and management by automatically categorizing invoices based on their due date and amount.

The bot processes a folder of text-based PDF invoices, extracts key details, and classifies each invoice as:

Overdue – Past the due date.

Due Soon – Approaching the due date.

Paid – Already settled.

A structured Excel report is then generated for easy record-keeping and follow-up.

⚙️ Features

📂 Bulk processing of invoice PDFs.

🔎 Automated extraction of:

Invoice Number

Due Date

Amount

📊 Smart classification into Overdue, Due Soon, or Paid.

📑 Export of results into an Excel file.

💡 Easily extendable for notifications or system integration.

🛠️ Tech Stack

UiPath Studio – RPA workflow development

Regex / Document Processing – Text extraction from PDFs

Excel Activities – Structured reporting

VB.NET / C# Invoke Code – Logic for date and amount handling

📂 Project Structure
📦 InvoiceCategorizationAutomation
 ┣ 📂 Data
 ┃ ┗ Invoices (sample PDFs)
 ┣ 📂 Outputs
 ┃ ┗ Invoice_Report.xlsx
 ┣ 📂 Workflows
 ┃ ┣ Main.xaml
 ┃ ┣ ExtractInvoice.xaml
 ┃ ┣ CategorizeInvoice.xaml
 ┃ ┗ ExportToExcel.xaml
 ┣ README.md
 ┗ InvoiceCategorization.sln

🚀 How to Run

Clone or download this repository.

Open the solution in UiPath Studio.

Update the invoice input folder path in the Data\Invoices directory.

Run the Main.xaml workflow.

View the generated Invoice_Report.xlsx file inside the Outputs folder.

📊 Sample Output (Excel)
Invoice No.	Due Date	Amount	Status
INV001	2025-08-10	5000	Overdue
INV002	2025-08-25	3200	Due Soon
INV003	2025-07-30	1500	Paid
🔮 Future Improvements

📧 Add automated email reminders for overdue invoices.

🔗 Integrate with databases / ERP systems.

🧠 Use AI Document Understanding for scanned invoices.

📊 Build a dashboard for real-time invoice tracking.

👨‍💻 Author

Apoorva Deep

B.Tech CSE (AI & ML), KIIT

Passionate about RPA, AI, and Automation

LinkedIn
 | GitHub
