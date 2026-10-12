# Mathematical Reasoning with Python

A small, reproducible portfolio demonstrating mathematical problem-solving, Python implementation, and independent verification.

## Goals

- Explain mathematical ideas clearly and accurately.
- Translate formulas into readable Python.
- Verify computational answers using an independent method when practical.
- State assumptions, interpret results, and acknowledge limitations.

## Repository structure

```text
mathematical-reasoning-with-python/
├── README.md
├── requirements.txt
├── .gitignore
└── notebooks/
    ├── 01_probability.ipynb
    ├── 02_statistics.ipynb
    ├── 03_linear_algebra.ipynb
    └── 04_calculus.ipynb
```

## Getting started (Windows + VS Code)

1. Install Python and the **Python** and **Jupyter** extensions in VS Code.
2. Open this folder in VS Code.
3. Create a virtual environment in the terminal:

   ```powershell
   py -m venv .venv
   .\.venv\Scripts\Activate.ps1
   python -m pip install --upgrade pip
   pip install -r requirements.txt
   ```

4. Open a notebook in `notebooks/` and select the `.venv` Python kernel.
5. Run **Restart Kernel and Run All Cells**. Confirm the outputs are consistent with the explanations.

If PowerShell blocks activation, you can use the interpreter directly:
`.\.venv\Scripts\python.exe -m pip install -r requirements.txt`.

## Notebook method

Each worked problem should include:

1. **Problem and assumptions**
2. **Mathematical reasoning**
3. **Python implementation**
4. **Independent verification**
5. **Interpretation and limitations**

Do not treat code output as proof by itself. Check formulas, assumptions, edge cases, and units.

## Current status

This is a starter portfolio. Review every notebook, run all cells, and improve the explanations in your own words before presenting it as your work. Add new problems only when you can explain and verify them.

## Author

**Tanvir Ahammod**  
Mathematics graduate | Python | Mathematical reasoning

- GitHub: https://github.com/tanvirahammod76
- LinkedIn: https://www.linkedin.com/in/tanvir-ahammod/

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
