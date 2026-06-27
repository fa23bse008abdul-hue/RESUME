# 🚚 Transport Invoice Management System

A professional **Transport Invoice Management System** built using **HTML, CSS, and JavaScript** for **Muhammed Mohsin United Business Co S.P.C**.

The application allows users to create transport invoices, calculate VAT automatically, export invoices as **PDF** and **Excel**, print invoices, save them locally in the browser, and reload previously saved invoices.

---

## 📸 Preview

> Add your screenshots inside the **images/** folder.

### Main Invoice

```text
images/screenshot-home.png
```

### Saved Invoice Drawer

```text
images/screenshot-drawer.png
```

### PDF Export

```text
images/screenshot-pdf.png
```

---

# ✨ Features

## Invoice Management

* Create transport invoices
* Auto invoice numbering
* Next Invoice button
* Edit existing invoices
* Delete saved invoices
* Save invoices locally using Local Storage
* Load previously saved invoices

---

## Customer Information

* Customer Company Name
* Customer Address
* Customer VAT Number

---

## Transport Information

* Invoice Number
* Invoice Date

---

## Dynamic Charges Table

Each row contains:

* Date
* Vehicle Number
* Description
* Container / BL Number
* VAT %
* Quantity
* Rate
* Amount

Features include:

* Unlimited rows
* Add new row
* Delete row
* Automatic amount calculation

---

## Automatic Calculations

The application automatically calculates:

* Row Total
* Subtotal
* VAT
* Grand Total
* Received Amount
* Balance Due
* Amount in Words

Currency:

* Omani Rial (OMR)
* Three decimal precision

---

## Amount in Words

Converts invoice totals into professional wording.

Example:

```text
One Thousand Five Hundred Twenty Three Rials Omani and Two Hundred Fifty Baiza Only
```

---

## Export Features

### Print Invoice

Creates an A4 printable invoice.

---

### Export PDF

Uses:

* html2pdf.js

Features

* High-quality PDF
* A4 Portrait
* Proper margins
* Printable layout

---

### Export Excel

Uses:

* SheetJS (xlsx)

Exports:

* Customer Details
* Invoice Details
* Charges Table
* Total Amount
* Amount in Words

---

## Local Storage

Invoices are saved inside the browser using

```javascript
localStorage
```

Saved information includes

* Invoice Number
* Date
* Customer Details
* Charges
* Total
* Amount in Words
* Save Timestamp

---

# 🖥 Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* html2pdf.js
* SheetJS (xlsx)

---

# 📁 Project Structure

```text
Transport-Invoice/

│
├── index.html
├── style.css
├── script.js
│
├── images/
│   ├── logo.jpeg
│   ├── screenshot-home.png
│   ├── screenshot-drawer.png
│   ├── screenshot-pdf.png
│   └── banner.png
│
└── README.md
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/transport-invoice.git
```

Open

```text
index.html
```

No installation required.

No server required.

Runs directly in any modern web browser.

---

# 🛠 Browser Support

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Opera
* Brave

---

# 📄 Invoice Workflow

```
Create Invoice

↓

Add Charges

↓

Automatic Calculations

↓

Save Invoice

↓

Load Previous Invoice

↓

Print

↓

Export PDF

↓

Export Excel
```

---

# ⚙ JavaScript Modules

The application is organized into multiple sections.

## Local Storage

* loadSavedInvoices()
* persistInvoices()

---

## Invoice Generator

* makeSampleInvoice()
* makeBlankInvoice()

---

## Rendering

* renderInvoiceMeta()
* renderChargesTable()

---

## Calculations

* computeRowAmount()
* recalcSummary()
* getTotal()
* getSubTotalWithoutVatt()

---

## Number Formatting

* formatMoney()
* amountToWordsOMR()
* numberToWords()

---

## Invoice Operations

* saveInvoice()
* nextInvoice()
* collectCurrentInvoiceData()
* loadInvoice()

---

## Drawer Operations

* openDrawer()
* closeDrawer()
* renderDrawerList()

---

## Export

* printInvoice()
* exportPdf()
* exportExcel()

---

# 🎨 User Interface

Modern interface including

* Sticky Toolbar
* Responsive Layout
* Professional Invoice Design
* Printable A4 Layout
* Rounded Cards
* Company Branding
* Dynamic Table
* Invoice Summary Boxes
* Saved Invoice Drawer

---

# 📱 Responsive Design

Optimized for

* Desktop
* Laptop
* Tablet

---

# 🔮 Future Improvements

* Customer Database
* Driver Management
* Vehicle Database
* Login System
* Cloud Storage
* Multi-user Support
* Email Invoice
* QR Code Generation
* Barcode Support
* Multiple Currency Support
* Dark Mode
* Invoice Search
* Monthly Reports
* Dashboard
* Analytics
* Company Settings

---

# 📦 Libraries Used

## html2pdf.js

Used for

* PDF generation
* Printable invoices

---

## SheetJS

Used for

* Excel Export
* XLSX File Generation

---

# 👨‍💻 Author

**Muhammed Mohsin United Business Co S.P.C**

Transport Invoice Management System

---

# 📃 License

This project is intended for educational and business use.

You may modify and customize it according to your organization's requirements.

---

# ⭐ Highlights

* Pure HTML, CSS, JavaScript
* No Frameworks
* Professional Invoice Layout
* Local Storage Support
* PDF Export
* Excel Export
* Auto VAT Calculation
* Amount in Words
* A4 Print Ready
* Responsive Design
* Easy to Customize
