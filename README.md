# Software-Engineering-Final-Project-3.1BSIT
It contains the document and figma for the Final Project in Software Engineering
# Software Engineering Final Project — 3.1 BSIT

Welcome to the official repository for our **Software Engineering Final Project**. This project features **StockWise**, a web-based inventory management system, along with its UI/UX Figma design assets.

---

## 📌 Repository Contents

| File / Folder | Description |
| :--- | :--- |
| **`stockwise (1).zip`** | Full source code archive for the StockWise Flask application. |
| **`Untitled.fig`** | Figma design file containing wireframes and interactive prototypes. |
| **`README.md`** | Overview, architecture details, and setup instructions. |

---

## 🚀 About StockWise

**StockWise** is an inventory management application built using Python and Flask. It provides businesses with tools to track stock levels, manage item inventories, log movement transactions, and generate analytical reports.

### Key Features
* **Authentication**: User registration and secure login.
* **Dashboard Overview**: Summary of stock health, metrics, and low-stock alerts.
* **Item Management**: CRUD operations for inventory items (SKU, pricing, stock levels, categories).
* **Stock Movements**: Record and view history for stock-ins, stock-outs, and adjustments.
* **Reporting**: Export and analyze inventory summaries.

---

## 🛠 Tech Stack

* **Backend Framework**: Python (Flask)
* **Database**: SQLite / Relational DB
* **Frontend**: HTML5, CSS3, Jinja2 Templates
* **Design & Prototyping**: Figma (`Untitled.fig`)
* **Testing**: Pytest

---

## 💻 How to Setup and Run StockWise

1. **Extract the source code:**
   Unzip `stockwise (1).zip` to access the application directory.

2. **Navigate into the project directory:**
   ```bash
   cd stockwise

# Create virtual environment
python -m venv venv

# Activate on Windows:
venv\Scripts\activate

# Activate on macOS/Linux:
source venv/bin/activate

