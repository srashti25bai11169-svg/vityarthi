# vityarthi
Project Title : Python based Cgpa Calculator

Overview Of the Project: Objective: Develop a Python tool to automate the accurate calculation of SGPA and CGPA, replacing manual effort and error.
Architecture: The system uses a simple three-tier structure: CLI Input, Logic Functions (for calculation), and Formatted Output.
Reliability Design: decimal module is used universally for calculations to ensure $100\%$ mathematical accuracy and prevent floating-point errors.
Performance Design: Grade mapping relies on Python Dictionaries for fast, O(1) lookups to maintain quick processing speed.
Input Robustness: Immediate validation with try-except blocks handles non-numeric and invalid grade inputs robustly.
Key Learnings: Reinforced the necessity of the decimal module and the value of a modular design for maintainability and accuracy.
Future: Plan to enhance the tool with a GUI (e.g., Tkinter) and add a Predictive CGPA feature for academic planning.

Features:
SGPA & CGPA Calculation: Computes individual semester (SGPA) and overall (CGPA) weighted averages.
Grade Point Mapping: Instantly converts letter grades (e.g., 'A+') to numerical Grade Points (GP) using an internal dictionary.
High Precision: Uses the decimal module for all math to guarantee mathematical accuracy.
Data Validation: Performs immediate checks on input (credits and grades) to prevent errors.
Structured Output: Provides a clear, formatted CLI report summarizing all results.
Configurability: Allows easy adjustment of the Grade Mapping scale.

Technologies/Tools used:
Module: Used for all arithmetic (SGPA/CGPA) to ensure $100\%$ mathematical accuracy and avoid floating-point errors.
Dictionaries: Used for efficient Grade Mapping (Grade $\rightarrow$ Point) for fast performance.
Standard I/O: Implements the Command Line Interface (CLI) for input and output.
Lists: Used for structuring and managing course data across semesters.

Steps to install & run the project:
Prerequisites: Ensure Python 3.x is installed.
Setup: Download the project file (.py script); no external dependencies are required.
Run: Open the terminal, navigate to the file's directory, and execute the script using: python cgpa_calculator.py.
Interact: Follow the sequential prompts to input semester credits and grades; the final report will display in the terminal.

Instruction for testing:
Testing the CGPA Calculator focuses on three key areas:
Unit Logic: Verify all Grade Point (GP) conversions and confirm SGPA/CGPA formulas match manual calculations precisely.
Input Validation: Test with invalid inputs (text, negative numbers, bad grades) to ensure the system re-prompts instead of crashing.
System/Performance: Conduct a full, multi-semester run to check end-to-end accuracy and verify the calculation completes in under 1 second.

Screenshort:
![6064888E-2E38-4B92-895D-998911A25E33](https://github.com/user-attachments/assets/9bd26114-6b53-46a5-a78a-3d9bc161ecf5)
