# 🔧 JSON Refiner – Advanced Edition
### 🚀 Professional JSON Processing Platform (Python + Gradio)

---

## 📌 Overview

**JSON Refiner – Advanced Edition** is a powerful and professional JSON processing platform built using **Python** and **Gradio 4.0+**.

It provides advanced tools for transforming, validating, merging, and analyzing JSON data through a clean and interactive web interface.

This platform is ideal for:
- Developers
- Data Engineers
- API Testers
- Students working with structured data

---

## ✨ Core Features

### 1️⃣ Core Refining
- Convert key-value pairs into structured JSON
- Automatic data type inference (`int`, `float`, `bool`, `null`)
- Case style conversion
- Remove null values
- Flatten nested JSON
- JSON statistics display

---

### 2️⃣ JSON Validation
- JSON Schema validation (Draft 7 support)
- Required field checking
- Detailed validation error reporting
- Clean validation report output

---

### 3️⃣ Case Conversion
Supports multiple naming conventions:

- `snake_case`
- `camelCase`
- `kebab-case`
- `PascalCase`

Easily transform JSON keys between different coding standards.

---

### 4️⃣ Deep Merge JSON
- Merge multiple JSON objects
- Recursive deep merging
- Intelligent conflict resolution
- Supports 2 or 3 JSON inputs

---

### 5️⃣ Flatten / Unflatten
Convert between nested and flat JSON structures.

**Nested Example:**
```json
{
  "user": {
    "name": "John",
    "address": {
      "city": "NYC"
    }
  }
}
```

**Flattened Output:**
```json
{
  "user.name": "John",
  "user.address.city": "NYC"
}
```

---

### 6️⃣ History Tracking
- Complete transformation history
- Timestamp logging
- Operation status tracking
- Downloadable history reports
- Clear history option

---

## 💡 Example Inputs

### Key-Value Input
```
name: John Doe
age: 30
is_active: true
address: {"city": "New York", "zip": "10001"}
```

---

### JSON Input
```json
{
  "user_name": "John Doe",
  "user_age": 30,
  "user_address": {
    "city_name": "New York",
    "zip_code": "10001"
  }
}
```

---

## 🛠️ Installation Guide

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/json-refiner-advanced-edition.git
cd json-refiner-advanced-edition
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Application
```bash
python app.py
```

---

## 📦 Requirements

- Python 3.9+
- Gradio 4.0+
- jsonschema
- typing
- datetime

---

## ⚠️ Troubleshooting

### ❌ Invalid JSON
- Ensure proper formatting
- Use double quotes
- Avoid trailing commas
- Close all brackets properly

### ❌ Schema Validation Issues
- Confirm schema follows Draft 7
- Check required fields
- Verify correct property types

### ⏳ Large File Processing
Large JSON files may take a few seconds depending on system performance.

---

## 🚀 Usage Tips

- Use **Core Refining** for quick data transformations
- Validate JSON before API submission
- Check statistics to understand structure depth
- Review History tab to track all changes
- Download reports for documentation or submission

---

## 🖥️ Built With

- Python
- Gradio 4.0+
- JSON Schema Draft 7

---

## 📄 License

This project is open-source and available for educational and professional use.

---

## 🛠️ JSON Refiner – Advanced Edition
Built with ❤️ using Python and Gradio
