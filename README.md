# MiniTAC Compiler

## Overview

MiniTAC Compiler is a Python-based educational compiler designed to demonstrate the internal working of a compiler through different stages of compilation. It converts source code into Three-Address Code (TAC), applies various optimization techniques, performs control-flow and liveness analysis, eliminates unnecessary instructions, and executes the optimized code.

The project features an interactive **Streamlit dashboard** that provides visual representations of each compiler phase, making complex compiler design concepts easier to understand and explore.

## Features

- **Lexical Analysis:** Converts source code into tokens by identifying keywords, identifiers, operators, and constants.
- **Syntax Analysis:** Validates program structure and generates an Abstract Syntax Tree (AST).
- **TAC Generation:** Translates the AST into Three-Address Code.
- **Code Optimization:** Implements constant folding, constant propagation, algebraic simplification, copy propagation, and common subexpression elimination.
- **Control Flow Graph:** Represents program execution through basic blocks and control-flow connections.
- **Liveness Analysis:** Determines which variables are required during program execution.
- **Dead Code Elimination:** Removes unnecessary temporary instructions to improve code efficiency.
- **Program Execution:** Executes the optimized TAC and displays the final output.
- **Code Complexity Analyzer:** Evaluates program structure and complexity.
- **Learn Mode:** Provides explanations of compiler phases through an interactive learning interface.

## Technology Stack

- Python
- Streamlit
- HTML and CSS
- Pytest

## Installation and Execution

**1. Clone the repository**

```bash
git clone <repository-url>
```

**2. Navigate to the project directory**

```bash
cd MiniTAC-Compiler
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

**4. Run the application**

```bash
streamlit run app.py
```

## Project Objective

The objective of MiniTAC Compiler is to provide hands-on experience with compiler design and optimization techniques. By combining compiler implementation with interactive visualization, the project helps users understand how source code is analyzed, transformed, optimized, and executed step by step.
