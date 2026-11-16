# Learn Modern AI Python

A notebook-based course for learning Python, from core language concepts to topics used in modern Python development. Each lesson is a Jupyter notebook with explanations and runnable examples.

## Course outline

| Lesson | Topics |
| --- | --- |
| [01](<Lesson 01 - Introduction to Python.ipynb>) | Python introduction, execution, and practical applications |
| [02](<Lesson 02_  Data Types.ipynb>) | Built-in data types |
| [03](<Lesson 03 - Operators, Keywords & Variables.ipynb>) | Operators, keywords, and variables |
| [04](<Lesson 04 - Strings & Type Casting.ipynb>) | Strings and type casting |
| [05](<Lesson 05 - Control Flow & Loops.ipynb>) | Control flow and loops |
| [06](<Lesson 06 - Lists, Tuples & Dictionary.ipynb>) | Lists, tuples, and dictionaries |
| [07](<Lesson 07 - The Set, Frozenset & GC.ipynb>) | Sets, frozensets, and garbage collection |
| [08](<Lesson 08 - Module & Functions.ipynb>) | Modules and functions |
| [09](<Lesson 09 - Exception Handling.ipynb>) | Exception handling |
| [10](<Lesson 10 - I_O File Handling.ipynb>) | File input and output |
| [11](<Lesson 11 - The Math & Date Time Calendar.ipynb>) | Math, date, time, and calendar |
| [12](<Lesson 12 - OOP_ Objects & Classes - Part 1.ipynb>) | Object-oriented programming, part 1 |
| [13](<Lesson 13 - OOP_ Objects & Classes - Part 2.ipynb>) | Object-oriented programming, part 2 |
| [14](<Lesson 14_ Metaclasses & Dataclasses.ipynb>) | Metaclasses and dataclasses |
| [15](<Lesson 15_ Pydantic & Generics.ipynb>) | Pydantic and generics |
| [16](<Lesson 16 - Asyncio.ipynb>) | Asynchronous programming with `asyncio` |
| [17](<Lesson 17 - CPython & GIL.ipynb>) | CPython and the GIL |
| [18](<Lesson 18_  Docstrings & MkDocs.ipynb>) | Docstrings and MkDocs |

## Getting started

You’ll need Python and a Jupyter environment. To use JupyterLab in a virtual environment:

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install jupyterlab
jupyter lab
```

Or open a notebook directly in VS Code with the Python and Jupyter extensions installed. Select the Python environment you want to use as the notebook kernel, then run cells from top to bottom.

Start with **Lesson 01** and continue in order. Lessons build on earlier material, though individual notebooks can also be used as references.

## Notebooks

Lesson files are stored in the repository root. Open any `.ipynb` file in JupyterLab or VS Code.

The repository does not include a shared dependency file. Most introductory lessons use the Python standard library; some later examples use third-party packages such as `requests`, `numpy`, `rich`, `pytest`, and `pydantic`. Install a package in the active notebook environment if a lesson requires it.

There are two Lesson 04 files: `Lesson 04 - Strings & Type Casting.ipynb` and `Lesson 04 - Strings & Type Casting(1).ipynb`. Their cell sources are identical; either file can be used.

## Working with the lessons

- Run cells in order when starting a lesson; later examples may rely on earlier definitions.
- Use a fresh kernel to repeat a lesson from a clean state.
- Keep any package installations in the same environment selected for the notebook.
- Treat file-handling examples as working in the notebook's current directory.

## Repository contents

This repository is a collection of learning notebooks, not an installable Python package or a single application. It has no project-wide test suite or pinned environment at present.
