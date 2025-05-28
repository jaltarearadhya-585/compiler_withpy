# 🧠 Mini Compiler for a Custom Language (Python)

This project is a **Mini Compiler** built using Python. It includes all the essential stages of compilation like lexical analysis, syntax analysis, semantic analysis, intermediate code generation, and more.

---

## 📁 Project Structure



markdown
Copy
Edit

---

## 💡 Features

- **Custom Language Support**  
  Designed for a simplified custom programming language.

- **Lexical Analysis**  
  Tokenizes the input source code using `lexer.py`.

- **Syntax Analysis (Parsing)**  
  Checks code structure using grammar rules defined in `parser.py`.

- **Semantic Analysis**  
  Ensures correctness of variable declarations, types, etc. using `semantic.py`.

- **Intermediate Code Generation**  
  Converts valid source code into intermediate representation (`icg.py`).

- **Test Suites**  
  Individual test scripts provided for each phase of the compiler.

- **GUI**  
  User interface for compiling and testing programs (`mini_compiler_gui.py`).

---

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/mini-compiler.git
   cd mini-compiler
Install Requirements (if any)

bash
Copy
Edit
pip install ply  # if you're using PLY
Run the GUI

bash
Copy
Edit
python mini_compiler_gui.py
Run Individual Tests

bash
Copy
Edit
python test_lexer.py
python test_parser.py
python test_semantic.py
python test_icg.py
🧪 Sample Input
plaintext
Copy
Edit
int a = 10;
int b = 20;
int c = a + b;
✅ Output
Tokens from lexer

Parse tree from parser

Semantic correctness

Intermediate representation (3AC or similar)

👥 Contributors
Name	  
Aradhya Jaltare	
Dhruv Gahtori	
Kamal Joshi	
Deepesh Singh Kharkwal	

📄 License
This project is for educational purposes and follows the open academic license.

yaml
Copy
Edit

---

