🚀 EvenLang Mini Compiler
EvenLang is a lightweight C++ simulation of a multi-phase compiler. It demonstrates the journey of a simple input through the standard stages of compilation to perform a basic parity check (Even vs. Odd).

🛠 Compiler Phases Simulated
Lexical Analysis: Scans characters to ensure they belong to the allowed alphabet (0-9, -).

Syntax Analysis: Checks if the sequence follows grammatical rules (e.g., no letters, correctly placed negative signs).

Semantic Analysis: Validates the "meaning" and constraints, such as checking if the number is within the int range.

Code Generation: Produces the final result based on the processed logic.

Testing Phase: Simulates final execution verification.

💻 How to Run
Prerequisites: Ensure you have a C++ compiler installed (like g++).

Compile:

Bash

g++ -o evenlang main.cpp
Execute:

Bash

./evenlang
📝 Usage
Enter any integer (e.g., 42, -7, 1005) to see the compiler phases in action.

Type exit to close the program.

⚠️ Error Handling
The program includes built-in detection for:

Lexical Errors: Non-numeric characters (e.g., "abc").

Syntax Errors: Improper formatting (e.g., "--5").

Semantic Errors: Numbers too large for a standard 32-bit integer.
