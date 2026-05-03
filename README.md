# Pixelssuite Automation Test

## Description
This project tests the preview functionality of the Pixelssuite website using Playwright.

## Feature Tested
Image Format Conversion (PNG Preview)

## Setup Instructions
1. Install Python
2. Run:
   pip install playwright openpyxl
   playwright install

## How to Run
python image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png"

## Output
- execution_results.csv (test results)
- results/preview_pass.png (screenshot evidence)

## Conclusion
The preview functionality works correctly when a valid PNG image is uploaded.
