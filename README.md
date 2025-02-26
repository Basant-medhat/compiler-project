# 🖥️ Compiler Project - Six Phases of Compilation  
🚀 A Python-based **compiler** that implements all six phases of compilation: **Lexical Analysis, Syntax Analysis, Semantic Analysis, Intermediate Code Generation, Optimization, and Code Generation**.  

## 📌 Project Overview  
This project simulates the **compilation process**, transforming high-level code into machine-readable instructions while ensuring **syntax correctness, semantic validation, and optimized execution**.  

## 🛠 Tech Stack & Tools  
- **Programming Language:** Python  
- **Parsing Techniques:** Recursive Descent, LL(1) Parsing  
- **Compiler Phases:** Tokenization, Parsing, Semantic Checking, Code Optimization ,Code Generation 
- **Tools Used:** NLTK (for Lexical Analysis), GUI   

## 📌 Compiler Phases & Workflow  

### 🔹 1. **Lexical Analysis (Scanner)**
✅ Reads input source code and converts it into tokens.  
✅ Removes unnecessary whitespaces, comments, and identifies **keywords, identifiers, operators, and literals**.  

### 🔹2. **Syntax Analysis**
It takes tokens as input and generates a parse tree as output, the parser checks that the expression made by the tokens is syntactically correct or not.

### 🔹3. **Semantic Analysis**
 It checks whether the parse tree follows the rules of language, keeps track of identifiers, their types and expressions. 

### 🔹4. **Intermediate Code Generation**  
It generates the source code into the intermediate code. 
It is between the high-level language and the machine language. should be generated in easily way to translate it into the target machine code.

### 🔹5. **Code Optimization**
 improve the intermediate code so output could run faster and take less space. 
 It removes the unnecessary lines and arranges the sequence of statements in order to speed up the program execution

### 🔹6. **Code Generator**
 It takes the optimized intermediate code as input and maps it to the target machine language. Produces target machine code assembly-like output.
