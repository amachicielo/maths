# Applied Mathematics and Statistics Notebooks

A collection of Python notebooks used to practise statistical reasoning, probability, non-parametric methods, and numerical linear algebra.

## Notebook index

| Notebook | Focus |
| --- | --- |
| [hypothesis-testing.ipynb](hypothesis-testing.ipynb) | Null and alternative hypotheses, test statistics, p-values, and worked examples |
| [random-variables-and-distributions.ipynb](random-variables-and-distributions.ipynb) | Random variables, probability distributions, and SciPy statistics |
| [Nonparametric_Methods.ipynb](Nonparametric_Methods.ipynb) | Kernel density estimation and bandwidth selection |
| [leverrier-neptuno-numericalmethods-py.ipynb](leverrier-neptuno-numericalmethods-py.ipynb) | Leverrier's algorithm, eigenvalues, traces, and characteristic polynomials |

## Run locally

    python -m venv .venv
    # Windows: .venv\Scripts\activate
    # macOS/Linux: source .venv/bin/activate
    pip install jupyter numpy scipy pandas matplotlib seaborn sympy
    jupyter notebook

## Scope

These are learning notebooks rather than a reusable Python package. Their portfolio value is in showing the mathematical foundations behind data science work; production projects in this profile demonstrate engineering, testing, deployment, and automation.
