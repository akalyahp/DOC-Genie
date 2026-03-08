DOC-GENIE

Professional Python Function Docstring Generator using AST Analysis

📌 Project Overview

DOC-GENIE is a Python-based tool that automatically generates professional docstrings for Python functions. Writing documentation manually can be time-consuming and developers sometimes forget to include proper explanations for their functions. This project solves that problem by automatically analyzing Python code and generating structured documentation.

DOC-GENIE uses Python's Abstract Syntax Tree (AST) to understand the internal structure of a function and generate clear and meaningful documentation. This helps developers improve code readability and maintainability.

---

🎯 Objectives

- To automatically generate docstrings for Python functions.
- To reduce the time required for manual documentation.
- To improve code readability and maintain proper documentation standards.
- To support popular documentation formats such as Google style and NumPy style.

---

⚙️ Features

- Automatic Python function analysis.
- Generates professional docstrings instantly.
- Supports Google style and NumPy style documentation formats.
- Simple and interactive user interface.
- Option to export generated documentation as TXT or PDF.

---

🧠 System Working

The system works by analyzing Python functions using AST (Abstract Syntax Tree). AST helps the program understand the structure of the code such as function name, parameters, loops, conditions, and return statements.

After analyzing the function, the system generates a well-structured docstring that describes the purpose of the function, its parameters, and return values.

---

🧩 Modules

1. Code Analysis Engine

This module reads the Python code and analyzes its structure using AST. It extracts important elements such as function name, parameters, loops, and conditions.

2. Docstring Generator

This module generates documentation automatically based on the information extracted from the code.

3. User Interface

The interface is built using Gradio. Users can paste Python code or upload a Python file and generate docstrings easily.

4. Export Module

This module allows users to download the generated documentation as TXT or PDF files.

---

🛠️ Technologies Used

- Python
- AST (Abstract Syntax Tree)
- Gradio
- ReportLab

---

💡 Applications

- Helps developers document legacy code.
- Useful for API documentation.
- Improves code readability.
- Helps students learn proper coding documentation practices.

---

🏁 Conclusion

DOC-GENIE simplifies the process of writing Python documentation by automatically generating professional docstrings. This saves developer time and ensures consistent and clear documentation for Python projects.
Recording link:
https://drive.google.com/file/d/1ZdT4vn4t6vZEaJzO88nuS6mjCQmlYQaj/view?usp=drive_link
