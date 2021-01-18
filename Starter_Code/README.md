# Save Qualifying Loans

* As a user, I need the ability to save the qualifying loans to a CSV file so that I can share the results as a spreadsheet.

  * Given that I am using the loan qualifier command-line interface (CLI), when I run the qualifier, then the tool should prompt the user to save the results as a CSV file.
  
  * Given that there are no qualifying loans, when prompting a user to save a file, then the program should notify the user and exit.
  
  * Given that I have a list of qualifying loans, when I am prompted to save the results, then I should be able to opt out of saving the file.
  
  * Given that I have a list of qualifying loans, when I choose to save the loans, the tool should prompt for a file path to save the file.
  
  * Given that I am using the loan qualifier CLI, when I choose to save the loans, then the tool should save the results as a CSV file.
---

## Technologies

This project leverages python 3.7 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

* [pytest](https://docs.pytest.org/en/stable/) - For basic assertion testing of financial calculators and filters, and filio.

---

## Installation Guide


Before running the application first install the following dependencies.

```python
  pip install fire
  pip install questionary
  pip install pytest
  pip install mkdocs
```

---

## Usage


To use the loan qualifier application simply clone the repository and run the **app.py** with:

```python
python app.py
```

Upon launching the loan qualifier application you will be greeted with the following prompts.

![Loan Qualifier Prompts](Images/loan_qalifier.png)

---

## Contributors

stk714
---

## License

Python 3.7.9 64-bit ('dev': conda)
