# Custom-Language-Development-OcamlMini

## 📚 Overview
**OcamlMini** is a lightweight, custom programming language developed using OCaml. This project serves as an educational and practical exploration into language design, compiler construction, and operational semantics. With a focus on simplicity and clarity, OcamlMini demonstrates key principles behind programming language design, including parsing, evaluation, and execution.

## 🚀 Key Features
- **Custom Syntax and Semantics:** A minimalistic language syntax designed for easy parsing and interpretation.
- **Interpreter:** Evaluate OcamlMini code efficiently with built-in error handling.
- **Parser:** Robust parsing system to validate and process the custom language's syntax.
- **Operational Semantics:** Implements formal operational semantics to ensure correctness.
- **Extensibility:** Easily extend the language to include additional features.

## 🛠️ Project Structure
- **/src:** Core source code for the OcamlMini language.
- **/test:** Comprehensive test suite to validate language features.
- **/bin:** Compiled executables for the interpreter and tools.
- **microcaml-opsem.pdf:** Detailed document on the operational semantics of the OcamlMini language.

## 📥 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Flashy990/Custom-Language-Development-OcamlMini.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Custom-Language-Development-OcamlMini
   ```
3. Build the project:
   ```bash
   make
   ```

## 📝 Usage
Run the interpreter with an OcamlMini script:
```bash
./bin/ocamlmini script.om
```
Example OcamlMini script:
```
let x = 10;
print(x + 5);
```

## 🧪 Testing
Run the test suite to ensure functionality:
```bash
make test
```

## 📖 Documentation
Refer to **microcaml-opsem.pdf** for detailed insights into the operational semantics and theoretical foundations of OcamlMini.
