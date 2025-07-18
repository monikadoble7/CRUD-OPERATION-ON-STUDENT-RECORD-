# 📚 School Student Manager

A simple command-line interface (CLI) tool in Python for managing a MySQL database of student records.
Supports **Create**, **Read**, **Update**, and **Delete** operations interactively.

---

## 🧭 Table of Contents

* [Motivation](#motivation)
* [Features](#features)
* [Prerequisites](#prerequisites)
* [Installation](#installation)
* [Usage](#usage)
* [Project Structure](#project-structure)
* [Error Handling & Logging](#error-handling--logging)
* [Contributing](#contributing)
* [License](#license)

---

## Motivation

Built to simplify student record management—ideal for learning database CRUD operations in a clean, interactive Python CLI.&#x20;

---

## Features

* Add new student records
* View all student entries
* Update a student’s grade
* Remove student records
* Menu-driven user experience

---

## Prerequisites

* Python 3.7+
* MySQL Server installed
* Credentials for MySQL root account

---

## Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/yourusername/school-manager.git
   cd school-manager
   ```
2. Install dependencies:

   ```bash
   pip install mysql-connector-python
   ```
3. Create the database/table in MySQL:

   ```sql
   CREATE DATABASE school;
   USE school;
   CREATE TABLE students (
     id INT AUTO_INCREMENT PRIMARY KEY,
     name VARCHAR(100),
     age INT,
     grade VARCHAR(10)
   );
   ```

---

## Usage

Run the main script:

```bash
python main.py
```

Then follow the menu prompts to **Insert**, **Display**, **Update**, or **Delete** student records.&#x20;

**Example:**

```
----- Student Records -----
1. Insert Student
2. Display All Students
3. Update Student Grade
4. Delete Student
5. Exit
Enter your choice (1‑5): 
```

---

## Project Structure

```
.
├── main.py         # CLI & menu dispatcher
├── db.py           # DB helper functions (connect, insert, update, delete)
└── requirements.txt
```

---

## Error Handling & Logging

* Uses context managers with rollback on failure (recommended for future improvements)
* Currently prints success/failure messages; consider logging to a file

---

## Contributing

Contributions are welcome! Please follow the steps:

1. Fork the repository
2. Create a branch: `git checkout -b feature/YourFeature`
3. Commit your changes
4. Submit a Pull Request

---

## License

This project is available under the **MIT License**. See `LICENSE` for details.

---

### 📷 (Optional)

Include a screenshot or brief console output demo. Visuals help users get started faster.&#x20;

---

## Final Tips

* Keep this README **brief, clear, and self-contained**&#x20;
* Update install and usage steps whenever code changes&#x20;
* Consider adding badges (build status, PyPI version) for visibility&#x20;

---
Name: Monika Doble
Phone:9890884532
Email:monikdoble7@gmail.com
