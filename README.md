# 📦 Barcode Scanner with SQLite Validation

This Python project uses your webcam to scan barcodes using `OpenCV` and `pyzbar`, and checks if the scanned barcode exists in a local SQLite database.

---

## 🚀 Features
- Real-time barcode scanning via webcam.
- Validates scanned barcodes against a pre-populated SQLite database.
- Adds new barcodes to the database with uniqueness enforcement.
- Simple CLI feedback for valid/invalid scans.

---

## 🧰 Requirements

- Python 3.6+
- [ZBar](https://github.com/mchehab/zbar) (required by `pyzbar`)
- `pyzbar`
- `opencv-python`
- `sqlite3` (built-in)

---

## 📥 Installation

### 1. Clone the Repo
```bash
git clone https://github.com/your-username/barcode-scanner-sqlite.git
cd barcode-scanner-sqlite
