# Python package template

Example package template. You can run and install with:

```bash
git clone https://github.com/Chicago-Club-Management-Company/python_package_template
pip install python_package_template/
```

or, with dev packages, and running the CI/CD:

```bash
git clone https://github.com/Chicago-Club-Management-Company/python_package_template
cd python_package_template/
pip install python_package_template/[dev]
pytest
ruff check cool_package/
mypy cool_package/
```