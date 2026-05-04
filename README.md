# Test Automation UI

## Prerequisites

- Python 3.8+ installed
- Command Prompt (or PowerShell) opened in project directory:
  `D:\IT23626492_Assignment 1_test_automation_ui`

## Install dependencies (one-time)

Run the following commands from the current directory:

```bash
pip install -U pip
pip install playwright openpyxl
playwright install
```

## Run the test

Run the automation test script:

```bash
python IT23626492_image_preview_test.py
```

Optional (headless mode):

```bash
python IT23626492_image_preview_test.py --headless
```

## Output

After execution, the script generates:

- Screenshot(s) in the `results` folder
- CSV test report in `execution_results.csv`
