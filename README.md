# Python PEP8 pre-commit template
Python template repository with pre-commit hooks

## Hooks

* check-yaml - 4.3.0
* isort - 5.10.1
* autopep8 - 2.0.0
* flake8 - 5.0.4

## How to use

```sh
# Install virtual environment
python3 -m venv venv

# Activate virtual environment
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt --upgrade pip

# Install pre-commit hooks
pre-commit install

# Check your code manually
pre-commit run
check yaml...........................................(no files to check)Skipped
isort................................................(no files to check)Skipped
autopep8.............................................(no files to check)Skipped
flake8...............................................(no files to check)Skipped

# Your code will be checked on every commit
git commit -m "First commit"
check yaml...........................................(no files to check)Skipped
isort....................................................................Passed
autopep8.................................................................Passed
flake8...................................................................Passed
[main 723dacf] First commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 test.py
```